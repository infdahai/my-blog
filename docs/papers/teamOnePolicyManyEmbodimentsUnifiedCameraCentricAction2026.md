---
citekey: "teamOnePolicyManyEmbodimentsUnifiedCameraCentricAction2026"
title: "One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation"
authors: [" Xiaomi Embodied Intelligence Team", "University of Macau", " :", "Shaoqing Xu", "Fang Li", "Guozhi Zhan", "Zhixiang Duan", "Yuhan Wang", "Yuechen Luo", "Shengyin Jiang", "Hanbing Li", "Zhiying Du", "Longlong Wang", "Longmei Jiang", "Weixiang Liang", "Ying Gong", "Yong Pan", "Ziping Zhao", "Zhiyuan Chen", "Yangwei You", "Kun Ma", "Qinyuan Liu", "Hangjun Ye", "Zhi-xin Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.26058"
doi: "10.48550/arXiv.2608.26058"
tags: [paper, embodied-ai, "cs.RO"]
status: read
rating: 4
created: 2026-08-27
---

# One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation

>  Xiaomi Embodied Intelligence Team, University of Macau,  :, Shaoqing Xu, Fang Li, Guozhi Zhan, Zhixiang Duan, Yuhan Wang, Yuechen Luo, Shengyin Jiang, Hanbing Li, Zhiying Du, Longlong Wang, Longmei Jiang, Weixiang Liang, Ying Gong, Yong Pan, Ziping Zhao, Zhiyuan Chen, Yangwei You, Kun Ma, Qinyuan Liu, Hangjun Ye, Zhi-xin Yang · 2026
> [arXiv](https://arxiv.org/abs/2608.26058) · [PDF](https://arxiv.org/pdf/2608.26058)

## Abstract

Scaling generalist vision-language-action (VLA) policies is severely bottlenecked by the inherent heterogeneity of embodied data, which spans diverse robot morphologies, camera configurations, and low-level action spaces. Existing paradigms typically address this mismatch through explicit action retargeting, human-to-robot video synthesis, or dataset-specific adaptation branches, fundamentally hindering the joint learning of a unified policy. We introduce UCAG-P, a camera-centric unified action formulation that structurally aligns heterogeneous embodied datasets into a shared geometric action space. Rather than treating robot-specific commands as the shared policy target, UCAG-P represents manipulation through camera-observable anchor motion in image and camera-frame coordinates, treating robot arms, humanoids, and human hands as different embodiments of a common action schema. A geometry-conditioned action translator combines predicted motion with target-embodiment kinematics to produce executable controls. The resulting decoupled architecture allows a shared VLA policy to learn transferable manipulation geometry while retaining embodiment-specific controllability. UCAG-P is trained on 4.03K hours of robot and simulation data and 2.34K hours of human demonstrations. A single checkpoint reaches 98.3% on LIBERO, 88.7% and 89.2% on RoboTwin Easy and Hard, 82.0% zero-shot on LIBERO-Plus, and 62.0% on RoboCasa GR-1, without benchmark-specific fine-tuning.

## TL;DR

Scaling generalist vision-language-action (VLA) policies is severely bottlenecked by the inherent heterogeneity of embodied data, which spans diverse robot morphologies, camera configurations, and low-level action spaces. Existing paradigms typically address this mismatch through explicit action retargeting, human-to-robot video synthesis, or dataset-specific adaptation branches, fundamentally hindering the joint learning of a unified policy.

## 深读（研究员）

**定位**：动作空间统一/解耦系（非数据改造系）。同族：UHAS / KITE / Motion-Focused / UniDexTok，但落点是更干净的「相机中心几何动作空间」。

**核心思想**：异构本体数据（形态×相机位×动作空间）合训被卡死的根源是**共享策略目标被定义成了"机器人专用指令"**。UCAG-P 不重定向、不合成、不加分支，而是把共享目标换成 **相机可观测的锚点运动**（image + camera-frame 坐标），机械臂/人形/人手都变成"同一动作模式"的不同实例。

**方法到实现（层）**：①统一动作公式：用相机可视锚点运动做共享 target（label 空间重构，而非数据改写）②几何条件化动作翻译器：预测运动 + 目标本体运动学 → 可执行控制 ③解耦架构：共享 VLA 学可迁移的"操作几何"，本体专用控制头保持可控。数据：4.03K h 机器人/仿真 + 2.34K h 人手示范，不作 benchmark 微调：LIBERO 98.3%，LIBERO-Plus 零样本 82%，RoboTwin 88.7/89.2，RoboCasa GR-1 62%。

**为什么重要（真洞察）**：
- 这是纲领「统一动作空间」层的**教科书级实现**：无需动作重定向，就让异构合训成立——把"跨本体桥"的代价从「改写示范数据」降到「重标动作空间」。
- 人手示范（2.34K h）与多本体+仿真**同空间直接合训**，且零样本吃下 LIBERO-Plus——实证了「统一动作空间×多源共训」这条路存在，是对证据清单缺口①的**有力部分填补**。
- 对「数据×训练」的意义：当动作空间统一后，**各源数据的边际贡献才谈得上公平比较**（否则重定向噪声污染了贡献测量）——它为缺口②的消融打了地基。

**局限·下一步**：
- 用了人手示范 + 机器人 + 仿真，但**未含 EGO 被动视频**（第一视角人体视频作为数据源）——④源头还有一格；
- 相机中心表述对多相机/大视差/长臂遮挡的可迁移性待验；
- 翻译器/运动学耦合在硬件差异极大（软手/气动）时是否崩未知；
- 数字强但多为受限语法基准（LIBERO），开放世界长程未见。

**一句话**：把「动作空间」而非「数据」统一，异构机器人+仿真+人手免重定向合训成一根权重——统一动作空间路线的强实证。

## Related
<!-- [[other-paper-citekey]] -->
