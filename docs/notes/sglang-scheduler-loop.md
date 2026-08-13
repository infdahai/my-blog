---
title: SGLang 架构 02 · Scheduler 循环
description: 请求进了 waiting_queue 之后，怎么被组进 batch、怎么和上一拍重叠、KV 不够时谁被踢回去。延迟真正产生的地方。
tags: [sglang, architecture, scheduler]
date: 2026-08-13
---

# SGLang 架构 02 · Scheduler 循环

上一篇把请求送到 Scheduler 门口。这篇只回答：

> 它进门之后，怎么排队、怎么组 batch、怎么和 GPU 重叠、KV 不够时谁出局。

源码主文件：

- `python/sglang/srt/managers/scheduler.py`（4300+ 行，先只读循环）
- `schedule_batch.py` 的 `Req` / `ScheduleBatch.retract_decode()`
- `schedule_policy.py` 的 `SchedulePolicy` / `PrefillAdder`

PD、spec、HiSparse、dllm 先当旁路。默认假设：单机、普通 generate、`disaggregation_mode=NULL`。

## 先记住四个容器

`init_running_status()` 里就这几样：

| 名字 | 类型 | 住着谁 |
|---|---|---|
| `waiting_queue` | `List[Req]` | 已 tokenized、还没上 GPU |
| `running_batch` | `ScheduleBatch` | 正在 decode 的连续批 |
| `cur_batch` | 当前这一拍要 `run_batch` 的 | 可能是新 prefill，也可能是 running decode |
| `last_batch` | 上一拍 | overlap 时，这一拍 GPU 跑着，CPU 还在收上一拍的结果 |
| `chunked_req` | 单个 `Req` 或空 | 一次吃不完的超长 prefill，下一拍接着切 |

再加两个别和它们搞混：

- Tokenizer 的 `rid_to_state` 在主进程，Scheduler 看不见
- Scheduler 的 `Req` 才占 KV。两边只靠 `rid` 对齐

`Req` 里现在就要认识的字段：

- `prefix_indices`：radix 已经命中、不用重算的前缀
- `is_retracted`：刚被从 decode 踢回 waiting
- `extend_range`：这一拍还要 prefill 多长
- `priority`：可选。没开 priority scheduling 时乱传会被拒

## 循环长什么样

默认走 `event_loop_overlap()`。`event_loop_normal()` 是教学版：跑完一拍，立刻处理结果，再跑下一拍。生产默认把 CPU 和 GPU 错开。

把 overlap 压成人话：

```text
while True:
    收新请求，丢进 waiting_queue
    如果引擎 pause，本拍什么都不跑

    batch = get_next_batch_to_run()     # 决定这一拍是 prefill 还是 decode
    把 batch 扔给 GPU：run_batch()
    把 (batch 副本, 结果句柄) 推进 result_queue

    弹出上一拍，process_batch_result()  # 完成 / 继续 / 流式回包
    如有需要，基于上一拍结果做 sampling / grammar
    last_batch = 这一拍
```

关键点：**GPU 在跑第 N 拍时，CPU 在收第 N-1 拍的结果，并准备第 N+1 拍。**  
这就是 v0.4 说的 zero-overhead scheduler。代价是状态永远“慢一拍”，debug 时你看到的 `running_batch` 不一定是 GPU 正在算的那个。

两种情况会关掉 overlap，退化成同步：

- 连续两拍都是 prefill，并且开了 `SGLANG_DISABLE_CONSECUTIVE_PREFILL_OVERLAP`。为了第一段的 TTFT，宁可吞吐差一点
- spec + grammar 还没打通，那一拍强制同步

MLX / 你的 Mac 走的是另一份 `event_loop_overlap_mlx`。语义接近，实现不是这份。在 4090 上读这篇对应的 CUDA 循环。

## 请求怎么进 waiting_queue

`process_input_requests()` 不做调度。它只是一个分发器：

1. 可能先收割过期 session
2. 健康检查在忙的时候直接吞掉
3. `_request_dispatcher(recv_req)` 按类型分到 handler
4. 普通生成落到 `handle_generate_request()`

`handle_generate_request()` 把 `TokenizedGenerateReqInput` 做成 `Req`，然后 `_add_request_to_queue()`。

默认（非 PD）就是三步：

1. 校验 / 补默认 priority
2. 队列满了就 abort 新来的或挤掉更低优先级的
3. `waiting_queue.append(req)`，打上入队时间

