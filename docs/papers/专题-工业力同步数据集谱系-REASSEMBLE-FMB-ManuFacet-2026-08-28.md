---
title: 专题 · 工业力同步数据集谱系（REASSEMBLE · FMB · ManuFacet）
description: 接触富集工业数据从基准板到产线级力协议的谱系精密分析
tags: [专题, industrial-dataset, force, REASSEMBLE, FMB, ManuFacet]
created: 2026-08-28
feishu_parent: VTB4wrwB2im3IvkS1SUcCQLHnKb
feishu_wiki: https://huazhi-ai.feishu.cn/wiki/Lf8LwIoJmiK9cckdePmcrchvnEJ
feishu_docx: OJWYdXxKNoMVaOxPBGYc7JbInHd
feishu_node: Lf8LwIoJmiK9cckdePmcrchvnEJ
---

# 专题 · 工业力同步数据集谱系（REASSEMBLE · FMB · ManuFacet）

> **文档性质**：工业数据集专题第 2 篇（谱系深析 / insight）。  
> **飞书**：主文档「数据论文分析」下**子文档**（不堆主文）。  
> **核验**：REASSEMBLE ✔arxiv **2502.05086**；FMB ✔arxiv **2401.08553**；ManuFacet ✔项目 PDF/HF（前篇专论）。

---

## 0 · 本篇要回答什么

前篇（ManuFacet 精密分析）立住了哲学 **D：精密力同步工业数据**。本篇回答：

1. D 不是从 1000h 突然冒出来的——**谱系上游**是谁？各解决了什么、还缺什么？  
2. FMB / REASSEMBLE / ManuFacet 在**协议完备度 × 有效规模 × 闭环回流**上如何递进？  
3. 读工业/接触数据集时，固定用哪张**谱系尺子**打分？

**预告口径**：工业力同步线走的是  
**可复现装配基准（FMB）→ 多模态接触+失败显式（REASSEMBLE）→ 产线级力协议+基础模型闭环（ManuFacet）**；进步函数是协议×有效小时×飞轮，不是轨迹条数。

---

## 1 · 三节点速写（已核验）

### 1.1 FMB — Functional Manipulation Benchmark  
- **id**：✔ **2401.08553**（Berkeley：Luo / Levine 等）  
- **定位**：**可复现的功能操作基准 + 工具包**，不是「最大工业数据集」。  
- **设计原则**：复杂度与可进入性平衡——任务够窄以便小模型可追踪进度，又够多样以考泛化；**3D 打印 procedural 物体**便于外实验室复现。  
- **技能**：抓取、重定位、一类装配行为；可评单技能，也可评多阶段组合排序。  
- **数据**：约 **22,500** 条人类演示；多相机 RGB-D、运动学、**末端 F/T**（Franka 自带，未额外外挂 F/T 传感器——论文明确写出）。  
- **规模口径**：ManuFacet Table 1 记 **≈31 h**（本篇采用该对照小时；FMB 原文以演示条数为主叙事）。  
- **开源**：数据集、CAD、代码、基线策略；站点 functional-manipulation-benchmark.github.io  
- **对 D 线贡献**：把「装配/插入」做成**可复现科研对象** + 明确带 **EE 力/力矩**；模块化 pipeline 让后人可只改一环。  
- **相对 ManuFacet 的缺口**：实验室 3D 打印件 ≠ 产线公差零件；小时数小；无接触相工业 taxonomy；无力同步「协议级」多中心 schema；失败飞轮与真机 RL 基础模型不是主叙事。

### 1.2 REASSEMBLE — Multimodal Contact-rich Assembly/Disassembly  
- **id**：✔ **2502.05086**（TU Wien / DLR：Sliwowski 等）  
- **定位**：**接触富集装配/拆卸多模态数据集**，锚定 **NIST Assembly Task Board #1**（跨机构可部署基准板）。  
- **动作**：pick / insert / remove / place；**17 物体**。  
- **规模**：演示 **4,551**（成功 4,035 / 失败 **516**）；总时长 **781 min ≈ 13.0 h**（与 ManuFacet 表 ≈13 h 一致）。  
- **层级标注**：4,551 高层演示 + **10,195** 低层 skill；显式服务三类任务——  
  - Hierarchical Temporal Action Segmentation  
  - Motion Policy Learning  
  - **Success / Anomaly Detection**  
