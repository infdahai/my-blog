---
citekey: "kapelyukhZeroBotLearningScratchMinutesGenerativeReal2Sim2026"
title: "ZeroBot: Learning from Scratch in Minutes with Generative Real2Sim"
authors: ["Ivan Kapelyukh", "Xiaohan Zhang", "Stephen James", "Laura Herlant", "Edward Johns"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34010"
doi: "10.48550/arXiv.2609.34010"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# ZeroBot: Learning from Scratch in Minutes with Generative Real2Sim

> Ivan Kapelyukh, Xiaohan Zhang, Stephen James, Laura Herlant, Edward Johns · 2026
> [arXiv](https://arxiv.org/abs/2609.34010) · [PDF](https://arxiv.org/pdf/2609.34010)

## Abstract

We present ZeroBot, a real2sim framework for learning a robot manipulation task from scratch in minutes under challenging conditions: zero human demonstrations, zero policy pre-training, and zero known object models. Given only a single view of an object and a goal pose for that object, ZeroBot uses image-to-3D generative models to obtain a complete object mesh, which is used in simulation for large-scale parallel reinforcement learning. To accelerate training, we introduce an action space which leverages the generated geometry and learned value function to sample states involving robot-object contact. When evaluated on real-world tasks including grasping, pushing, articulated object interaction, and multi-stage manipulation, ZeroBot achieves an 87% success rate with an average training time of 119 seconds. These results show the value of using image-to-3D models in a real2sim framework for rapid, autonomous robot learning.

## TL;DR

We present ZeroBot, a real2sim framework for learning a robot manipulation task from scratch in minutes under challenging conditions: zero human demonstrations, zero policy pre-training, and zero known object models. Given only a single view of an object and a goal pose for that object, ZeroBot uses image-to-3D generative models to obtain a complete object mesh, which is used in simulation for large-scale parallel reinforcement learning.

## Related
<!-- [[other-paper-citekey]] -->
