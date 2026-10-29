---
citekey: "junDriftOPDSequenceLevelReverseKLDistillationOneStep2026"
title: "DriftOPD: Sequence-Level Reverse-KL Distillation for One-Step VLA Policies"
authors: ["Youngjun Jun", "Kyumin Choi", "Youngmin Kim", "Seonghyun Jin", "Sunwoo Park", "Jangho Park", "Jong Chul Ye"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00317"
doi: "10.48550/arXiv.2610.00317"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# DriftOPD: Sequence-Level Reverse-KL Distillation for One-Step VLA Policies

> Youngjun Jun, Kyumin Choi, Youngmin Kim, Seonghyun Jin, Sunwoo Park, Jangho Park, Jong Chul Ye · 2026
> [arXiv](https://arxiv.org/abs/2610.00317) · [PDF](https://arxiv.org/pdf/2610.00317)

## Abstract

Vision-Language-Action (VLA) models increasingly rely on action experts that generate short action chunks under receding-horizon control. While chunk-level training is convenient across robot embodiments, it optimizes local action likelihood without explicitly accounting for long-horizon task success. Sequence-level reinforcement learning can address this limitation, but typically requires policy rollouts and closed-loop interaction, which are costly for real-robot manipulation. We introduce DriftOPD, a teacher-free, rollout-free framework for sequence-level on-policy distillation of continuous VLA action experts. We show that the sequence-level reverse Kullback-Leibler (KL) divergence decomposes into a chunk-level reverse-KL term and a future-potential term that captures the long-horizon effect of the current action. DriftOPD optimizes these two terms using a one-step drifting objective and a Q-function critic learned from offline demonstrations, respectively, enabling sequence-level optimization with only offline data and one-step action generation. Across multiple VLA architectures in simulation and real-world manipulation, DriftOPD generally outperforms existing one-step distillation baselines while achieving task success performance comparable to multi-step teacher policies. These results demonstrate that long-horizon behavior can be effectively distilled into one-step VLA action experts without online interaction or a separate teacher.

## TL;DR

Vision-Language-Action (VLA) models increasingly rely on action experts that generate short action chunks under receding-horizon control. While chunk-level training is convenient across robot embodiments, it optimizes local action likelihood without explicitly accounting for long-horizon task success.

## Related
<!-- [[other-paper-citekey]] -->
