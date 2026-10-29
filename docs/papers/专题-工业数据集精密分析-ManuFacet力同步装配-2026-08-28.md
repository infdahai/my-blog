---
title: 专题 · 工业数据集精密分析（ManuFacet / 力同步装配）
description: 单专题深析：工业接触富集数据协议、ManuFacet-1K/Facet-0、与A/B/C/E供给哲学对照、对数据×训练的含义
tags: [专题, industrial-dataset, ManuFacet, force, 精密分析]
created: 2026-08-28
feishu_wiki: https://huazhi-ai.feishu.cn/wiki/XpPrw2vwWiN7SVkvVr3c4fmMnRd
feishu_docx: WXjod70yhooiKVxPGsqcpbxcn7a
parent_wiki: VTB4wrwB2im3IvkS1SUcCQLHnKb
---

# 专题 · 工业数据集精密分析（ManuFacet / 力同步装配）

> **文档性质**：单专题深度调研（insight），非实验执行清单。  
> **飞书位置**：主文档「数据论文分析」下的**子文档**（不堆主文档章节）。  
> **核心样本**：NTU PINE Lab · ManuFacet-1K / Facet-0  
> **项目页**：https://pine-lab-ntu.github.io/facet-0/  
> **核验**：项目页 + 论文 PDF §1–§3 + HF 卡片；arxiv 标准编号页面未给（⚠ 待补）。

---

## 0 · 本专题要回答的问题

1. **工业数据集**和通用真机数据集（AgiBot / OpenX）差在协议层的哪几条硬约束？  
2. 为什么「再堆通用 VLA 数据」跨不过亚毫米装配？  
3. ManuFacet 的数据协议（力同步 / 接触相 / 失败保留 / 同 schema）各自解决什么机制问题？  
4. Facet-0 如何把协议变成可训练监督（action–wrench 联合）？  
5. 这对我们「数据×训练」五条供给哲学与 R4/R5/R6 意味着什么？

**一句话预告**：工业精密域的瓶颈是**数据协议**，不是模型牌子；协议 = 力同步 × 接触相标注 × 失败保留 × 公差进成功判据。

---

## 1 · 问题背景：制造装配仍是具身的「硬骨头」

站页问题陈述（可核验）：
- 装配 / 插入 / 紧固 / 对齐仍高度依赖人工，对零件与布局变化脆。  
- 例子：航发 ~18,000 零件；半导体贴装 ±5–25 µm；美国制造岗位缺口量级（Deloitte 引用）。  
- 两种现状都不够：  
  - **预编程自动化**：单任务高效，改型/变体贵、专家示教重。  
  - **人工**：灵活，但短缺、疲劳、安全与一致性。  

提出的第三条路：**数据驱动制造智能**——用**真实工业数据**训基础模型，跨零件/布局/批次适应，产线边部署边改进。

**关键论断（站页金句）**：  
> **Scaling ≠ precision** — 差距在 manufacturing data。  
> 公开机器人数据里 **&lt;1%** 触及制造装配；规模买到的是泛化，不是 ±0.1 mm 插入所需的接触判断、力修正与恢复。

| 对照 | 规模 | 含义 |
|---|---|---|
| 通用公开数据（OpenX 等合计口径） | ~11,000 h 量级 | 广，但几乎不碰制造装配接触 |
| 制造装配公开（REASSEMBLE + FMB） | ~44 h | 有力/阶段，但太小 |
| **ManuFacet-1K** | **~1,000 h** | 力同步精密装配，把这一格拉起一个数量级 |

论文 Table 1 进一步钉死：OpenX / AgiBot World 在 Sync F/T 上为 mixed / n/r；FMB(~31h)、REASSEMBLE(~13h) 有 F/T 但规模小；ManuFacet 同时具备 **~1000h + Sync F/T + contact phase + long-horizon**。

---

## 2 · ManuFacet-1K：数据协议精拆

### 2.1 构成（PDF §3.1，已核）

