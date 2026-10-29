---
citekey: "hielscherRoboMMTLearningStableTrackingModulatedExpressiveInteractiveMotion2026"
title: "RoboMMT: Learning Stable Tracking of Modulated Expressive and Interactive Robot Motion"
authors: ["Till Hielscher", "Kai O. Arras"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.26414"
doi: "10.48550/arXiv.2610.26414"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# RoboMMT: Learning Stable Tracking of Modulated Expressive and Interactive Robot Motion

> Till Hielscher, Kai O. Arras · 2026
> [arXiv](https://arxiv.org/abs/2610.26414) · [PDF](https://arxiv.org/pdf/2610.26414)

## Abstract

Expressive robot motion can improve naturalness, effectiveness, and perceived likability in human-robot interaction. When deployed on dynamically unstable platforms, however, reactive execution of expressive body motion may bring the robot to its stability limits, especially when expressivity is decoupled from physical control. In this paper, we present RoboMMT (Robot Modulated Motion Tracking), a modular control architecture that couples parameterized expressive motion synthesis, physics-based character control, and reactive adaptation to spatial interaction goals. Our approach trains a reference-conditioned tracking policy across a broad domain of expressivity, enabling it to faithfully realize the commanded motions while maintaining dynamic stability. Goal reactivity is achieved by training lightweight, task-specific interaction policies that modulate the reference generator's spatial goal-attraction point, with the stabilizing tracking policy kept in the loop. Evaluations on a quadruped and two humanoid robots show that the learned tracker remains stable and accurate across the entire modulation domain, whereas trackers trained without this coverage lose balance, tracking accuracy, or both. We show that layering closed-loop goal adaptation over this foundation enables interactive facing and pointing behaviors, while maintaining stable execution and comparable reference-tracking fidelity. The robot learns to proactively redistribute its weight and take corrective steps. Zero-shot sim-to-real transfer is demonstrated through real-robot experiments on a quadruped under heavy disturbances.

## TL;DR

Expressive robot motion can improve naturalness, effectiveness, and perceived likability in human-robot interaction. When deployed on dynamically unstable platforms, however, reactive execution of expressive body motion may bring the robot to its stability limits, especially when expressivity is decoupled from physical control.

## Related
<!-- [[other-paper-citekey]] -->