HiCache 打开时，这里会顺手 `_prefetch_kvcache()`，让后面的 prefix 尽量已经在附近。Q1 先当它是优化，不是主路径。

session 请求在这里分叉：带 `session_params.id` 的走 session 树，radix-native 的只用顶层 `session_id`。下一篇 cache 再展开。今天只要知道：**大多数机器人一步控制，如果没开 session，就是普通 Req，每次都当新前缀来匹配。**

## 一拍选谁跑：`get_next_batch_to_run()`

这是 Scheduler 的心脏。顺序固定，不要凭直觉重排。

```text
1. 处理挂起的 chunked abort、等待超时、运行超时
2. 如果上一拍是 prefill（extend）：
      把已经 prefill 完的人 merge 进 running_batch
      还没切完的那个人留在 chunked_req，不进 decode
3. 尝试组一个新的 prefill batch：get_new_batch_prefill()
4. 若有新 prefill → 这一拍跑 prefill（优先）
   否则 → update_running_batch()，这一拍跑 decode
5. 打上本拍调度时间，返回
```

一句话：**有能 prefill 的，先 prefill；没有，才让正在 decode 的人再往前走一步。**

这对吞吐是对的，对机器人是刀。一张新图进来，正在 50Hz 吐动作的请求可能被按住一拍。后面讲 priority / prefill delayer，根子都在这句。

`running_batch.batch_is_full` 是个闸。满了就不再从 waiting 拉人，除非开了 priority preemption，允许把 decode 里的人挤回去。

## Prefill 怎么组：`PrefillAdder`

`get_new_batch_prefill()` 真正干活的是 `PrefillAdder`。

先看要不要组：

- waiting 空，且没有未切完的 `chunked_req` → 不组
- 可分配请求槽用完（`req_to_token_pool` / `pp_max_micro_batch_size`）→ 标满，不组
- `min_free_slots_delayer` 觉得 KV 太紧 → 故意推迟 prefill，给 decode 留空
- 测试 retract 时，也会故意不组 prefill，把人堆在 waiting 里

然后：

1. `policy.calc_priority(waiting_queue, running_batch)` 排序
2. 如果有 `chunked_req`，先把它的下一刀放进 adder
3. 按排好的 waiting 一个个 `init_next_round_input(tree_cache)` + `adder.add_one_req()`
4. adder 说 `CONTINUE` 就继续塞；`NO_TOKEN` 或其他原因就停
5. 被选中的人从 `waiting_queue` 拿掉，做成新的 `ScheduleBatch`，`prepare_for_extend()`

`init_next_round_input(tree_cache)` 是 radix 命中发生的地方。`Req.prefix_indices` 在这里被填上。命中越长，这一拍要 extend 的 token 越少。

政策（`SchedulePolicy`）现在认识这几个就行：

| 政策 | 意识 | 行为 |
|---|---|---|
| `fcfs` | 无 cache | 先来先走；开了 priority 就先比 priority |
| `lpm` | 有 cache | 最长前缀命中优先 |
| `dfs-weight` | 有 cache | 沿 radix 树深度加权 |
| `lof` | 无 cache | 预计输出更长的优先 |

waiting 超过 128 时，LPM 会退化成 FCFS，避免每次排序都去扫树。  
机器人连续控制如果共享同一段 system prompt，LPM 会把它们聚在一起打，cache 更甜；如果每步都是新图、前缀几乎不共享，LPM 帮不上忙，还浪费排序。

`PrefillAdder` 还会干两件脏活：

- **chunked prefill**：单请求太长，切成多拍 extend。切到一半的人挂在 `chunked_req`，下一拍优先继续切，避免 KV 悬空泄漏
- **preempt**：priority 模式下，为了让高优先级 prefill 进来，把 running 里的人踢回 waiting

多模态还有一条显式限制：Transformers 后端的 VL 模型会关掉 chunked prefill，怕图被切到一半对不上。原生 VLM 路径另说，不要默认“带图也能随便 chunk”。

## Decode 怎么往前走：`update_running_batch()`

没有新 prefill 时，对 `running_batch` 做：

1. `filter_batch()` 扔掉已经结束的
2. 空了就返回
3. `check_decode_mem()`：每人再往前走一个 token，KV 还够不够
4. 不够就 `retract_decode()`
5. 够就让 `new_token_ratio_tracker` 衰减一步，准备 `run_batch()`

