---
title: 专题 · CHORD 全文精读（Danfei EGO 接触力支线）
description: 接触wrench空间引导RL；4,739仿真任务；灵巧手接触丰富操纵；SOTA 82%
tags: [专题, CHORD, DanfeiXu, ego, contact, wrench, 灵巧手, 精读]
created: 2026-08-28
feishu_wiki: 
feishu_docx: 
arxiv: 2607.00033
---

# 专题 · CHORD 全文精读（Danfei EGO 接触力支线）

> **论文**：✔ arXiv **2607.00033** · *Learning Dexterous Manipulation Using Contact Wrench Guidance From Human Demonstration*  
> **作者网**：**NVIDIA**（Zhu、Fan† 等，**Danfei Xu**, Yuke Zhu, Soha Pouya, Yan Chang Lead）  
> **站点**：nvidia-isaac.github.io/video_to_data/chord/  
> **飞书**：主文档下子文档

---

## 0 · 一句话

**CHORD = 用「物体为中心接触 wrench 空间引导」做灵巧手接触丰富操纵的 RL 框架**：把人与机器人运动都表征为**它们能在物体上引起的力/力矩**，用「诱发瞬时运动」度量相似性 → 让 RL 在接触丰富、长程、硬/关节/多物体任务上可规模。  
配套 **4,739 个双臂灵巧任务**仿真基准（源自动捕 + 自采重建视频），在 **1,831** 个任务上平均 **82.12%** 成功率；泛化到全身操纵（**90.77%**），并真机 open/closed-loop 部署。

**在 EGO 线中**：这是 **R6 / 接触精密支线** 的「力级（wrench）」供给哲学对照 —— 相对 ManuFacet（精密力同步工业数据）、MimicTouch（人手指+触觉），CHORD 给 **「仿真 + 力/接触变异型引导」可规模路径**：人提供参考，力语义在仿真 RL 里落地。

---

## 1 · 问题
- 灵巧手靠近人手形态，但转人演示到机器人策略难（接触丰富、长程、多物体、可变形/关节）。  
- 现有 **location-based 接触奖励不足**：位置近了但**法向/物理作用不对**（盒盖例：位置匹配但接触法向近乎垂直演示）→ 光匹配接触位置没用。  
- 需要一种**跨本体一致的接触表示**：物体所能承受的力/力矩（诱发运动）→ wrench。

---

## 2 · 方法

**设定**：物体有 K 刚体（K 个独立物 或 关节物体 K 个部分）。参考轨迹 τ = {人手 keypoints, 物体(各部件) SE(3) 位姿}。  
流程：人手 keypoints **IK 重定向**到手配置 → 策略 π(a|o_robot, o_object; x_robot, x_object) 预测动作。

### 2.1 接触 wrench 空间奖励（§3.1, Eq.1–3）— 核心
- 从人演示的**物体坐标系**里抽手接触点 {p} 与法向 {n}。  
- 用库仑摩擦锥的多面体近似，把每个接触的可行接触力离散成 `d` 条单位 edge force → 每条诱导**primitive wrench** w = [f; p×f] ∈ R⁶ → 组 **wrench matrix** 𝒲 ∈ R^(6×cd)，表示「人手接触能给该物体施加的力-力矩方向 = 运动诱发能力」。  
- 不同 𝒲 列数/顺序不同 → 用 **support function** σ = max_col(ℬᵀ𝒲) ∈ R^b（预采样 b 个单位方向 ℬ）统一比较人机。  
- **奖励**：比较机器人 support σ_r 与人类 σ_h，带上下 tolerance β；再惩罚 **unintended contacts**（人没有机有）与 **missed contacts**（人有机没有）。  
- **不做**重建完整多接触可行 net-wrench polytope；只比「方向性能力」当引导，**可执行性交给仿真器**。  
- 关键：contact wrench 奖励要先收敛再衰减 VOC（training 稳定必要条件）。

### 2.2 高效鲁棒训练（§3.2）
- **沿参考轨迹任意状态重置** + 短稳定窗口（VOC 全开），让机器人先恢复接触再 anneal。  
- **用人类接触 wrench 矩阵采样力扰动**物体（任务相关扰动）。  
- 残差动作空间（用重定向机运动当 prior）。  
- **噪声 contact 场景（RGB 视频重建）**→ 退化为 **reduced contact wrench guidance / force-closure 目标** r_fc = (1/B)Σ1[σ_r,k,b > ε]（鼓励各基向正 support = 力闭）。  
- **全身扩展**：hand-only 参考 → 用 inpainting 模块补全身运动；whole-body（第三者视角重建）→ 指重建不准 → 用 force-closure 目标。

### 2.3 基准（§3.3）
- 汇整公开人操纵数据集 [13–16, 39–41] + 室内视频重建 → 导入 Isaac Lab → **4,739 任务**。  
- 覆盖双臂 × 单/多刚体 × 关节物体；与 prior 比**任务更多、horizon 更长、接触事件更密**（Fig.3，Ferrari-Canny epsilon 度量抓取稳定）。

