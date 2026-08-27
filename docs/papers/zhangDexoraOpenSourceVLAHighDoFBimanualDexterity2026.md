---
citekey: "zhangDexoraOpenSourceVLAHighDoFBimanualDexterity2026"
title: "Dexora: Open-source VLA for High-DoF Bimanual Dexterity"
authors: ["Zongzheng Zhang", "Jingrui Pang", "Zhuo Yang", "Kun Li", "Minwen Liao", "Saining Zhang", "Guoxuan Chi", "Jinbang Guo", "Huan-ang Gao", "Modi Shi", "Dongyun Ge", "Yao Mu", "Jiayuan Gu", "Rui Chen", "Hao Dong", "Huazhe Xu", "Li Yi", "Yixin Zhu", "Hang Zhao", "Pengwei Wang", "Shanghang Zhang", "Guocai Yao", "Jianyu Chen", "Hongyang Li", "Hao Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2605.18722"
doi: "10.48550/arXiv.2605.18722"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Dexora: Open-source VLA for High-DoF Bimanual Dexterity

> Zongzheng Zhang, Jingrui Pang, Zhuo Yang, Kun Li, Minwen Liao, Saining Zhang, Guoxuan Chi, Jinbang Guo, Huan-ang Gao, Modi Shi, Dongyun Ge, Yao Mu, Jiayuan Gu, Rui Chen, Hao Dong, Huazhe Xu, Li Yi, Yixin Zhu, Hang Zhao, Pengwei Wang, Shanghang Zhang, Guocai Yao, Jianyu Chen, Hongyang Li, Hao Zhao · 2026
> [arXiv](https://arxiv.org/abs/2605.18722) · [PDF](https://arxiv.org/pdf/2605.18722)

## Abstract

Vision-Language-Action (VLA) models have recently become a central direction in embodied AI, but current systems are restricted to either dual-gripper control or single-arm dexterous hand manipulation. While low-dimensional gripper control can often be handled with simpler methods, high-dimensional dexterous hand control benefits greatly from full end-to-end VLA learning. In this work, we introduce Dexora, the first open-source VLA system that natively targets dual-arm, dual-hand high-DoF manipulation. We design a hybrid teleoperation pipeline that decouples gross arm kinematics (captured with a custom exoskeleton backpack) from fine finger motion (markerless hand tracking via Apple Vision Pro), and that drives both a physical dual-arm dual-hand platform and an identical MuJoCo digital twin. Using that interface, we assemble a large training corpus: an embodiment-matched synthetic corpus (100K simulated trajectories, 6.5M frames) and a real-world dataset of 10K teleoperated episodes (2.92M frames). To mitigate noisy teleoperation demonstrations, we propose a data-quality-aware training recipe: an offline discriminator provides clip-level weights for diffusion-transformer policy training, down-weighting low-quality demonstrations. Empirically, Dexora outperforms competitive VLA baselines on both basic and dexterous benchmarks (e.g., average dexterous success 66.7% vs. 51.7%), attains 90% success on basic tasks, and shows robust out-of-distribution and cross-embodiment generalization. Ablations confirm the importance of real data and the discriminator for dexterity.

## TL;DR

Vision-Language-Action (VLA) models have recently become a central direction in embodied AI, but current systems are restricted to either dual-gripper control or single-arm dexterous hand manipulation. While low-dimensional gripper control can often be handled with simpler methods, high-dimensional dexterous hand control benefits greatly from full end-to-end VLA learning.

## Related
<!-- [[other-paper-citekey]] -->
