---
citekey: "chenAnyWorldFactorizedEgocentricWorldModelsCrossEmbodimentGeneralization2026"
title: "AnyWorld: Factorized Egocentric World Models for Cross-Embodiment Generalization"
authors: ["Cheng Chen", "Jerry Bai", "Jiacheng Wei", "Boyu Chen", "Xiaoji Zheng", "Fan Wu", "Minghao Yang", "Tianrun Chen", "Ruibo Li", "Xiaoyu Yue", "Xiaoyang Guo", "Yixiao Ge", "Guosheng Lin", "Fayao Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29242"
doi: "10.48550/arXiv.2608.29242"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-01
---

# AnyWorld: Factorized Egocentric World Models for Cross-Embodiment Generalization

> Cheng Chen, Jerry Bai, Jiacheng Wei, Boyu Chen, Xiaoji Zheng, Fan Wu, Minghao Yang, Tianrun Chen, Ruibo Li, Xiaoyu Yue, Xiaoyang Guo, Yixiao Ge, Guosheng Lin, Fayao Liu · 2026
> [arXiv](https://arxiv.org/abs/2608.29242) · [PDF](https://arxiv.org/pdf/2608.29242)

## Abstract

Collecting contact-rich robot experiences at scale remains a major bottleneck for generalizable manipulation. Beyond data quantity, robot learning also requires diverse experiences across embodiments, viewpoints, and scenes. Human egocentric videos provide abundant physical interactions, but each video captures only a narrow slice of experience under a single body, camera trajectory, and environment. We propose AnyWorld, a cross-embodiment world modeling framework that expands a single human interaction into diverse robot-native rollouts without paired human-robot demonstrations. Our model factorizes an interaction into action, camera, and embodiment: action controls capture the motion structure, camera controls specify viewpoint evolution, and the target embodiment context defines the acting body and its interaction geometry. This formulation enables independent recomposition of embodiment, viewpoint, and scene factors, allowing a single model to generate many robot-domain experiences while preserving the underlying dynamics and object interactions. We train the model with large-scale human interaction pretraining followed by mixed-embodiment fine-tuning. Experiments show that our model supports controllable recomposition across embodiments, viewpoints, and scenes, and we further demonstrate that the generated data can improve manipulation performance on the RoboCasa GR1 tabletop benchmark and a real IRON humanoid robot. Beyond aggregate gains, we test whether unpaired human experience can be recomposed into robot-native video-action pairs that target a policy gap. Controlled IRON interventions correct a spurious completion prior and establish language-grounded spatial target selection; an action-only counterfactual intervention fails to learn the latter reliably, showing that both action calibration and visual recomposition are necessary.

## TL;DR

Collecting contact-rich robot experiences at scale remains a major bottleneck for generalizable manipulation. Beyond data quantity, robot learning also requires diverse experiences across embodiments, viewpoints, and scenes.

## Related
<!-- [[other-paper-citekey]] -->
