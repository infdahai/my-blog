---
title: 专题 · EgoWAM 全文精读（Danfei EGO 线）
description: 世界动作模型：固定骨干只换世界预测目标 Pixel/DINO/3D Flow；人机共训转移接口
tags: [专题, EgoWAM, DanfeiXu, ego, WAM, 精读]
created: 2026-08-28
feishu_wiki: https://huazhi-ai.feishu.cn/wiki/HBktw1ZFyin5IAkZ65ecGfbMnsd
feishu_docx: KHhhdWdjKoeskVx5SKFcdjxcn5z
arxiv: 2607.08436
---

# 专题 · EgoWAM 全文精读（Danfei EGO 线）

> **系列**：Danfei Xu EGO 线全文精读 · **世界/表示层** 定海篇  
> **论文**：✔ **2607.08436** · *EgoWAM: World Action Models Beyond Pixels with In-the-Wild Egocentric Human Data*  
> **作者**：Baoyu Li\*, Xinchen Yin\*, …, **Danfei Xu**（Georgia Tech）  
> **项目**：gatech-rl2.github.io/egowam.github.io  
> **飞书**：主文档下子文档

---

## 0 · 一句话

**EgoWAM 问：人→机迁移时，世界预测目标该是什么？**  
在 **固定** 策略骨干、动作头、数据混合的前提下，只换世界头： **Pixel VAE / DINO / 3D motion flow**。  
结论：**BC 共训常被不可执行人动作拖垮；WAM 共训把人数据变成可靠增益。** Pixel 弱；**DINO 最强 OOD（至约 4×）**；**3D Flow 最强 ID 空间（约 +20–30%）**。推理时丢掉世界头，成本≈ BC。

**在 EGO 线中的位置**：蓝本 **L5 世界/物理** 的可控实验；相对 MimicPlay（plan）、EgoScale（人动作缩放）、EgoEngine（翻译），EgoWAM 专攻 **「转移该走动力学通道还是动作通道」**。

---

## 1 · 问题

Ego 人数据可扩展，但 **BC 把可迁移内容（物/景/任务语义）与不可迁移因素（形态、头动、行为风格）缠在动作头里** → 共训出 **不可执行的人样动作**，伤害真机。  

**World Action Model (WAM)**：既预测动作，也预测场景如何演化 → 动力学通道可传任务相关结构。  
核心问题：**哪种世界表示** 最利人→机？

### 三 desiderata（Fig.1）
1. **D1 外观抽象**（不绑纹理/身份）  
2. **D2 跨本体一致**（agent-invariant 物理效应）  
3. **D3 分离相机运动与环境变化**（ego-motion factoring）

---

## 2 · 方法

### 2.1 动作通道先对齐到「强 BC 基线」（§3.1）
- 人：Aria ego；机：双臂 + 腕视 + **同一 Aria ego**。  
- 动作统一 **14-D EE**：每臂 6D SE(3)+gripper；机 FK 到 **静态 ego 相机系**；人腕在 **device 系** 用 \(T_t^{-1}\) 消头动。  
- 速度：人窗 **1 s**、机 **1.5 s**，同 progress 重采样为 k 步。  
- 分位 normalize。  
- 共享 encoder + **flow matching** 动作头；人+机 BC 共训 = 最强动作对齐基线。

### 2.2 WAM：第二监督通道（§3.2–4.2）
共享 trunk \(z=f_\phi(o)\) → 动作头 ∥ **可替换世界头** \(g_\psi(s|z)\)。

| 世界目标 | 含义 | 对 D1–D3 |
|---|---|---|
| **Pixel VAE** | 重建未来像素/潜变量 | 外观纠缠，转移弱 |
| **DINO / RAE** | 预测语义特征 | 强外观抽象；ego-motion 仅部分缓解 |
| **3D Flow** | Aria VIO 稳相机后的 **3D 点位移场** | 静物≈0 流、操作物保留物理位移；**三者最贴 D1–D3** |

训练：  
\(L = L^{robot}_{action}+L^{human}_{action}+\lambda(L^{robot}_{world}+L^{human}_{world})\)，\(\lambda=1\)。  

**推理：丢掉世界头**，只 unroll 动作头（~30 Hz）——训练塑形表示，不增加测试想象成本。

---

## 3 · 实验（§5）

- 双臂 ARX5 + Aria + 腕 D405。  
- 三任务（EgoVerse flagship）：**cup-on-saucer**（精密刚体）、**fold-clothes**（可变形三折）、**bag-grocery**（开袋装 3 物）。  
- 机 demo：300–360/任务；人数据：  
  - In-domain human 1:1（同场景物、视点行为不对齐）  
  - **EgoVerse ~10:1** 野外规模。  
- ID/OOD 各 20 rollouts；全文 **~1800** 真机 rollout。

### 主发现
**Q1 WAM vs BC**  
- 人机动作不对齐时，BC 复现人样不可执行动作而掉点；WAM 把同数据变增益。  
- 大量 EgoVerse 时 BC 仍易过拟合机数据、不泛化；WAM（尤其 DINO）吃野外人数据。  
- UMAP：BC 人机 embedding 分离；WAM **拉齐共享 latent**。

**Q2 世界表示**  
- **Pixel**：弱；幻觉抓空、折衣不完。  
- **DINO**：OOD 物/景最强（摘要 **至约 4×**）。  
- **3D Flow**：ID 空间精度最强（**+20–30%** 量级；杯放置跨工作空间）。

**Q3 不对齐人数据**  
- 故意采「怪抓法」不可映射机动作：BC **掉到 robot-only 以下**；3D Flow WAM **仍稳且超 robot-only**。  
- 仅 bag-grocery 等动作天然对齐任务上，BC 共训才有正收益。

---

## 4 · Insight（EGO 线 / 蓝本）

1. **人数据默认不该只走动作 BC** —— MimicPlay 用 plan，EgoWAM 用 world；EgoScale 的「动作标注人」是第三路，且仍要 mid 锚定。  
2. **转移接口从 action 升到 world representation** 后，可在 **不改推理成本** 下吃 in-the-wild ego。  
3. **表示选择有分工**：要 OOD 语义 → DINO；要 ID 几何接触精度 → 3D Flow；Pixel 作对照基线。  
4. **与 ManuFacet**：3D Flow 是视觉几何动力学，**仍无力/接触 wrench**；L5 合流未完成。  
5. **与 A4/统一动作空间**：动作已 14-D 相机中心对齐，但仍不够；世界头补的是 **动力学不变性**。  
6. 实验控制干净（只换世界目标）→ 蓝本「世界表示选型」可直接引用本篇表格。

## 5 · 口径

**EgoWAM（2607.08436）在固定骨干/动作头/数据混合下比较 WAM 世界目标：Pixel 弱转移；DINO 主 OOD（至约 4×）；相机稳定 3D Flow 主 ID 空间（约 +20–30%）。BC 共训常因不可执行人动作受损，WAM 经动力学通道吃 EgoVerse 级野外人数据，推理丢世界头保持 BC 延迟——EGO 线 L5「世界表示作迁移接口」的可控证据。**

## 6 · 关联
MimicPlay（层级 plan）· EgoScale（人动作缩放）· EgoBridge（潜空间对齐）· 蓝本 L5 · ManuFacet（力世界对照）
