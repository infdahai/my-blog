---
title: 工业数据集洞察 · Facet-0 / ManuFacet-1K（NTU PINE Lab）
description: 接触富集精密装配：力同步工业数据 + 语义-接触基础模型；对数据×训练/R4/R6 的洞察
tags: [insight, industrial-dataset, force, contact-rich, R4, R6]
created: 2026-08-28
url: https://pine-lab-ntu.github.io/facet-0/
---

# 工业数据集洞察 · Facet-0 / ManuFacet-1K

> 来源：[项目页](https://pine-lab-ntu.github.io/facet-0/) · PDF `assets/paper/Facet-0.pdf` · HF [ManuFacet-1K](https://huggingface.co/datasets/Pinelab/ManuFacet-1K) / [FACET-0](https://huggingface.co/Pinelab/Facet-0)
> 机构：NTU PINE Lab（Data Foundry）· 通讯 Ziwei Wang
> 口径：**调研洞察**，不实跑。核验级别：项目页+PDF 摘要/§3 已核；arxiv id 页面链到 PDF，未给标准 arxiv 编号（⚠ 若后续有 arxiv 再补）。

---

## 1 · 一句话定位
**不是又一个通用 VLA 数据集**，而是专门为 **±0.5 mm 接触富集精密装配** 打造的：
- **ManuFacet-1K**：~1000h **力同步(force-synchronized)** 工业装配数据（演示 + 闭环 rollout）
- **FACET-0**：在其上训的工业基础模型——**预测并评估动作的接触后果**（joint action–wrench），0.5 mm 精度

---

## 2 · 数据集设计（ManuFacet-1K）— 研究员该看的点

### 2.1 规模与构成（PDF §3）
| 项 | 数值 |
|---|---|
| 总时长 | ~**1,000 h**（演示 + 闭环 rollout + 人干预） |
| 可训时长(站页) | ~642 h trainable（站页 live 数字，论文写 ~1000h 含更广） |
| 任务 | CPU 37.3% / RAM 21.9% / Disk 23.4% / GPU 17.3% |
| 本体 | **3 embodiments**：UR7e(主) / xArm / Franka，**同一 schema** |
| 采集点 | 多中心网络，2 机箱族（Dell T5810 72% / T1700 28%） |
| 动作分辨率 | **0.5 mm** |
| 传感 | 腕部 6 轴 F/T · 3 RGB · 关节本体感 · 并行夹爪 |
| 状态 | 每帧 13-D：`s = [x∈R6; g∈R; w∈R6]`（位姿+开合+wrench） |
| 时钟 | 站页：160 Hz state / 15 Hz vision |
| 标注 | VLM 子任务/指令；**7 相 skill-phase taxonomy** |
| QA | 站页 ~90% pass；失败+恢复段**保留**（recovery-rich） |

### 2.2 设计签名（相对 OpenX / AgiBot World 的差异）
1. **力是一等公民，不是附加模态**：每帧 wrench 与位姿对齐；kinesthetic 力反馈遥操，力调节是**有意**的。
2. **接触相 taxonomy（7 相）**：approach / align / insert / press / seat / fasten / retreat —— 其中 5 个接触相是少数帧但承载多数结果信息；峰力呈双峰（对齐低力 / seating 高约一个数量级）。
3. **统一 schema 跨本体**：不是"多数据集拼盘"，而是**同一传感+状态+相词汇**跨 3 本体/多产线。
4. **数据飞轮**：异常纠正轨迹**保留**进 corpus（不是扔掉失败）→ deployment experience 回流。
5. **工业公差直接进任务定义**：任务/成功标准来自合作产线，不是实验室玩具。

### 2.3 论文 Table 1 的关键对比（公开数据里制造装配极稀缺）
| 数据集 | 规模 | Sync F/T | 时序标签 |
|---|---|---|---|
| Open X-Embodiment | 1.4M traj | mixed | mixed |
| AgiBot World | 2,976 h | n/r | sub-step |
| FMB | ~31 h | ✓ | stage |
| REASSEMBLE | ~13 h | ✓ | action/skill |
| **ManuFacet-1K** | **~1,000 h** | **✓** | **contact phase** |

站页金句：**公开机器人数据里 <1% 触及制造装配**；OpenX+AgiBot 等 ~11k h 泛用 vs 制造装配公开仅 ~44 h（REASSEMBLE+FMB）——ManuFacet 把这一格拉到 1000h。

---

## 3 · 模型设计（FACET-0）— 与数据如何咬合

核心对象不是"更大的 VLA"，而是 **semantic–contact representation**：把"任务意图"与"运动将引发的接触"绑在同一表示里。

流水线（站页+摘要）：
1. **Robotic Reasoning VLM**（~5–10 Hz）：语义规划 + 子任务跟踪 → 粗 reference action-force chunks
2. **Force-Residual Head**（~20 Hz）：力历史 → Δa 修正 → 细 action-force chunks，0.5 mm
3. **Safety Critic**：`Q(s,z,f,a)` 门控，接触安全包络
4. **执行** ~200 Hz 柔顺接触感知控制

训练三阶段：
- **Pre-train**：遥操装配 + assembly-VQA（"该怎么做、该什么手感"）
- **Post-train（真机 RL）**：+45% success / −40% cycle time / +60% failure recovery（站页）
- **Adapt**：少样本、安全有界迁移；~6.6% 权重，+30% adapted success

摘要硬结果：**5 个亚毫米 PC 装配任务 mean success 82% vs 最强 baseline 15%**；0.5 mm 放置精度；50 ms 指令延迟。

关键技术选择：
- **flow matching** 同时生成 action chunk **与** 预期未来腕部 wrench profile（joint action–wrench proposal）
- **Action–Wrench Critic** 区分"任务进度相似但接触后果不同"的运动 → 接触选择性 credit
- RL 定义在**可执行笛卡尔动作**上；辅助 wrench head 保持预测性、**非指令**的 action–contact 耦合（力不是直接当命令乱喷）

---

## 4 · 对「数据×训练」主线的洞察（重点）

### I1 · Scaling ≠ Precision —— 数据**类型**比数据**规模**更决定接触任务上限
通用 VLA 数据（OpenX / AgiBot）堆到上千～上万小时，仍几乎不覆盖 **接触判断 / 力修正 / 卡滞恢复**。ManuFacet 的主张是：跨过 ±0.1–0.5 mm 插入，需要**为接触而建的数据集**，不是再堆视觉示范。
→ 映射我们纲领：**R4 真机遥操在"精密接触"上不可被 R1 EGO / R3 仿真简单替代**；EGO 人视频几乎给不出亚毫米 wrench 真值。

### I2 · 力/接触不是"多一个传感器"，而是**监督对象本身**
Facet-0 把 wrench profile 与 action **联合生成+联合评价**。这比"VLA + 力输入拼接"更强：接触后果进入表示与 credit。
→ 映射 **R6 物理/接触/触觉**：它石 WIYH 的 VLTA 是"触觉进数据标准"；ManuFacet 是"**力进动作生成与价值**"。两者同属 R6，但工业线把 R6 推到了**可执行闭环**（不只是模态并列）。

### I3 · 接触相 taxonomy = 工业版 "L3 时域原子动作"
我们 L0–L4 量尺里 L3=时域事件。ManuFacet 的 7 相（尤其 5 个接触关键相）是**为接触结果服务的 L3**，比 EPIC verb-noun 或 Open-AoE 原子动作更贴物理。
→ 启示：EGO/通用操作的 L3 若要对接触任务有用，可能需要**力/接触条件化的相标注**，而不是纯语义分割。

### I4 · "失败+恢复保留"是数据飞轮，不是 QA 垃圾
多数数据集扔掉失败；ManuFacet 把 anomaly-corrected 轨迹留作 flywheel，post-train RL 直接吃 deployment experience。
→ 对 R4/工业数据路线：评测与采集协议应**显式保留接触失败模态**，否则策略永远学不会 recovery（站页 +60% recovery 即来自于此）。

### I5 · 统一 schema × 少本体 > 大杂烩多本体（在精密域）
OpenX 的跨本体是格式拼盘；ManuFacet 是 **3 本体 + 同一 13-D 状态 + 同一相词汇 + 同一 F/T 同步**。精密域的跨本体红利来自**对齐的接触接口**，不是本体数量。
→ 与我们 **R5 统一动作空间** 合流：工业精密线的"统一"必须含 **wrench 通道**，纯位姿统一动作空间在插入任务上会不够。

### I6 · 与 EGO/企业数据版图的位置
| 路线 | 代表 | ManuFacet 相对位置 |
|---|---|---|
| R1 人/EGO | EgoSuite / Open-AoE | 正交：EGO 无亚毫米 wrench；不能替代本域 |
| R3 仿真 | GR00T/Cosmos | 互补但危险：接触 sim2real 是经典深坑；本工作选择**真机力同步** |
| R4 真机 | AgiBot World | **同哲学、不同regime**：AgiBot 广任务通用操作；ManuFacet 窄任务极高精度+力 |
| R6 接触 | WIYH / HRDexDB / CHORD | **工业闭环标杆**：规模(1000h) × 力同步 × RL post-train |

**产业含义**：Data Foundry 路线 = "工业接触数据基础设施"——与光轮(人行为规模)、它石(VLTA)、智元(通用真机)、NVIDIA(仿真) 并列的**第五条供给哲学：精密力同步工业数据**。

---

## 5 · 局限（洞察用，非贬低）
- 任务仍偏 **3C/PC 装配**（汽车/航发 inspection 标为 next up）——精密域内泛化 vs 跨行业泛化未证。
- 1000h 相对 OpenX 仍小，但**单位小时信息密度**（力+相+恢复）可能高一个量级——应用"有效小时"而非"原始小时"比较。
- 力是腕部 F/T，不是分布式触觉皮肤；与 GelSight/MimicTouch 的空间触觉仍是不同粒度。
- 开源程度：HF 有 model/dataset；论文 PDF 在项目页；标准 arxiv id 待补。

---

## 6 · 一句话口径（可进纲领/路线图）
**ManuFacet-1K / Facet-0 证明：接触富集精密制造的瓶颈不是"再来一个通用 VLA"，而是"力同步 + 接触相标注 + 失败保留"的工业数据协议；在该协议上，action–wrench 联合生成+真机 RL 把亚毫米装配从 ~15% 拉到 ~82%。对数据×训练：R4/R6 在精密域必须升格为"力是监督对象"，且 EGO/仿真无法廉价替代这一格。**
