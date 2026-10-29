---
title: 专题 · DreamZero(2602.15922) 全文精读：WAM 零样本策略
description: 2602.15922 WAM=zero-shot policy；视频-动作联合扩散；跨本体video-only；与 Zero-WAM(2608.26103) 区分
tags: [专题, ZeroWAM, DreamZero, WAM, world-model, ICL, 跨本体, 精读]
created: 2026-08-30
feishu_wiki: https://huazhi-ai.feishu.cn/wiki/MhU1wbs0siakdAkYsUMc4Jcdneg
feishu_docx: MPy8dpHkqo5Bc8xa4bOcM05Xnfc
arxiv: 2602.15922
---

# 专题 · DreamZero(2602.15922) 全文精读：WAM 零样本策略

> ⚠ 注意：本页是 **DreamZero (2602.15922)**，不是“Zero-WAM”。真正的 **Zero-WAM (2608.26103)** 见另一篇（ICL 人类视频任务规格）。切勿混淆。

> **论文**：✔ arXiv **2602.15922** · *World Action Models are Zero-shot Policies*（NVIDIA）  
> **名称**：论文主打 **DreamZero**（14B WAM），常被简称为 ZeroWAM 话题。  
> **作者网**：Seonghyeon Ye… **Danfei Xu**, Yilun Du, Yuke Zhu, **Jim Fan**, Joel Jang 等（NVIDIA + 学界）。  
> **站点**：https://dreamzero0.github.io  
> **飞书**：主文档下子文档

---

## 0 · 一句话

**DreamZero = 基于预训练视频扩散主干（Wan/TEAM 14B）的 World Action Model（WAM）：联合预测「未来视频 + 动作」，靠世界物理先验实现「零样本地学技能 + 开世界泛化 + 视频-only 跨本体 + few-shot 新本体适应」。**

**对 ICL 这件事的核心答案**：DreamZero 的**零样本泛化**是真·推理期条件化（ICL 式）；但**跨本体/少样本适应是 post-training（梯度更新）**，不是纯 ICL。→ **ICL 的边界 = 它给"语义/任务/环境"泛化，但"新本体动作动力学"仍需至少一次表征内共同训练。**

---

## 1 · 问题：VLA 的盲区

VLA（如 GR00T、Gemini Robotics）有语言先验，能靠 web 知识识别"把可乐放 Taylor Swift 桌上"这类**语义目标**，但**对训练数据里没有的物理动作技能（如系鞋带）几乎无解**。

> "VLM priors 告诉你 what 该做什么，但缺 how —— 如何用精确空间觉知、对齐几何/动力学/电机控制去执行。"

VLA 泛化新环境/新任务，需大量收集任务-环境特定动作数据。

---

## 2 · 方法：DreamZero 三个关键设计

**三个挑战**：视频-动作对齐 / 双向 vs 自回归架构 / 实时推理（视频扩散慢）。

1. **单模型端到端联合去噪**（视频+动作共享目标）
   联合预测 \(o_{l:l+H}, a_{l:l+H} | o_{0:l}, c, q_l\)，分解为：
   - 自回归视频预测 \(o_{l:l+H}|o_{0:l},c,q_l\)
   - 逆动力学 IDM \(a_{l:l+H}|o_{0:l+H},q_l\)
   - **但用一个模型端到端联合学**（而非视频模型 + IDM 两个分开模型）→ 深深绑定两模态。

2. **自回归 + 闭环 KV-cache 替换**
   执行完 action chunk 后，用**真实观测替换预测帧进 KV cache** → 消除累积误差 + 高效推理（KV caching 保原生帧率）。

3. **38× 推理加速**（系统+实现+模型级优化）→ **7Hz 实时闭环**（2×GB200）。

**数据观**：从"反复精心演示"转向**异构轨迹（play data）**即可学技能——因为视频作为稠密表征承担了简单逆动力学之外的动力学学习。

---

## 3 · 结果（四大 claim）

| 维度 | 结果 |
|---|---|
| **开世界泛化** | vs SOTA VLA，环境/任务泛化平均任务进度 **>2×** |
| **实时** | 14B 自回归视频扩散，7Hz 闭环 |
| **video-only 跨本体** | 10–20 min 视频数据（无动作）→ 未见任务 +42% 相对提升 |
| **few-shot 新本体** | 仅 30 min play 数据适应新机器人，保留零样本泛化 |

### 关键实验细节
- **跨本体（video-only）**：YAM→AgiBot 38.3→**55.4%**；Human→AgiBot 38.3→**54.3%**。只给 **72 条多视角轨迹**（20/12 min）。
- **few-shot 新本体**：AgiBot→YAM，**55 轨迹 / 11 任务（~30 min）** post-training → 语言跟随 pick-and-place 保留。

---

## 4 · （重点）★ "ICL 说明了什么" —— 深入辨析

