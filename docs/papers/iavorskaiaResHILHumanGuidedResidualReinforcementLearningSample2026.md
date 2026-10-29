---
citekey: "iavorskaiaResHILHumanGuidedResidualReinforcementLearningSample2026"
title: "Res-HIL: Human-Guided Residual Reinforcement Learning for Sample-Efficient Dexterous Manipulation"
authors: ["Mariia Iavorskaia", "Christian Dietz", "Sebastian Albrecht", "Majid Khadiv"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.30023"
doi: "10.48550/arXiv.2609.30023"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-26
---

# Res-HIL: Human-Guided Residual Reinforcement Learning for Sample-Efficient Dexterous Manipulation

> Mariia Iavorskaia, Christian Dietz, Sebastian Albrecht, Majid Khadiv · 2026
> [arXiv](https://arxiv.org/abs/2609.30023) · [PDF](https://arxiv.org/pdf/2609.30023)

## Abstract

Imitation learning enables robots to acquire manipulation skills from demonstrations, but the resulting policies can fail outside the training data, while collecting more demonstrations requires substantial human effort. Human-in-the-loop reinforcement learning uses corrective feedback during online training, but typically learns the complete task policy rather than refining a pretrained imitation policy. We introduce Res-HIL, a human-in-the-loop residual reinforcement learning framework that learns corrective actions on top of a frozen imitation policy. Each human intervention provides two complementary learning signals: direct supervision of the residual policy and reward shaping of preceding autonomous behavior. Res-HIL combines these signals with zero initialization of the residual policy to stabilize and accelerate online learning. We evaluate Res-HIL on five contact-rich manipulation tasks spanning high-precision and long-horizon behaviors. With only 20 initial demonstrations, Res-HIL outperforms state-of-the-art full-policy human-in-the-loop reinforcement learning and residual fine-tuning without human guidance on every task after ten minutes of online training. Res-HIL improves its pretrained base policies and outperforms imitation policies trained with five times more demonstrations. An ablation study shows that direct residual supervision is critical to performance, while intervention-aware reward shaping substantially improves training efficiency.

## TL;DR

Imitation learning enables robots to acquire manipulation skills from demonstrations, but the resulting policies can fail outside the training data, while collecting more demonstrations requires substantial human effort. Human-in-the-loop reinforcement learning uses corrective feedback during online training, but typically learns the complete task policy rather than refining a pretrained imitation policy.

## Related
<!-- [[other-paper-citekey]] -->