- **模态（相对通用集的增量）**：  
  - 常规：外视 + 腕视 RGB、本体感觉  
  - **增量**：**Event camera**、**Force & Torque**、**Microphone×3**  
- **相/技能结构示例**（文内）：Insert 可拆为 Approach / Align / Release 等低层 —— 已具「接触过程可分段」思想，但词汇服务于 NIST 板与分割基准，尚未升到产线 7 相工业协议。  
- **对 D 线贡献**：  
  1. **失败样本显式入集**（516 failed）并服务 anomaly detection；  
  2. 力 + 事件相机 + 音频的**多物理通道**；  
  3. 高/低层时间标注，接近工业 L3 雏形；  
  4. NIST 板降低跨实验室部署摩擦。  
- **缺口**：~13 h 仍是**基准板小时数**；无 1000h 级产线网络；无 joint action–wrench 基础模型与部署 RL 飞轮；拆装物体集固定在 NIST 板生态。

### 1.3 ManuFacet-1K / Facet-0（前篇结论压缩）  
- **~1000 h** 力同步；3 本体**同一 13-D schema**（位姿+开合+wrench）；**7 接触相**；失败纠正轨迹保留；PC 产线公差任务。  
- Facet-0：action–wrench 联合生成 + Critic credit + 真机 RL → **82% vs baseline ~15%**。  
- **相对上游**：把 FMB 的「可研究装配」与 REASSEMBLE 的「多模态接触+失败」**拉到可训基础模型的小时数与工业协议完备度**。

---

## 2 · 谱系递进表（协议 × 规模 × 闭环）

| 维度 | FMB (2401.08553) | REASSEMBLE (2502.05086) | ManuFacet-1K |
|---|---|---|---|
| 时代角色 | 可复现装配**基准/工具包** | 接触**多模态+失败显式** | **产线级力协议 + FM** |
| 有效规模 | ~22.5k demos / ≈31 h | 4.5k demos / **≈13 h** | **≈1000 h** |
| F/T | EE F/T（臂原生） | 外置/专用 F&T + 多模态 | **每帧 sync wrench 入 13-D 状态** |
| 时序结构 | 技能阶段（抓/转/装） | 高/低层动作 + insert 子步 | **工业 7 相 taxonomy** |
| 失败 | 非主资产 | **516 failed 入集 + anomaly 任务** | **纠正轨迹保留 + RL 飞轮** |
| 任务域 | 3D 打印 procedural 件 | NIST Task Board #1 | **真实 PC 机箱产线族** |
| 跨本体 | 单平台工具包叙事 | 单生态基准板 | **3 本体同 schema** |
| 模型闭环 | IL 基线技能可组合 | 分割/策略/异常三任务 | **VLM+力残差+Critic+真机 RL** |
| 开源友好 | CAD+数据+策略 ★★★ | 多模态基准 ★★★ | HF 数据/模型 + PDF ★★★ |
| 哲学位置 | D 的**科研入口** | D 的**模态与失败协议雏形** | D 的**工业协议标杆** |

**读表结论**：
- 规模上 REASSEMBLE 甚至小于 FMB 小时数，但**协议信息密度**（失败、事件、音频、层次标注）更高——再次验证「有效小时 > 原始小时」。  
- ManuFacet 的跃迁是 **×30–80 的小时数 × 协议升级（相+同 schema+飞轮）× 学习闭环**，不是单点刷榜。

---

## 3 · 三条机制洞察（谱系级）

### I1 · 工业接触数据的进化顺序是「可复现 → 可诊断 → 可规模闭环」
1. **FMB**：先让社区**做得了、复得现、拆得开 pipeline**（否则精密接触无人跟）。  
2. **REASSEMBLE**：让接触过程**可分割、可听、可测力、可标失败**（否则只有成功轨迹的模仿会脆）。  
3. **ManuFacet**：在可诊断协议上**加小时数与产线约束**，并接上 foundation model + 部署 RL。  

→ 启示：只抄 ManuFacet 的「1000h」而不抄前两级的**可复现与失败/相标注**，工业数据项目容易变成「贵而不可复现的私有遥操堆」。