| 维度 | 规格 |
|---|---|
| 时长 | ~**1,000 h**（开环遥操演示 + 闭环 rollout + 人干预） |
| 任务配比 | CPU 37.3% · RAM 21.9% · Disk 23.4% · GPU 17.3% |
| 本体 | **3**：UR7e（主采集）· xArm · Franka；**同一 schema** |
| 机箱/产线变体 | Dell Precision T5810 ~72% · T1700 ~28%（full/mid tower） |
| 传感 | 腕部 **6 轴 F/T** · 3 RGB · 关节本体感 · 平行夹爪 |
| 状态每帧 | \(s_t = [x_t \in \mathbb{R}^6;\ g_t \in \mathbb{R};\ w_t \in \mathbb{R}^6]\)（位姿+开合+wrench）共 **13-D** |
| 动作分辨率 | **0.5 mm** |
| 时钟（站页） | ~160 Hz state · ~15 Hz vision |
| 语言 | VLM 生成 sub-task / instruction，复用于预训练、奖励分解、适配 |
| 发布 | 数据卡、去标识中心 ID、策展代码；HF：Pinelab/ManuFacet-1K |

站页运营向数字（与论文 ~1000h 口径可并存：可训子集 vs 全 corpus）：~642 h trainable、~25k curated episodes、QA ~90% 等——**分析以论文 §3 为准，站页作动态补充**。

### 2.2 七相接触 taxonomy（§3.2）— 工业版「L3」

```
approach → align → insert → press → seat → fasten → retreat
         \__________ 五个接触意图相（critical）__________/
```

研究员要点：
1. **相 ≠ 评测动词**：相描述轨迹内时间交互体制；评测 skill verb 是子目标，一个 verb 可跨多相。  
2. **信息密度偏斜**：接触相帧是少数，但承载**多数结果信息**。  
3. **力的双峰**：低力对齐模 vs seating 模（约高一个数量级）——说明若只学视觉/平均力，会抹掉关键模式。  
4. **可寻址**：相边界采集时标记 + 离线 VLM 校验；分歧重标 → 预训练 / 奖励分解 / action–wrench 条件化都有统一索引。

→ 映射我们 L0–L4：**这是为接触结果服务的 L3**，比 EPIC verb-noun 或纯语义原子动作更贴物理。EGO 线的 L3 若要服务插入类任务，缺的是**力条件化相结构**，不是更多自然语言。

### 2.3 采集与策展五步（§3.3）

1. 时间戳多模态同步  
2. 段级有效性抽取  
3. 基于显著性的 action-chunk 采样  
4. VLM 辅助子任务/指令监督  
5. 异常纠正，**纠正后轨迹保留进飞轮**

**设计签名：失败不是垃圾。** 多数通用数据集过滤失败；工业接触里失败模态（卡滞、偏置、过压）恰恰是 post-train RL 与 recovery 的燃料。站页 post-train：**failure recovery +60%**，与此协议直接相关。

### 2.4 遥操形态

力矩控制臂 + 力反馈 kinesthetic 遥操 → 力调节是**操作者有意行为**，不是事后贴的传感器噪声。这对「wrench 作为监督」至关重要：标签分布反映策略意图，而非随机碰撞。

---

## 3 · Facet-0：协议如何变成模型

### 3.1 要学的对象

不是「更大的 VLA」，而是 **semantic–contact representation**：把「任务语义意图」与「运动将引发的接触后果」绑在同一表示里。

摘要机制：
- 因果 **wrench 历史** 与 视觉–语言语义、运动学状态对齐  
- **flow matching** 生成每个 action chunk **以及** 它预期诱发的未来腕部 wrench profile（**joint action–wrench proposal**）  
- 部署 rollout 训 **distributional Action–Wrench Critic**：区分任务进度相似但接触后果不同的运动  
- **phase-aware rewards + contact-selective credit** 把改进集中在决定性交互  
- 轻量 **bounded actor** 复用冻结表示做 on-robot 适配；RL 定义在可执行笛卡尔动作上；辅助 wrench head 保持**预测性、非指令**的 action–contact 耦合（力不是乱当命令喷）

### 3.2 系统分层（站页）

