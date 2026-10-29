---
citekey: "kktabakRealWorldReinforcementLearningMPCScaffoldingDexterousManipulation2026"
title: "Real-World Reinforcement Learning with MPC Scaffolding for Dexterous Manipulation"
authors: ["Emek Barış Küçüktabak", "Karankumar Patel", "Zhaodong Yang", "Jinda Cui", "Kazuhiro Sasabuchi", "Jun Takamatsu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.14878"
doi: "10.48550/arXiv.2609.14878"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Real-World Reinforcement Learning with MPC Scaffolding for Dexterous Manipulation

> Emek Barış Küçüktabak, Karankumar Patel, Zhaodong Yang, Jinda Cui, Kazuhiro Sasabuchi, Jun Takamatsu · 2026
> [arXiv](https://arxiv.org/abs/2609.14878) · [PDF](https://arxiv.org/pdf/2609.14878)

## Abstract

Real-world reinforcement learning (RL) offers a promising route to dexterous manipulation policies that can adapt directly from physical interaction, but learning is hindered by inefficient early exploration and costly failures. We propose a framework that uses sampling-based model predictive control (MPC) as scaffolding for real-world dexterous RL, providing structured prior experience and task-directed guidance during learning without human demonstrations or corrective actions. A small set of MPC trajectories is first used to populate an offline replay buffer and to pretrain the actor and critic. During online learning, MPC intermittently guides data collection while an off-policy Soft Actor-Critic learner trains from both prior MPC experience and newly collected physical interaction, with control gradually transitioning to the learned policy. On continuous in-hand rotation with a 16-DoF Allegro hand, the method reaches 100\% success in policy-only evaluation (5/5 trials) after 7 minutes of online RL, following initialization with 20 MPC trajectories collected on hardware in 12 minutes. Online training incurs about three object drops on average. After 20 minutes of online learning, the policy achieves more than five times the rotation speed of the MPC controller. It completes 1000 consecutive rotations over more than 110 minutes without a drop. Ablations show complementary benefits from MPC-based pretraining, retained MPC experience, and online MPC guidance. We further demonstrate rapid adaptation to different object geometries and successful goal-conditioned reorientation, showing that the framework enables efficient, low-intervention, real-world dexterous RL.

## TL;DR

Real-world reinforcement learning (RL) offers a promising route to dexterous manipulation policies that can adapt directly from physical interaction, but learning is hindered by inefficient early exploration and costly failures. We propose a framework that uses sampling-based model predictive control (MPC) as scaffolding for real-world dexterous RL, providing structured prior experience and task-directed guidance during learning without human demonstrations or corrective actions.

## Related
<!-- [[other-paper-citekey]] -->
