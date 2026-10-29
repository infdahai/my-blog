---
citekey: "dongReinforcementLearningRealTimeVisionLanguageActionPolicies2026"
title: "Reinforcement Learning for Real-Time Vision-Language-Action Policies"
authors: ["Perry Dong", "Kuo-Han Hung", "Dorsa Sadigh", "Chelsea Finn"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18207"
doi: "10.48550/arXiv.2609.18207"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# Reinforcement Learning for Real-Time Vision-Language-Action Policies

> Perry Dong, Kuo-Han Hung, Dorsa Sadigh, Chelsea Finn · 2026
> [arXiv](https://arxiv.org/abs/2609.18207) · [PDF](https://arxiv.org/pdf/2609.18207)

## Abstract

Reinforcement learning fine-tuning on top of large, pretrained Vision-Language-Action (VLA) models offers promise for highly reliable robot deployment. However, because of their scale, modern VLA models suffer from high inference latency, so the observation used to select an action is often stale by execution time, creating a distribution shift that can substantially degrade reliability and performance. Prior work has explored asynchronous policy execution to reduce the effect of latency, but these methods are mostly built on imitation learning and offer no mechanism for moving beyond the training distribution toward higher reliability. We close this gap by enabling RL fine-tuning that meets the real-time control requirements of dynamic real-world manipulation. Our approach builds on EXPO-FT, a framework for sample-efficient, reliable VLA fine-tuning with reinforcement learning, and decouples slow, expressive action generation from fast, reactive action edits: a large pretrained VLA proposes action chunks using its strong behavior prior, while a lightweight edit policy performs fast, reactive decision-making by editing actions in response to changes in state, conditioned on the latest observation. We instantiate this as Real-Time EXPO-FT, an RL framework for finetuning real-time VLA policies. On the Kinetix benchmark, Real-Time EXPO-FT enables a delayed policy to achieve the best performance among delayed and non-delayed methods in 10 out of 10 environments. On four dynamic real-world tasks, robot object passing, ball balancing, table soccer kicking, and dynamic object picking, with online robot data capped at 10 minutes, Real-Time EXPO-FT improves average policy performance from 42% to 97%, all without human intervention, demonstrating rapid, sample-efficient adaptation to challenging real-world dynamics. Website: https://pd-perry.github.io/real-time-expo-ft

## TL;DR

Reinforcement learning fine-tuning on top of large, pretrained Vision-Language-Action (VLA) models offers promise for highly reliable robot deployment. However, because of their scale, modern VLA models suffer from high inference latency, so the observation used to select an action is often stale by execution time, creating a distribution shift that can substantially degrade reliability and performance.

## Related
<!-- [[other-paper-citekey]] -->