| 层 | 频率 | 作用 |
|---|---|---|
| Reasoning VLM | ~5–10 Hz | 语义规划、子任务跟踪、粗 reference action-force chunks |
| Force-Residual Head | ~20 Hz | 力历史 → Δa，细化到 0.5 mm |
| Safety Critic | — | \(Q(s,z,f,a)\) 门控，接触安全包络 |
| 执行 | ~200 Hz | 柔顺、接触感知执行 |

对比实验叙事：vision-only 在接触处 jam；force residual 可纠正并 seat——更低峰值接触力、更小插入误差、更快恢复。

### 3.3 三阶段训练与硬指标

| 阶段 | 内容 | 站页/摘要效果 |
|---|---|---|
| Pre-train | 遥操装配 + assembly-VQA（做什么 + 该什么手感） | 技能与任务先验 |
| Post-train | 真机 RL / reward-driven rollout | +45% success · −40% cycle · +60% recovery |
| Adapt | few-shot、安全有界；~6.6% 权重 | +30% adapted success |

**摘要硬结果**：五任务亚毫米 PC 装配 **mean success 82% vs 最强 baseline 15%**；0.5 mm 放置精度；50 ms 指令延迟。

### 3.4 对「力觉 VLA」文献位置的判断

论文自我定位：通用 VLA 接口偏低频位姿，欠表示力与状态历史；经典柔顺控制稳接触但手调、弱耦合多模态；既有 force-aware VLA 改善感知，却常把学习环**开环**——部署检出失败，却缺对后续纠正交互的 credit 机制。  
Facet-0 的增量：**闭环 credit + 联合生成 wrench profile + 相选择信用**。

---

## 4 · 精密对照：工业协议 vs 其他供给哲学

### 4.1 五条哲学中的 D

| 哲学 | 代表 | 与 ManuFacet |
|---|---|---|
| A 通用真机 | AgiBot / OpenX / π | **同属真机，regime 不同**：A 广任务；D 窄任务极高精度+力协议 |
| B 人/EGO | 光轮 / 它石 / EgoVerse | **正交**：EGO 无亚毫米 wrench 真值；规模与语义先验，不替代 D |
| C 仿真 | GR00T / Cosmos | **互补危险**：可造力，接触 sim2real 深坑；D 选真机力同步为主供给 |
| **D 精密工业力** | **ManuFacet** | 本专题主体 |
| E 配对金标准 | HRDexDB | E 定质量上限；D 给可 soft 的工业量级 |

### 4.2 协议层对照表（分析用）

| 协议项 | A 通用真机 | B EGO | C 仿真 | **D ManuFacet** |
|---|---|---|---|---|
| 成功判据 | 任务完成/泛化 | 多为语义/操作成功 | 仿真成功 | **公差 + 力包络 + 恢复** |
| 力/触 | 可选扩展 | 人触觉≠产线 F/T | 可仿真 | **每帧 sync F/T 强制** |
| 时序结构 | sub-step / 技能 | 原子动作/叙述 | 可任意 | **接触 7 相** |
| 失败样本 | 常过滤 | 少系统性保留 | 可合成 | **保留 + 飞轮** |
| 跨本体 | 多源拼盘或共训 | 需 retarget | 可随机化 | **少本体 + 同一 13-D schema** |
| 单位小时信息 | 中 | 低～中（缺 L4） | 高但不真 | **高（力+相+恢复）** |

### 4.3 与 REASSEMBLE / FMB 的谱系

二者已有 sync F/T 与阶段标签，但是 **~13h / ~31h** 量级。ManuFacet 的贡献不是「发明力」，而是把工业接触协议**拉到可训基础模型的小时数**，并配上 joint action–wrench 学习与真机 RL 闭环。  
→ 工业数据集路线的进步函数 ≈ **协议完备度 × 有效小时 × 闭环回流**，不是轨迹条数。

---

## 5 · 对「数据×训练」主线的精密含义

### 5.1 修正 1：真机必须再拆 A vs D

混称「真机数据」会掩盖：  
- A 解决覆盖与泛化；  
- D 解决接触体制下的稳、准、恢复。  
采购/精读/对标时先问四问：  
1. 有无 **sync F/T**？  
2. 有无 **接触相**（非仅技能动词）？  
3. **失败是否保留**？  
4. 成功是否含 **公差/力包络**？

