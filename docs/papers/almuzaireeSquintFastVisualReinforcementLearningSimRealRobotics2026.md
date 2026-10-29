---
citekey: "almuzaireeSquintFastVisualReinforcementLearningSimRealRobotics2026"
title: "Squint: Fast Visual Reinforcement Learning for Sim-to-Real Robotics"
authors: ["Abdulaziz Almuzairee", "Henrik I. Christensen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2602.21203"
doi: "10.48550/arXiv.2602.21203"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# Squint: Fast Visual Reinforcement Learning for Sim-to-Real Robotics

> Abdulaziz Almuzairee, Henrik I. Christensen · 2026
> [arXiv](https://arxiv.org/abs/2602.21203) · [PDF](https://arxiv.org/pdf/2602.21203)

## Abstract

Visual reinforcement learning is appealing for robotics but expensive. Off-policy methods are sample-efficient yet slow while on-policy methods parallelize well but waste samples. Recent work has shown that off-policy methods can train faster than on-policy methods in wall-clock time for state-based control. Extending this to vision remains challenging, where high-dimensional input images complicate training dynamics and introduce substantial storage and encoding overhead. To address these challenges, we introduce Squint, a visual Soft Actor Critic method that achieves faster wall-clock training than prior visual off-policy and on-policy methods. Squint achieves this via parallel simulation, a distributional critic, resolution squinting, layer normalization, a tuned update-to-data ratio, and an optimized implementation. We evaluate on the SO-101 Task Set, a new suite of eight manipulation tasks in ManiSkill3 with heavy domain randomization, and demonstrate sim-to-real transfer to a real SO-101 robot. We train policies for 15 minutes on a single RTX 3090 GPU, with most tasks converging in under 6 minutes.

## TL;DR

Visual reinforcement learning is appealing for robotics but expensive. Off-policy methods are sample-efficient yet slow while on-policy methods parallelize well but waste samples.

## Related
<!-- [[other-paper-citekey]] -->
