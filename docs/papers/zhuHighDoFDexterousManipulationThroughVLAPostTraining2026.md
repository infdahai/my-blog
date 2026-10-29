---
citekey: "zhuHighDoFDexterousManipulationThroughVLAPostTraining2026"
title: "Towards High-DoF Dexterous Manipulation through VLA Post-Training"
authors: ["Junlei Zhu", "Shenzhe Yao", "Chaogui Huang", "Wenkai Zhu", "Jingwei Peng", "Guanqi He", "Soren Schwertfeger", "Jiahao Chen", "Yide Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.19666"
doi: "10.48550/arXiv.2609.19666"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# Towards High-DoF Dexterous Manipulation through VLA Post-Training

> Junlei Zhu, Shenzhe Yao, Chaogui Huang, Wenkai Zhu, Jingwei Peng, Guanqi He, Soren Schwertfeger, Jiahao Chen, Yide Liu · 2026
> [arXiv](https://arxiv.org/abs/2609.19666) · [PDF](https://arxiv.org/pdf/2609.19666)

## Abstract

Imitation-learned vision--language--action (VLA) foundation models acquire broad manipulation capabilities by scaling robot data across tasks and embodiments, but reliable deployment on a specific downstream task and hardware platform still requires post-training. Dexterous hands make this adaptation particularly difficult: their broad behavioural repertoire and high degree of freedom create a large and structured action space. Three obstacles are central: open-source VLAs do not natively provide an action interface for high-DoF hands; gesture mismatch during human-gated DAgger takeover creates command discontinuities and contaminates corrective trajectories; and reinforcement learning in the raw joint space is sample-inefficient. We present a unified four-step post-training pipeline comprising a learned temporal hand-action codec, supervised fine-tuning, DAgger, and real-world residual reinforcement learning. The codec adapts a pretrained VLA to absolute dexterous-hand commands. Buffered rollback, pose alignment, and smooth command blending enable continuous, task-relevant DAgger corrections, while latent residual RL confines exploration to coordinated hand motions captured by the codec. We evaluate the pipeline on five diverse real-world tasks spanning bimanual transfer, in-hand reorientation, and tool use. Within the reported post-training budgets, the resulting policies achieve 100\% success on every evaluated task over 20 trials per task. These results provide a practical path for adapting VLA foundation models to reliable real-world dexterous manipulation.

## TL;DR

Imitation-learned vision--language--action (VLA) foundation models acquire broad manipulation capabilities by scaling robot data across tasks and embodiments, but reliable deployment on a specific downstream task and hardware platform still requires post-training. Dexterous hands make this adaptation particularly difficult: their broad behavioural repertoire and high degree of freedom create a large and structured action space.

## Related
<!-- [[other-paper-citekey]] -->
