---
citekey: "manniLearningMultiPhaseLocoManipulationPhaseConditionedPolicy2026"
title: "Learning Multi-Phase Robot Loco-Manipulation via Phase-Conditioned Policy Optimization"
authors: ["Simone Manni", "Annika Wollschl\\\"ager", "Dario Bellicoso", "Abel Gawel", "Marco Hutter", "Simon Le Cleac'h", "Jan Br\\\"udigam"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36270"
doi: "10.48550/arXiv.2610.36270"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# Learning Multi-Phase Robot Loco-Manipulation via Phase-Conditioned Policy Optimization

> Simone Manni, Annika Wollschl\"ager, Dario Bellicoso, Abel Gawel, Marco Hutter, Simon Le Cleac'h, Jan Br\"udigam · 2026
> [arXiv](https://arxiv.org/abs/2610.36270) · [PDF](https://arxiv.org/pdf/2610.36270)

## Abstract

Complex whole-body loco-manipulation requires executing diverse maneuvers, such as crouching, grasping, and locomotion, within a single long-horizon task. While performing simple pick-and-place behaviors is well-established, scaling to complex, long-horizon tasks remains difficult. Currently, this challenge is addressed by relying on human motion data and correspondingly humanoid platforms, which limits platform independence and introduces substantial data processing overhead. Instead, we extend proximal policy optimization (PPO) to train a single policy for multi-phase tasks across diverse robotic hardware, leveraging prior task structure to shape behavior. Our method adapts PPO using a phase-conditioned critic, phase-gated reward functions, and a multi-phase reset curriculum to guide exploration. To support varied hardware, we employ a decoupled hierarchical control architecture that separates lower-level balancing dynamics from high-level phase execution. We demonstrate multi-stage loco-manipulation skills on hardware on both the Unitree G1 and a Boston Dynamics Spot equipped with a manipulator arm, and validate our design choices through ablations. Our approach enables the acquisition of complex loco-manipulation behaviors purely through environment interaction while directly incorporating high-level task structure into policy learning.

## TL;DR

Complex whole-body loco-manipulation requires executing diverse maneuvers, such as crouching, grasping, and locomotion, within a single long-horizon task. While performing simple pick-and-place behaviors is well-established, scaling to complex, long-horizon tasks remains difficult.

## Related
<!-- [[other-paper-citekey]] -->
