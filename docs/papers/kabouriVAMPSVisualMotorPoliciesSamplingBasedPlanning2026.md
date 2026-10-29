---
citekey: "kabouriVAMPSVisualMotorPoliciesSamplingBasedPlanning2026"
title: "VAMPS: Visual and Motor Policies from Sampling-Based Planning"
authors: ["Mohamed Yassine Kabouri", "Pietro Noah Crestaz", "Quang-Nam Nguyen", "Qilong Cheng", "Ludovic Righetti", "Nicolas Mansard"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05331"
doi: "10.48550/arXiv.2610.05331"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# VAMPS: Visual and Motor Policies from Sampling-Based Planning

> Mohamed Yassine Kabouri, Pietro Noah Crestaz, Quang-Nam Nguyen, Qilong Cheng, Ludovic Righetti, Nicolas Mansard · 2026
> [arXiv](https://arxiv.org/abs/2610.05331) · [PDF](https://arxiv.org/pdf/2610.05331)

## Abstract

Learning robot policies directly on physical systems remains difficult because data collection is costly and policy exploration can be unsafe. We introduce Visual and Motor Policies from Sampling-Based Planning (VAMPS), a framework that uses Model Predictive Path Integral (MPPI) control to train reusable policies without human demonstrations. VAMPS supports two training modes. For one-step proprioceptive policies, it operates iteratively in simulation: the policy warm-starts MPPI, and the refined trajectories provide new supervision as the policy changes. A learned terminal value improves short-horizon planning, while an Implicit Q-Learning (IQL) critic guides the policy update. Iterative refinement outperforms training once on frozen MPPI data, and we transfer the learned locomotion policy to a Unitree Go2. For visuomotor policies, VAMPS operates directly from real-robot data. MPPI uses task-specific state estimates to plan and execute trajectories while recording RGB and sensor observations on a Flexiv Rizon 10S. Action Chunking with Transformers predicts action chunks, reducing the effective prediction horizon, and is trained offline on this fixed dataset. We demonstrate visuomotor pick-and-place and force-aware whiteboard erasing. In the latter task, the policy additionally observes the measured $6$-D wrench and desired normal force. These results show that VAMPS can learn policies either in simulation followed by hardware transfer or directly from autonomously collected real-robot data.

## TL;DR

Learning robot policies directly on physical systems remains difficult because data collection is costly and policy exploration can be unsafe. We introduce Visual and Motor Policies from Sampling-Based Planning (VAMPS), a framework that uses Model Predictive Path Integral (MPPI) control to train reusable policies without human demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