### 5.2 修正 2：R4 ∩ R6 是精密域的主战场

- R4 真机在精密域不可被 R1/R3 廉价替代（缺 wrench 真值与真接触）。  
- R6 不能停在「多一个触觉通道」：要升级到 **力是监督对象 + credit 进训练环**（Facet-0），WIYH 的 VLTA 是标准入门，ManuFacet 是工业闭环标杆。

### 5.3 修正 3：R5 统一动作空间要能挂 wrench

相机中心/夹爪不变统一了「空气中的几何」；插入任务还需要 **接触条件下的可微接口**（wrench 历史、相索引、安全包络）。否则统一动作空间在 D 域会系统性欠定。

### 5.4 修正 4：用「有效小时」比较，不用原始小时

1h ManuFacet（力+相+恢复）≠ 1h 纯 RGB 遥操 ≠ 1h 被动 EGO。  
版图比较应报：**有效接触小时 / 相标注覆盖 / F/T 同步率 / 失败段占比**。

### 5.5 修正 5：开源争夺的第三条协议线

- A 线：跨机构通用格式（OpenX 系）  
- B 线：人/EGO 规模标品（光轮/它石）  
- C 线：仿真与世界模型基础设施（NVIDIA）  
- **D 线：工业力同步 schema + 接触相词汇 + 飞轮策展**（Data Foundry / ManuFacet 候选人）

谁定义 D 协议，谁更可能定义精密制造具身的数据接口。

---

## 6 · 局限与外推边界（精密，不灌鸡汤）

1. **任务族偏 3C/PC 装配**；汽车接触装配、航发 inspection 为 next up——跨行业接触几何是否共用 7 相，未证。  
2. **腕部 F/T ≠ 分布式触觉皮肤**；与 GelSight / 皮肤式触觉是不同空间粒度，合流仍是开放问题。  
3. **3 本体同 schema** 的跨本体结论不能直接外推到双手/人形全身。  
4. **82% vs 15%** 是摘要主结果，基线集合与任务定义以全文实验节为准（本专题以摘要+协议层为主，实验表细项可续补）。  
5. **arxiv 标准 id 待补**；引用目前用项目 PDF + HF。

---

## 7 · 精读清单（调研向，供后续单篇）

| 优先级 | 对象 | 看什么 |
|---|---|---|
| P0 | ManuFacet PDF 全文实验/附录 B | QC 阈值、相标注一致性、消融（无 F/T / 无相 / 无 RL） |
| P1 | REASSEMBLE · FMB | 早期力同步谱系，规模与标签粒度对照 |
| P1 | 力觉 VLA 相关（论文 related） | 开环力感知 vs 闭环 credit 的分界 |
| P2 | 它石 WIYH × ManuFacet | VLTA 人中心 vs 产线 F/T 协议对照 |
| P2 | AgiBot World 视触觉扩展 | A 向 D 靠拢的可能路径 |

---

## 8 · 口径（可引用）

**工业数据集专题口径**：  
精密接触制造的具身瓶颈不是再来一个通用 VLA，而是工业数据协议——**力同步 × 接触相标注 × 失败保留 × 公差化成功判据**。ManuFacet-1K 把该协议做到 ~1000h 可训规模；Facet-0 用 action–wrench 联合生成与真机 RL 信用分配把亚毫米装配从约 15% 拉到约 82%。对数据×训练：真机须拆 A/D；R4∩R6 是精密主场；R5 统一动作空间必须能挂 wrench；比较数据请用有效接触小时，而非原始小时。

---

## 9 · 关联文档

| 文档 | 关系 |
|---|---|
| 主文档「数据论文分析」 | 父节点；本篇为子文档 |
| `工业数据集洞察-Facet0-ManuFacet1K-2026-08-28.md` | 首轮洞察卡（较短） |
| `企业工业数据集版图-含ManuFacet-五条供给哲学-2026-08-28.md` | 版图与五哲学 |
| `数据集路线研究-主线图谱与研究计划-2026-08-28.md` | R1–R6；R4/R6 已挂 ManuFacet |
| EGO 数据集 8 集对照 | B 线；与 D 正交，勿混比 L4 |