### 4.1 先把事实摆正：什么是真 ICL，什么是 post-training

| DreamZero 能力 | 实现方式 | 是 ICL 吗 |
|---|---|---|
| 未见**任务/环境**的零样本泛化 | 一次预训练，推理时只给语言+观测条件 | ✅ **真·推理期条件化** |
| 跨本体 video-only 转移 | **10K 步 co-train（1:1 与预训练数据）** | ❌ 是共同训练（梯度） |
| few-shot 新本体适应 | 30 min **post-training 微调** | ❌ 是梯度更新 |

**关键：作者把"few-shot embodiment adaptation"叫 adaptation，但实现是 post-training。** 这也解释了标题为什么是"Zero-shot policies"而非"in-context policies"。

### 4.2 ICL 说明的四件事

**① ICL 给的是"世界/语义"杠杆，不是"电机动力学"杠杆。**
DreamZero 零样本泛化新环境/任务 = 语言+观测条件化，激活预训练视频扩散的**世界物理先验**（空间、动作、目标语义）。这正是 LLM ICL 的具身版：**不更新权重，靠条件化 + 先验**。但一旦要换**本体**（新机械结构、新动作空间），条件化不够——需要梯度。**→ ICL 擅长交换"任务语义"，不擅长交换"本体物理"。**

**② ICL 的前提是"先验足够丰富 + 表征足够稠密"。**
DreamZero 能用 video-only 跨本体，是因为视频是**稠密世界表征**，本身承载了任务动力学；LLM ICL 能用是因为语言是**稠密语义表征**。**→ ICL 的强度取决于条件信号的表征密度**，不是"in-context"三个字本身。

**③ 少样本 ≠ ICL；"30 min 适应"是更强的声明。**
多数 RL/IL 的 few-shot 是微调。把 30 min 说成"few-shot"容易误读成 ICL。**→ 跨本体的"迁移"仍要一次 mini 共同训练，可视为"少样本具身微调"而非推理期 ICL**——这对"免训练跨本体"的期望是冷水。

**④ ICL 是数据侧结论，不是算法侧魔法。**
DreamZero 能零样本，根因是**视频扩散从 web 学到的世界先验 + 异构数据**，而非某种"in-context 机制"。**→ ICL 在具身的可行性，本质是"数据多样性"问题，回到你的「数据×训练」主线。**

### 4.3 一句话总结 ICL 之辨
> **ZeroWAM 证明：ICL 式的"条件化先验"能让具身模型零样本地跨任务、跨环境（语义/世界层）；但它不自动跨本体（物理/动力学层）——后者仍需至少 30 分钟/少量轨迹的梯度共同训练。ICL 告诉我们"数据先验能换多少泛化"，也划定了"先验换不动动力学时要回到数据/训练"。**

---

## 5 · 与其他 WAM/EGO 线的咬合

- **与 EgoWAM (2607.08436)**：EgoWAM 用世界表示(3D flow/DINO)做迁移接口；DreamZero 用**视频世界表征做接口**——同一主张"世界表征是可迁移接口"，但 DreamZero 直接预训练在视频 => 更强先验。
- **与 EgoVerse/人 EGO 数据**：Human→AgiBot **54.3%** = 具身"人视频当世界经验"又一个实证；呼应 EgoVerse"human data 供世界层"。
- **与数据×训练**：Zero-shot 泛化 = 预训练视频世界先验的价值；few-shot 适配要梯度 = 数据"性质(本体-dynamics)"决定需要哪种训练。**视频稠密表征 = 让"ICL(-like) 可迁移面"变大的关键。**

---

## 6 · 局限（分析补）
- **high-precision 任务**：作者自承 sub-cm 精度（插销/细装配）仍受 BC 式局限——稠密数据优先广度、缺密演示。
- **推理贵**：7Hz@2×GB200 vs VLA 20Hz@消费卡——视频扩散仍重。
- **长程**：视觉记忆目前短程（~6s），需 System2/更长上下文。
- **跨本体成功率仍中等**（~54%）——"video→动作"迁移信号在，但未到可用水平。

## 7 · 口径
**DreamZero（2602.15922，NVIDIA）以 14B 视频扩散为骨干、联合预测视频与动作构建 WAM，靠世界物理先验实现零样本跨任务/环境（>2× over VLA）、7Hz 实时闭环、video-only 跨本体(+42%)与 30 min 少样本新本体适应。它印证"视频稠密表征是 ICL 式零样本的具身接口"，同时划清边界：跨本体迁移靠 mini co-train 而非纯推理期 ICL——语义/世界可零样本，动力学仍需一次表征共同训练。**

## 8 · 关联
EgoWAM(世界表示) · EgoVerse(人数据) · 具身世界模型(RoboPhys-3D) · 数据×训练 · 跨本体统一动作空间 · WandB 评估线