---

## 3 · 实验（§4）

### 3.1 规模化评估（§4.1）
- **1,831 任务统一超参**；文称首个此量级的 RL-based 灵巧操纵。  
- 成功=完成率>0.7（完成率=成功 rollout/总 rollout；以位置误差>15cm 或旋转>40° 判终止）。  
- **平均成功率 82.12%**；经得起 IK 噪声与手物穿透（wrench 引导避开错位接触效应）。
- 与 prior 主指标（AUC/SP-SR/MP-SR/JPE/RPE/MPPE）：**CHORD 全面优于 DexMachina (DM)、ManipTrans (MT)、SP** 等。

### 3.2 接触奖励消融（§4.2）
三种：CHORD（wrench support）/ Position Only（接触位置，如 DexMachina）/ No Contact。  
**表演随接触引导增强而提升**：CHORD 最高；Position Only 明显掉点（只匹配接触位置不足以复制接触丰富行为）；No Contact 最弱（纯运动学目标不够）。  
接触位置匹配法向错 → wrench 空间把「物理作用对不对」纳入。

### 3.3 全身泛化（§4.5, Table 3）
- hand-only 参考（12 任务：rigid/articulated/multi-object 各 4）→ G1 humanoid + Dex3 三指手。  
  **CHORD 0.925 ± 0.104 vs Position Only 0.217 ± 0.333**（刚性 0.994 / 关节 0.914 / 多物 0.866 vs 位置法 0.460/0.000/0.192）。  
  → wrench 表示在**跨手形态（五指人手→三指手）**仍扛得住。  
- 第三者视角（TPV）任务用 force-closure 目标，全部一致成功。

### 3.4 真机（§4.6）
Dexmate + 两只 **Sharpa 灵巧手**，动捕跟踪。  
- 碗交接 5/5、盘中平板重定向 3/5、碗-盘叠放 5/5、搅拌机开合 5/5、胶囊机交替取放 5/5。  
- open-loop 盒取放 6/7 vs closed-loop 7/7。  
- 失败源于 sim-to-real 发散（初始物体摆放、open-loop 接触过渡）；状态反馈策略跟踪固定参考、无反应性重规划。

### 3.5 遥操对照（§4.7）— 反直觉发现
- 小样本遥操 pilot：**box-lifting 意外最难**（需抓握成形+接触时点+施力协调）。  
- 三大困难源：① IK 不保手指构型（大张开幅/近极限）② 无触觉反馈、只能靠视觉（被遮挡不足）③ 不能直接控关节力矩施力。  
- 操作者靠练习能出「近似正确」轨迹，但**底层接触交互仍错/脆弱**。

---

## 4 · Insight

1. **接触位置匹配 ≠ 接触正确**：CHORD 核心是把「接触**位置**」升级为「接触**能诱发什么运动**」（wrench/support）。这是 R6 供给哲学的又一精确表达：**力语义 > 位形语义**。  
2. **仿真 + 力引导让接触数据可规模**：对比 MimicTouch（真机+在线奖励）、ManuFacet（精密力同步采集），CHORD 是 **仿真 RL 侧贴合人演示** 的第三条路 —— 人只出参考，力在 sim 里做引导与本体迁移。  
3. **跨形态迁移靠「物体侧」表示**：五指人手→三指手仍 0.925，因比较的是**物体受力能力**而非手指位形 —— 正是「物体为中心 invariant 表示」的证据（≈ EgoWAM D2 agent-invariant）。  
4. **遥操接触精操的挫败** = 反过来印证「触觉/力反馈 + 关节力控」是人机接触操控、也是遥操数据采集的瓶颈。  
5. **失败条件要报**：真机 5 任务非全 5/5（3/5、6/7）→ 交叉评估必须给失败来源（这里=sim-to-real 摆放/接触过渡）。  
6. **与 OxE/R4**：CHORD 无需大规模真机 demo，人视频→sim RL，即 **「人数据 × 仿真力引导」来绕过真机遥操** —— 若推广成立，将松动「接触类必须靠精密真机同步」的结论。

## 5 · 局限（§6）
- 真机部署**依赖 state-based 观测**（未做视觉闭环）。  
- 需要相对干净的人演示；噪声接触会降奖励质量（需 force-closure 假设兜底）。  
- 物体位姿误差是不完美指标（有的任务不要求精确摆放，有的小误差即功能失败）。  
- （分析补）仿真规模、评测以成功/完成率为主，非力协议数据质量指标。

## 6 · 口径
**CHORD（2607.00033，NVIDIA）以物体为中心 contact wrench 空间做引导：把人机动作都刻画为「可诱导物体的力/力矩 = 诱发运动能力」，用 support function 统一比较、加未触及/多余接触惩罚；4,739 任务仿真基准上统一超参评估 1,831 任务、平均 82.12%，跨五指→三指手形态仍 0.925，真机 open/closed-loop 可部署，并与遥操对照揭示接触精操的力/触觉瓶颈。它是 EGO 接触力支线里『人演示 × 仿真力引导可规模』的代表证据。**
