---
citekey: "yinHowLearnWhatHumanWouldAvoidInterventionAware2026"
title: "How to Learn from What a Human Would Avoid? Intervention-Aware World Models with Real-World RL for Dexterous Manipulation"
authors: ["Jiaju Yin", "Zhenhui Zhang", "Lixin Xu", "Heng Zhang", "Jun Shao", "Yating Feng", "Arash Ajoudani", "Renjing Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.06009"
doi: "10.48550/arXiv.2609.06009"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# How to Learn from What a Human Would Avoid? Intervention-Aware World Models with Real-World RL for Dexterous Manipulation

> Jiaju Yin, Zhenhui Zhang, Lixin Xu, Heng Zhang, Jun Shao, Yating Feng, Arash Ajoudani, Renjing Xu · 2026
> [arXiv](https://arxiv.org/abs/2609.06009) · [PDF](https://arxiv.org/pdf/2609.06009)

## Abstract

Multi-fingered dexterous manipulation remains a frontier for real-world reinforcement learning (RL) due to the high-dimensional action space and the prohibitive cost of hardware failures. While human-in-the-loop (HIL) RL allows operators to intervene before failures occur, current pipelines often treat these interventions as reactive corrections, discarding the rich safety signal inherent in the operator's decision to take control. In this paper, we ask: How can we learn from what a human would avoid? We present WHIRL, a safety-aware RL framework that transforms binary human interventions into forward-predictive signals for proactive risk avoidance. Our approach centers on an intervention-aware latent world model with four prediction heads: dynamics, reward, termination, and a novel per-state intervention-probability head that learns to predict the likelihood of a human takeover at future states. This head provides an actor-side risk-shaping term that discourages the policy from entering "intervention-prone" regions, modeling the operator's internal safety threshold. We evaluate our framework on a 16-DoF LEAP Hand across tasks spanning convex and irregular object grasping, prismatic manipulation, and long-horizon multi-stage tasks. Our results show that predictive risk-shaping enables the system to achieve a 96.7 percent success rate on complex grasping tasks while reducing the operator intervention burden by up to 84 percent in step-weighted terms. By closing the loop between human intuition and predictive world modeling, this work provides a practical safety-aware recipe for training complex dexterous agents in the real world while reducing operator fatigue and hardware-risk exposure.

## TL;DR

Multi-fingered dexterous manipulation remains a frontier for real-world reinforcement learning (RL) due to the high-dimensional action space and the prohibitive cost of hardware failures. While human-in-the-loop (HIL) RL allows operators to intervene before failures occur, current pipelines often treat these interventions as reactive corrections, discarding the rich safety signal inherent in the operator's decision to take control.

## Related
<!-- [[other-paper-citekey]] -->
