---
citekey: "fengDUGMRUncertaintyAwareDynamicGridMappingRisk2026"
title: "DUGM-R: Uncertainty-Aware Dynamic Grid Mapping and Risk-Triggered Recovery for Learned Local Navigation"
authors: ["Haoyun Feng", "Adrian Rubio-Solis", "Zhaodong Guo", "George Mylonas"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27338"
doi: "10.48550/arXiv.2609.27338"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# DUGM-R: Uncertainty-Aware Dynamic Grid Mapping and Risk-Triggered Recovery for Learned Local Navigation

> Haoyun Feng, Adrian Rubio-Solis, Zhaodong Guo, George Mylonas · 2026
> [arXiv](https://arxiv.org/abs/2609.27338) · [PDF](https://arxiv.org/pdf/2609.27338)

## Abstract

Learned local navigation in crowded indoor environments is sensitive to how dynamic obstacle motion is represented, while collision-prone behaviour may persist after nominal policy training. We present a risk-aware reinforcement-learning framework that addresses these two issues through an uncertainty-aware Dynamic Uncertainty Grid Map (DUGM) and a modular post-training recovery mechanism. DUGM combines local occupancy, estimated obstacle motion, and motion-estimation uncertainty in a robot-centric representation. After the nominal policy is frozen, a finite-horizon Risk Value Function (RVF) is trained from nominal rollouts and used to trigger a dedicated recovery policy when continued nominal execution is predicted to be collision-prone. Experiments in a held-out NVIDIA Isaac Sim clinical-logistics benchmark show that uncertainty-aware dynamic representation improves nominal navigation over static and deterministic alternatives, while the recovery mechanism further mitigates residual collision-prone behaviour. The complete framework is also deployed directly on a TurtleBot3 without policy fine-tuning, retraining, or site-specific adaptation, retaining the performance trend observed in simulation. These results indicate that uncertainty-aware dynamic representation and post-training recovery provide complementary mechanisms for improving learned local navigation.

## TL;DR

Learned local navigation in crowded indoor environments is sensitive to how dynamic obstacle motion is represented, while collision-prone behaviour may persist after nominal policy training. We present a risk-aware reinforcement-learning framework that addresses these two issues through an uncertainty-aware Dynamic Uncertainty Grid Map (DUGM) and a modular post-training recovery mechanism.

## Related
<!-- [[other-paper-citekey]] -->
