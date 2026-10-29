---
citekey: "zouVLAStemLightweightSafetyMechanismVisionLanguageAction2026"
title: "VLA-Stem: A Lightweight Safety Mechanism for Vision-Language-Action Models via Reinforcement Learning"
authors: ["Bojun Zou", "Wenhao Yu", "Jiaohao Li", "Jiaxuan Lin", "Guanting Ye", "Haohan Geng", "Weihao Yu", "Yanyong Zhang", "Jianmin Ji"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.37378"
doi: "10.48550/arXiv.2610.37378"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# VLA-Stem: A Lightweight Safety Mechanism for Vision-Language-Action Models via Reinforcement Learning

> Bojun Zou, Wenhao Yu, Jiaohao Li, Jiaxuan Lin, Guanting Ye, Haohan Geng, Weihao Yu, Yanyong Zhang, Jianmin Ji · 2026
> [arXiv](https://arxiv.org/abs/2610.37378) · [PDF](https://arxiv.org/pdf/2610.37378)

## Abstract

Vision-Language-Action (VLA) models integrate high-level reasoning with low-level action execution for end-to-end robotic control. However, most VLA models target static manipulation in unconstrained environments, overlooking spatial constraints and dynamic obstacles. Fine-tuning VLAs on obstacle-avoidance data is a straightforward solution, but collecting such data is costly, especially for dynamic scenarios, and may degrade their original task capabilities. To address these limitations, we propose VLA-Stem, a lightweight, reinforcement-learning-based safety mechanism for VLA systems. Without fine-tuning the underlying VLA policy, VLA-Stem converts its action chunks into motion references and uses trajectory-level guidance to preserve their spatial intent while allowing flexible motion and timing adjustments. Conditioned on these references, robot proprioception, and local obstacle information, the Stem policy adaptively modifies execution at inference time, preserving the original task intent while enabling responsive adaptation to spatial constraints and dynamic obstacles. For robust and sample-efficient training, we combine teacher-student distillation with curriculum learning. We evaluate VLA-Stem on reference following, static spatial constraints, and dynamic obstacle avoidance. Across six constrained simulation settings, VLA-Stem achieves 52.8% average collision-free task success versus 23.7% for the strongest safety baseline, while preserving base-policy performance in obstacle-free settings; real-world experiments further show consistent collision reductions under static and dynamic obstacles. These results demonstrate that VLA-Stem couples high-level VLA task intent with rapid, reflex-like responses to immediate physical risks, providing a brainstem-inspired mechanism for robust robot execution.

## TL;DR

Vision-Language-Action (VLA) models integrate high-level reasoning with low-level action execution for end-to-end robotic control. However, most VLA models target static manipulation in unconstrained environments, overlooking spatial constraints and dynamic obstacles.

## Related
<!-- [[other-paper-citekey]] -->
