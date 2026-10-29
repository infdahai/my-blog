---
citekey: "liManyWaysSucceedDiversityDrivenRLFineTuning2026"
title: "Many Ways to Succeed: Diversity-Driven RL Fine-Tuning for VLA Generalization"
authors: ["Haoru Li", "Jinmei Liu", "Zhiyong Wang", "Xiaoming Li", "Zhenhong Sun", "Daoyi Dong", "Chunlin Chen", "Zhi Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09943"
doi: "10.48550/arXiv.2610.09943"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Many Ways to Succeed: Diversity-Driven RL Fine-Tuning for VLA Generalization

> Haoru Li, Jinmei Liu, Zhiyong Wang, Xiaoming Li, Zhenhong Sun, Daoyi Dong, Chunlin Chen, Zhi Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.09943) · [PDF](https://arxiv.org/pdf/2610.09943)

## Abstract

Reinforcement learning (RL) fine-tuning improves vision-language-action (VLA) policies through closed-loop experience, yet generalization beyond the fine-tuning distribution remains limited. Our analysis reveals a selective reshaping of exploration: RL contracts behavior globally, yet diversifies successful trajectories, elicits success with fewer rollouts, and covers more of the latent task-valid solution space than supervised fine-tuning. Broader successful-mode coverage may provide alternative strategies under distribution shifts. Inspired by this, we introduce DRIVE (Diversity-driven RL fIne-tuning for VLA gEneralization), which turns successful-behavior diversity into an explicit RL objective. DRIVE groups rollouts under matched task conditions, compares their trajectories with temporal alignment, and derives a success-conditioned intrinsic reward from relative behavioral diversity. This design encourages broader coverage of feasible solutions without rewarding diverse failures or superficial timing differences. Across LIBERO-Plus, ManiSkill3, and RoboTwin 2.0, DRIVE improves the average out-of-domain (OOD) performance over vanilla RL fine-tuning by 5.3 points on $π_0$ and 2.0 points on $π_{0.5}$. On a dual-arm AgileX PiPER-X platform, DRIVE further increases average OOD success from 64.1% to 73.3% (+9.2 points), demonstrating gains that persist under physical deployment.

## TL;DR

Reinforcement learning (RL) fine-tuning improves vision-language-action (VLA) policies through closed-loop experience, yet generalization beyond the fine-tuning distribution remains limited. Our analysis reveals a selective reshaping of exploration: RL contracts behavior globally, yet diversifies successful trajectories, elicits success with fewer rollouts, and covers more of the latent task-valid solution space than supervised fine-tuning.

## Related
<!-- [[other-paper-citekey]] -->
