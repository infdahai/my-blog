---
citekey: "wangLearningWhileDeployingFleetScaleReinforcementLearningGeneralist2026"
title: "Learning While Deploying: Fleet-Scale Reinforcement Learning for Generalist Robot Policies"
authors: ["Yi Wang", "Xinchen Li", "Pengwei Xie", "Pu Yang", "Buqing Nie", "Yunuo Cai", "Qinglin Zhang", "Chendi Qu", "Jeffrey Wu", "Jianheng Song", "Xinlin Ren", "Jingshun Huang", "Mingjie Pan", "Siyuan Feng", "Zhi Chen", "Jianlan Luo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2605.00416"
doi: "10.48550/arXiv.2605.00416"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Learning While Deploying: Fleet-Scale Reinforcement Learning for Generalist Robot Policies

> Yi Wang, Xinchen Li, Pengwei Xie, Pu Yang, Buqing Nie, Yunuo Cai, Qinglin Zhang, Chendi Qu, Jeffrey Wu, Jianheng Song, Xinlin Ren, Jingshun Huang, Mingjie Pan, Siyuan Feng, Zhi Chen, Jianlan Luo · 2026
> [arXiv](https://arxiv.org/abs/2605.00416) · [PDF](https://arxiv.org/pdf/2605.00416)

## Abstract

Generalist robot policies increasingly benefit from large-scale pretraining, but offline data alone is insufficient for robust real-world deployment. Deployed robots encounter distribution shifts, long-tail failures, task variations, and human correction opportunities that fixed demonstration datasets cannot fully capture. We present Learning While Deploying (LWD), a fleet-scale offline-to-online reinforcement learning framework for continual post-training of generalist Vision-Language-Action (VLA) policies. Starting from a pretrained VLA policy, LWD closes the loop between deployment, shared physical experience, policy improvement, and redeployment by using autonomous rollouts and human interventions collected across a robot fleet. To stabilize learning from heterogeneous, sparse-reward fleet data, LWD combines Distributional Implicit Value Learning (DIVL) for robust value estimation with Q-learning via Adjoint Matching (QAM) for policy extraction in flow-based VLA action generators. We validate LWD on a fleet of 16 dual-arm robots across eight real-world manipulation tasks, including semantic grocery restocking and 3--5 minute long-horizon tasks. A single generalist policy improves as fleet experience accumulates, reaching an average success rate of 95%, with the largest gains on long-horizon tasks.

## TL;DR

Generalist robot policies increasingly benefit from large-scale pretraining, but offline data alone is insufficient for robust real-world deployment. Deployed robots encounter distribution shifts, long-tail failures, task variations, and human correction opportunities that fixed demonstration datasets cannot fully capture.

## Related
<!-- [[other-paper-citekey]] -->
