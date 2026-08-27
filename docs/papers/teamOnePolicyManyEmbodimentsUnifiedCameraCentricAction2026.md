---
citekey: "teamOnePolicyManyEmbodimentsUnifiedCameraCentricAction2026"
title: "One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation"
authors: [" Xiaomi Embodied Intelligence Team", "University of Macau", " :", "Shaoqing Xu", "Fang Li", "Guozhi Zhan", "Zhixiang Duan", "Yuhan Wang", "Yuechen Luo", "Shengyin Jiang", "Hanbing Li", "Zhiying Du", "Longlong Wang", "Longmei Jiang", "Weixiang Liang", "Ying Gong", "Yong Pan", "Ziping Zhao", "Zhiyuan Chen", "Yangwei You", "Kun Ma", "Qinyuan Liu", "Hangjun Ye", "Zhi-xin Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.26058"
doi: "10.48550/arXiv.2608.26058"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation

>  Xiaomi Embodied Intelligence Team, University of Macau,  :, Shaoqing Xu, Fang Li, Guozhi Zhan, Zhixiang Duan, Yuhan Wang, Yuechen Luo, Shengyin Jiang, Hanbing Li, Zhiying Du, Longlong Wang, Longmei Jiang, Weixiang Liang, Ying Gong, Yong Pan, Ziping Zhao, Zhiyuan Chen, Yangwei You, Kun Ma, Qinyuan Liu, Hangjun Ye, Zhi-xin Yang · 2026
> [arXiv](https://arxiv.org/abs/2608.26058) · [PDF](https://arxiv.org/pdf/2608.26058)

## Abstract

Scaling generalist vision-language-action (VLA) policies is severely bottlenecked by the inherent heterogeneity of embodied data, which spans diverse robot morphologies, camera configurations, and low-level action spaces. Existing paradigms typically address this mismatch through explicit action retargeting, human-to-robot video synthesis, or dataset-specific adaptation branches, fundamentally hindering the joint learning of a unified policy. We introduce UCAG-P, a camera-centric unified action formulation that structurally aligns heterogeneous embodied datasets into a shared geometric action space. Rather than treating robot-specific commands as the shared policy target, UCAG-P represents manipulation through camera-observable anchor motion in image and camera-frame coordinates, treating robot arms, humanoids, and human hands as different embodiments of a common action schema. A geometry-conditioned action translator combines predicted motion with target-embodiment kinematics to produce executable controls. The resulting decoupled architecture allows a shared VLA policy to learn transferable manipulation geometry while retaining embodiment-specific controllability. UCAG-P is trained on 4.03K hours of robot and simulation data and 2.34K hours of human demonstrations. A single checkpoint reaches 98.3% on LIBERO, 88.7% and 89.2% on RoboTwin Easy and Hard, 82.0% zero-shot on LIBERO-Plus, and 62.0% on RoboCasa GR-1, without benchmark-specific fine-tuning.

## TL;DR

Scaling generalist vision-language-action (VLA) policies is severely bottlenecked by the inherent heterogeneity of embodied data, which spans diverse robot morphologies, camera configurations, and low-level action spaces. Existing paradigms typically address this mismatch through explicit action retargeting, human-to-robot video synthesis, or dataset-specific adaptation branches, fundamentally hindering the joint learning of a unified policy.

## Related
<!-- [[other-paper-citekey]] -->
