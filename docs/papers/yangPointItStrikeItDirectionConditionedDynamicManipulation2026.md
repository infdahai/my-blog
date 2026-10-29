---
citekey: "yangPointItStrikeItDirectionConditionedDynamicManipulation2026"
title: "Point It, Strike It: Direction-Conditioned Dynamic Manipulation of Deformable Linear Objects"
authors: ["Yi Yang", "Xiang Fei", "Lehong Wang", "Zilin Dai", "Ruogu Li", "Jiting Cai", "Liyao Chang", "Xinyi Yang", "Henry Kou", "Ruijie Fu", "Lu Li", "Howie Choset"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09573"
doi: "10.48550/arXiv.2610.09573"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Point It, Strike It: Direction-Conditioned Dynamic Manipulation of Deformable Linear Objects

> Yi Yang, Xiang Fei, Lehong Wang, Zilin Dai, Ruogu Li, Jiting Cai, Liyao Chang, Xinyi Yang, Henry Kou, Ruijie Fu, Lu Li, Howie Choset · 2026
> [arXiv](https://arxiv.org/abs/2610.09573) · [PDF](https://arxiv.org/pdf/2610.09573)

## Abstract

Goal-conditioned dynamic manipulation of deformable linear objects has mainly specified goals as positions for a rope tip to reach. Many tasks, however, depend on how the tip arrives. We therefore study single-swing rope striking with goals that specify the tip's 3D position and arrival direction, across the workspace and on different ropes. This is challenging because rope dynamics are hard to model, no demonstrations exist, distinct swings reach the same goal with different reliability, and the sim-to-real gap extends beyond the rope. To address these challenges, we extend the state-of-the-art DLO simulator DeformX with GPU acceleration, a stable Cosserat rod solver, and a cross-flow aerodynamic model, yielding DeformX2.0, which is more than $20{,}000\times$ faster. We then propose TRACE (Trace-rooted Adaptive Cross-Entropy), which generates striking data by warm-starting each new target from the stored swing whose tip path passes closest to it. Its cost penalizes rope bending and abrupt tip motion to favor repeatable swings. A conditional flow-matching policy trained on this data reaches 92.1% accuracy in simulation. Finally, we propose RECAP (Residual Calibration Policy), which fits the simulator's rope and rig parameters to a few calibration swings and adapts actions with a correction policy trained in simulation. On a real robot, across three ropes, RECAP raises success within 5cm from 72% to 87% for position goals, and within 10cm and 10° from 50% to 79% for goals that also specify the arrival direction.

## TL;DR

Goal-conditioned dynamic manipulation of deformable linear objects has mainly specified goals as positions for a rope tip to reach. Many tasks, however, depend on how the tip arrives.

## Related
<!-- [[other-paper-citekey]] -->