retract 的规则在 `ScheduleBatch.retract_decode()`，很粗，注释自己都写了 TODO：

- 非 spec：按「输出已经很长、输入相对短」的人优先踢。理由是他们占的 decode KV 多，踢了立刻腾得出空
- spec：只能从队尾踢，因为 `filter_batch` 的 API 限制
- 至少留一个人。最后一人还是装不下，就 abort，而不是把 Scheduler 弄崩
- 被踢的人 **不写回 radix**。注释写明：空间要立刻用，来不及插入
- 踢完回到 `_add_request_to_queue(..., is_retracted=True)`，重新走 waiting

对机器人，retract 等于这一步控制直接丢拍。P99 尖刺经常是它，不是模型变慢。日志关键字：

```text
KV cache pool is full. Retract requests. #retracted_reqs: ...
```

看见它，先看是不是有人把超长 prefill 和一堆短 decode 挤在同一张卡上。

## `run_batch()` 和回程

`run_batch()` 是 Scheduler 和 GPU worker 的边界。这篇只记接口：

- `forward_ct += 1`
- overlap 打开时，在 `forward_stream` 里等 schedule stream，再 `forward`
- 返回的是结果句柄，不是已经 decode 完的 Python list
- overlap 下，真正把 token 写回 `Req`、决定结束还是继续，发生在下一拍的 `process_batch_result()`

`process_batch_result()` 已经拆到 `scheduler_components/batch_result_processor.py`：

- prefill 结果 → 人进 `running_batch`，或继续当 `chunked_req`
- decode 结果 → 追加 token，结束的人走 Detokenizer，没结束的留在 running
- idle → 空转自检

流式输出从这里经 Detokenizer 回到 Tokenizer 的 `rid_to_state`。架构 01 的回程，源头就是这一拍。

## 延迟对照表，接上一篇

上一篇写到「出站」。现在可以往下填。

| 阶段 | 函数 | 机器人会怎么痛 |
|---|---|---|
| 入队 | `_add_request_to_queue` | 队列有上限；满了直接 abort |
| 排序 | `calc_priority` | 没共享前缀时 LPM 是空转 |
| 等槽 | `batch_is_full` / delayer | 新图来了，decode 可能被故意保护，或反过来被抢 |
| 组 prefill | `PrefillAdder.add_one_req` | 图太大就 chunk，TTFT 被切成多拍 |
| 先 prefill 后 decode | `get_next_batch_to_run` | 别人的一张图，能打断你的动作 decode |
| retract | `retract_decode` | 正在吐动作的请求被踢回 waiting，本周期作废 |
| overlap 慢一拍 | `event_loop_overlap` | 你 debug 看到的状态，不是 GPU 正在算的状态 |
| 连续 prefill 关 overlap | `is_disable_overlap_for_batch` | 两张图连着来，第一张 TTFT 优先 |

Q1 在 4090 上做实验，不要看平均值，看这三件事有没有发生：

1. 日志里有没有 retract
2. 一张新图进来时，已经在 decode 的请求 ITL 有没有跳
3. 同一 system prompt 第二次来，`prefix_indices` 是不是明显变长

## 建议你怎么读代码

仍然按一次循环走，不要从 `Scheduler.__init__` 的两千行初始化啃。

1. `init_running_status()`，认容器
2. `event_loop_normal()` 先读懂同步版，再读 `event_loop_overlap()`
3. `handle_generate_request()` 扫到 `_add_request_to_queue()` 即可
4. `get_next_batch_to_run()` 整函数，画一张「prefill 优先」的分支图
5. `_get_new_batch_prefill_raw()` 里 for waiting 的那一圈
6. `update_running_batch()` + `retract_decode()`
7. `run_batch()` 只看到调用 `tp_worker` 为止
8. `batch_result_processor.py` 的函数名扫一遍，先不进细节

过关标准：能讲清下面四句。

- waiting 和 running 分别是谁
- 为什么有新 prefill 时 decode 要让路
- chunked_req 为什么必须下一拍接着切
- retract 之后请求还在不在，KV 还在不在

## 下一篇预告

**03 · Radix 与 Session**：`init_next_round_input(tree_cache)` 里到底命中了什么，`session_id` / `session_params` 如何让连续控制不用每步重做 system prompt。

那篇之前，先在 `gpu` 那台 4090 上跑一个小模型，盯一眼镜子里的 retract 和 queue。纸上的循环，要对上一次真实日志。

## 我的笔记
