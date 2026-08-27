---
citekey: "louLMXExplainableActionModelingProgressEventUncertainty2026"
title: "LM-X: Explainable Action Modeling with Progress, Event, and Uncertainty Prediction for Generalist Robot Manipulation"
authors: ["Jin Lou", "Jingxuan Zhu", "Andong Chen", "Xupeng Wang", "Yuan Xu", "Yuexuan Li", "Xingdong Zhu", "Zhijie Zhu", "Yingwei Ji", "Wenpeng Nie", "Jingyi Li", "Liangliang Chen", "Jinyan Liu", "Zhiqi Song", "Jidong Zhang", "Hongming Li", "Yuchen Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25757"
doi: "10.48550/arXiv.2608.25757"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# LM-X: Explainable Action Modeling with Progress, Event, and Uncertainty Prediction for Generalist Robot Manipulation

> Jin Lou, Jingxuan Zhu, Andong Chen, Xupeng Wang, Yuan Xu, Yuexuan Li, Xingdong Zhu, Zhijie Zhu, Yingwei Ji, Wenpeng Nie, Jingyi Li, Liangliang Chen, Jinyan Liu, Zhiqi Song, Jidong Zhang, Hongming Li, Yuchen Zhu · 2026
> [arXiv](https://arxiv.org/abs/2608.25757) · [PDF](https://arxiv.org/pdf/2608.25757)

## Abstract

Generalist vision--language--action (VLA) policies learn long-horizon behavior mainly through short-horizon action prediction and reveal little beyond sampled commands. This creates two coupled bottlenecks: a single action target must implicitly absorb task progress, intermediate intent, and local reliability, while these control states remain hidden during execution. Inspired by functional principles of biological sensorimotor control, we introduce LM-X , which organizes prediction across task, event, and motor scales without claiming anatomical correspondence. Three explicitly supervised signals are emitted online and directly condition action generation: return-to-go (RTG) measures visible task progress, event-to-go (ETG) identifies the next semantic transition, and heteroscedastic action flow estimates local reliability through propagated variance. Explanation is therefore intrinsic to control rather than generated post hoc. Before a costly 20-day pretraining run on 64 NVIDIA B200 GPUs, a controlled five-task pretraining gate verifies the design: the complete model improves success by 16.0 points over the action-only backbone and by 10.8 points over the strongest single-head variant. We then train LM-X on more than 20,000 hours of real-robot trajectories, including over 1,000 hours of failed policy rollouts. LM-X achieves 74.1\% across 50 randomized-hard RoboTwin2.0 tasks versus 55.4\% for GR00T N1.7, and 68.6\% versus 50.7\% across seven real-robot tasks. RTG tracks semantic progress and visible regression, while variance rises during hesitation and oscillatory control. These results show that explicit multi-timescale predictive state can strengthen control while exposing interpretable internal estimates.

## TL;DR

Generalist vision--language--action (VLA) policies learn long-horizon behavior mainly through short-horizon action prediction and reveal little beyond sampled commands. This creates two coupled bottlenecks: a single action target must implicitly absorb task progress, intermediate intent, and local reliability, while these control states remain hidden during execution.

## Related
<!-- [[other-paper-citekey]] -->
