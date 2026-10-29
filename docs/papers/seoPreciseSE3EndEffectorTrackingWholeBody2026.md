---
citekey: "seoPreciseSE3EndEffectorTrackingWholeBody2026"
title: "Precise SE(3) End-Effector Tracking in Whole-Body Humanoid Control"
authors: ["Joohwan Seo", "Xiaofeng Guo", "Jinkun Cao", "Roberto Horowitz", "Rocky Duan", "Guanya Shi", "Koushil Sreenath"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09479"
doi: "10.48550/arXiv.2610.09479"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-09
---

# Precise SE(3) End-Effector Tracking in Whole-Body Humanoid Control

> Joohwan Seo, Xiaofeng Guo, Jinkun Cao, Roberto Horowitz, Rocky Duan, Guanya Shi, Koushil Sreenath · 2026
> [arXiv](https://arxiv.org/abs/2610.09479) · [PDF](https://arxiv.org/pdf/2610.09479)

## Abstract

Precise end-effector tracking during humanoid whole-body motion is challenging due to floating-base oscillations, gravity, dynamic coupling, and locomotion-induced disturbances. We propose ResGAC, a whole-body humanoid controller for precise end-effector pose tracking that combines geometric admittance control (GAC) with residual reinforcement learning. GAC provides structured $\SE$ task-space feedback and generates nominal arm joint-position targets, while residual RL compensates for unmodeled dynamics and coordinates locomotion and balance in the shared joint-position action space. The left-invariant geometric formulation allows the same GAC law to be used across manipulation reference frames. This enables the use of a ground-attached heading frame that preserves planar locomotion while removing pelvis roll, pitch, and heave from the manipulation reference, thereby reducing reference-induced end-effector motion during locomotion. ResGAC is validated on a real Unitree G1 humanoid. Across four standing end-effector tracking benchmarks, ResGAC consistently outperforms representative baselines, including SONIC, achieving lower translational and rotational errors. Real-world experiments further demonstrate reduced propagation of pelvis motion to the desired end-effector pose using the proposed ground-attached heading frame. ResGAC achieves $90\%$ success in a standing peg-in-hole task compared with $50\%$ for SONIC, and accurate world-frame $\SE$ end-effector pose tracking during lower-body motion. Experimental videos are included in the supplementary material and are also available on the project website: https://resgac.github.io/ResGAC-website/.

## TL;DR

Precise end-effector tracking during humanoid whole-body motion is challenging due to floating-base oscillations, gravity, dynamic coupling, and locomotion-induced disturbances. We propose ResGAC, a whole-body humanoid controller for precise end-effector pose tracking that combines geometric admittance control (GAC) with residual reinforcement learning.

## Related
<!-- [[other-paper-citekey]] -->
