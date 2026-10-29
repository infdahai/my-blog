---
citekey: "luoReflectVLAInternalizingReflectiveGuidanceDualPathPolicy2026"
title: "Reflect-VLA: Internalizing Reflective Guidance via Dual-Path On-Policy Self-Distillation for Autonomous Driving"
authors: ["Yuechen Luo", "He Chong", "Fang Li", "Shaoqing Xu", "Hexin Zhang", "Ruiqi Zhang", "Ziying Song", "Lei Yang", "Zhi-Xin Yang", "Fuxi Wen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13453"
doi: "10.48550/arXiv.2610.13453"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Reflect-VLA: Internalizing Reflective Guidance via Dual-Path On-Policy Self-Distillation for Autonomous Driving

> Yuechen Luo, He Chong, Fang Li, Shaoqing Xu, Hexin Zhang, Ruiqi Zhang, Ziying Song, Lei Yang, Zhi-Xin Yang, Fuxi Wen · 2026
> [arXiv](https://arxiv.org/abs/2610.13453) · [PDF](https://arxiv.org/pdf/2610.13453)

## Abstract

Reinforcement Learning (RL) substantially improves planning performance in autonomous-driving Vision-Language-Action (VLA) models. However, existing RL methods rely on scalar trajectory rewards that measure overall quality but fail to identify specific planning errors or provide actionable correction signals. In long-tail scenarios, errors in scene understanding, behavior selection, and trajectory execution are compressed into a single score. We observe that Reflective Guidance turns trajectory evaluation into explicit diagnoses and corrective instructions, substantially improving planning accuracy. Yet such guidance requires an initial prediction and its evaluation results, making it unavailable for direct single-pass inference. We propose Reflect-VLA, which treats Reflective Guidance as training-time privileged information and internalizes its planning benefits through Dual-Path On-Policy Self-Distillation (Dual-OPSD). Unlike scalar-reward optimization, Dual-OPSD uses the driving score only to route student-generated trajectories. It distills dense token-level corrective distributions from the teacher for risky trajectories while applying self-imitation to preserve reliable ones. To provide reliable corrective distributions on student rollouts, the teacher is progressively constructed through Driving-Knowledge Pretraining, Planning-and-Refinement SFT, and Self-Refinement Rejection Sampling. At inference time, Reflect-VLA generates trajectories in a single pass without explicit guidance or iterative refinement. Experiments on NAVSIM v1/v2 and Bench2Drive demonstrate competitive planning performance while reducing training time by over 90% compared with RL.

## TL;DR

Reinforcement Learning (RL) substantially improves planning performance in autonomous-driving Vision-Language-Action (VLA) models. However, existing RL methods rely on scalar trajectory rewards that measure overall quality but fail to identify specific planning errors or provide actionable correction signals.

## Related
<!-- [[other-paper-citekey]] -->
