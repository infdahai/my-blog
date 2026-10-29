---
title: 专题 · AgiBot World Colosseo 全文精读（post-OXE 真机开源）
description: 智元 AgiBot World：百万轨迹同构真机、HITL 质量、ViLLA/GO-1 潜动作；相对 OpenX +30% 的机制拆解
tags: [专题, AgiBot, 真机数据, GO-1, latent-action, OXE]
created: 2026-08-28
feishu_wiki: https://huazhi-ai.feishu.cn/wiki/E6SZwRaDriH7AKk7TLycQLQGn7e
feishu_docx: LOyXdqa11o5X2vxTQxTckmY6nyc
arxiv: 2503.06669
---

# 专题 · AgiBot World Colosseo 全文精读

> **性质**：调研洞察 · 全文精读（不实跑）  
> **飞书**：主文档下**子文档**  
> **论文**：✔ arXiv **2503.06669** · *AgiBot World Colosseo*  
> **项目**：https://agibot-world.com · Code: OpenDriveLab/AgiBot-World  
> **定位**：OXE 之后，**同构平台 + 质量协议 + 潜动作通用策略** 推进开放真机操作数据的代表作。

---

## 0 · 一句话

**AgiBot World = >100 台同构双臂/人形在 4000㎡ 级设施采的「高质量百万轨迹真机操作系统」+ GO-1（ViLLA：潜动作桥接网页/跨本体/真机）。**  
相对 Open X-Embodiment 预训练 **域内/域外平均约 +0.30 completion（+30% 叙事）**；强调 **HITL 质量 > 盲目堆量**；轨迹规模 **power-law，r=0.97**。

---

## 1 · 问题与贡献

可泛化操作需要可扩展真机数据；OXE 等在规模数量级、真实场景、长程、质量门、末端可扩展（夹爪→灵巧/视触觉）上仍不足。

**贡献**：
1. **数据/平台**：标准化硬件 + HITL；**1,001,552 轨迹 · 2976.4 h · 217 任务 · 87 skills · 106 scenes**。  
2. 相对既有集约 **一个数量级** 规模跃迁（文述）。  
3. **GO-1**：Vision-Language-**Latent**-Action（ViLLA）。  
4. 开源（CC BY-NC-SA 4.0）+ 工具 + 模型；复杂任务 **>60%**；相对 RDT **+32%**。

---

## 2 · 平台与数据（§III）

### 2.1 硬件：同构是质量下限（§III-A）
- **AgiBot G1** 系：双 7-DoF 臂、移动底盘、可调腰。  
- 末端模块化：夹爪 / **6-DoF 灵巧手**；接触可用 **视触觉夹爪**。  
- **8 相机** + 本体；**30 Hz**。  
- 遥操：**VR**（EE+IK，灵巧手预设手势）+ **全身动捕**（含手指，复杂灵巧）。

**Insight**：相对 OXE 多机构异构拼盘，AgiBot 赌 **同构舰队** → 少付 embodiment 税。哲学 A 内部分岔：**联盟异构 vs 舰队同构**。

### 2.2 采集：Human-in-the-loop（§III-B）
1. 预采定标准 → 2. 正式采 + 本地有效性 → 3. 云端审 + 语言标注。  

**Failure recovery**：失误后恢复完成的轨迹 **保留**，标失败原因/时间戳；约 **~1%**。与 ManuFacet「失败保留」同方向，深度不及力相协议。

### 2.3 统计（§III-C）
| 项 | 数值 |
|---|---|
| 轨迹 / 小时 | **1,001,552 / 2976.4 h** |
| 任务·技能·场景 | 217 · 87 · 106 |
| 机器人 | **>100 同构** |
| 设施·物体 | >4000 m² · >3000 物体 |
| 五域 | domestic / retail / industrial / restaurant / office |

**vs OXE/DROID**：多数轨迹 **30–60 s**（OXE v1 大量 <5 s；DROID 多 5–20 s）；每 skill ≥100 轨迹。  
**alpha ≈ 全量 14%**；文称 alpha ~**236 h** 即可在部分设定上优于更长小时 OXE 混合（质量叙事）。

---

## 3 · GO-1 · ViLLA（§IV）

相对 VLA，ViLLA：**先 latent action，再底层控制**。

| 阶段 | 内容 |
|---|---|
| **1 LAM** | 相邻帧逆动力学；网页人视频+跨本体；时空 Transformer + **VQ-VAE**（k=4） |
| **2 Latent Planner** | **InternVL2.5-2B**；多视(头/左腕/右腕)+语言→latent；embodiment-agnostic 长程规划 |
| **3 Action Expert** | 与 planner 联合，落地灵巧底层动作 |

**Insight**：潜动作 = 把无标签人视频/跨本体变成 **表示层伪标签**（连自动标注专题）；与 EgoScale「显式人动作空间」、OXE「粗 7D EE」形成第三路径。

---

## 4 · 实验（§V）

- 任务：Restock、Table Bussing、Pour Water、Fold Shorts、Wipe Table 等 + OOD 变体。  
- **RDT + 不同预训练**：AgiBot 相对 OXE 平均 **+0.30 / +0.29**（域内/域外）；Table Bussing 近 **3×**。  
- **GO-1 > RDT**；latent planner 再 **+0.12**；复杂任务 >60%、vs RDT +32%（摘要）。  
- **缩放**：9.2k→1M 轨迹，completion **power-law，r=0.97**。  
- **质量消融（锋利）**：Wipe Table 上 **验证 528** vs **未验证 482** → 更少验证数据 **+0.18 completion**；量大不等于更好。

---

## 5 · 主线 Insight

1. **post-OXE**：不是再拼 20 个机构，而是 **同构 + 协议 + 长程**。OXE=共训存在性；AgiBot=什么样的真机小时更值钱。  
2. **+30%** 首先是数据性质，其次才是 GO-1。  
3. **双缩放**：EgoScale（人动作小时–loss）∥ AgiBot（真机轨迹–completion）。  
4. 失败恢复已入集但 **~1%**、无力同步 → 仍哲学 **A** 非 **D**。  
5. CC BY-NC-SA：研究友好、商用受限。

## 6 · 口径

**AgiBot World（2503.06669）以 >100 台同构双臂在真实五域采约 100 万轨迹（2976 h、217 任务），HITL + 失败恢复（~1%）换质量；GO-1 以潜动作桥接网页与真机，预训练相对 OpenX 约 +30% completion，轨迹 power-law（r=0.97），验证数据优于更大量未验证数据。post-OXE「同构高质量真机操作系统」代表，哲学 A 质量峰，非精密力协议 D。**

## 7 · 关联
OXE 全文精读 · 企业版图 A · EgoScale · 自动标注/latent · ManuFacet 质量对照