### I2 · 失败样本从「瑕疵」变成「一等监督」是谱系分水岭
- FMB：工具包叙事，失败非核心资产。  
- REASSEMBLE：失败入集 + Success/Anomaly 独立任务。  
- ManuFacet：失败/纠正进飞轮，recovery 指标进 post-train（+60%）。  

→ 任何自称 D 线的数据集，若 QA 只保留成功段，在谱系上**停在 FMB 之前**，即使小时数更大。

### I3 · 力通道的「有」与「协议化」是两回事
| 层级 | 含义 | 代表 |
|---|---|---|
| 有 F/T 读数 | 传感器在 | FMB（臂原生 EE F/T） |
| 力+多物理对齐 | 事件/声/力服务接触诊断 | REASSEMBLE |
| **力进状态 schema + 生成目标 + credit** | wrench 是监督对象 | ManuFacet / Facet-0 |

→ 精读 force-aware 论文时固定追问：力是**日志**、**输入拼接**，还是 **joint 生成目标 + 价值信用**？

---

## 4 · 谱系尺子（以后打工业数据集的固定表）

给新公开的「工业/装配/接触」数据集打分（0/1/2）：

| 项 | 0 | 1 | 2 |
|---|---|---|---|
| F/T | 无 | 有记录 | **帧级同步进状态/学习目标** |
| 接触时序 | 无 | 技能/粗阶段 | **接触相/可对齐 L3** |
| 失败 | 过滤 | 部分保留 | **显式 anomaly + 飞轮回流** |
| 公差/成功 | 二元成功 | 任务定义含配合 | **产线公差/力包络** |
| 可复现 | 私有产线 | 有基准板/CAD | **公开 CAD+协议+基线** |
| 规模 | &lt;20h | 20–200h | **≥500h 有效接触** |
| 闭环 | 仅 IL | 有评测套件 | **部署 RL / 纠正回流** |
| 跨本体 | 单机 | 多机未统一 | **同 schema 多本体** |

- **FMB** 大致：可复现 2 · F/T 1 · 失败 0–1 · 规模 1 · 闭环 1  
- **REASSEMBLE**：F/T 1–2 · 失败 2 · 时序 1–2 · 规模 0–1 · 闭环 1  
- **ManuFacet**：多数项 2，任务族仍偏 3C（跨行业 1）

总分不重要，**短板项**决定它在谱系上停在哪一站。

---

## 5 · 与五条供给哲学 / R 路线的挂接

- 三者均属 **哲学 D 谱系**（不是 A 的「再来一个通用真机集」）。  
- **R4∩R6** 的文献阅读顺序建议：FMB（入门可复现）→ REASSEMBLE（失败与多模态）→ ManuFacet（协议+FM）。  
- **R5**：仅 FMB/REASSEMBLE 级统一「技能接口」不够；要到 ManuFacet 级才强迫 **wrench 进统一接口**。  
- **勿与 B 线混比 L4**：NIST 板/3D 打印插入的「成功」≠ EGO retarget 后的可执行；谱系内比协议，跨哲学比角色。

---

## 6 · 局限（本篇边界）

- FMB 的 ≈31 h 来自 ManuFacet 对照表，非 FMB 摘要主叙事；引用小时需注明来源。  
- 未展开两者全文所有消融数字；机制与协议层已核验，实验表可作 P1 续补。  
- 未纳入所有 force-aware VLA 模型论文（属「模型谱系」，可另开专题）。  

---

## 7 · 一句话口径

**工业力同步数据谱系 = FMB（可复现装配基准）→ REASSEMBLE（多模态接触 + 失败显式）→ ManuFacet（产线力协议 + 基础模型闭环）。**  
进步看 **协议完备度 × 有效接触小时 × 失败/部署飞轮**；有 F/T ≠ 力已协议化；自称工业集却过滤失败，在谱系上仍停在早期站。

---

## 8 · 关联

| 文档 | 关系 |
|---|---|
| 专题 · 工业数据集精密分析（ManuFacet） | 第 1 篇；本篇为谱系上游 |
| 企业/工业数据集版图（五条哲学） | D 的版图位 |
| 数据集路线 R4/R6 | 阅读与对标顺序 |

## 9 · 建议下一专题（仍子文档）
- **力觉 VLA / force-aware 策略谱系**（开环力输入 vs 闭环 credit）  
- 或 **WIYH（VLTA）× ManuFacet（产线 F/T）** 人中心 vs 产线协议对照  
