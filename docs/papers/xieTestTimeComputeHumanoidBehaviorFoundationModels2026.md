---
citekey: "xieTestTimeComputeHumanoidBehaviorFoundationModels2026"
title: "Test-Time Compute for Humanoid Behavior Foundation Models"
authors: ["Weiji Xie", "Junsong Wu", "Zibo Zhou", "Yueru Chen", "Xingyi Wang", "Zhenhua Xiong", "Weinan Zhang", "Chenjia Bai"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14896"
doi: "10.48550/arXiv.2610.14896"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Test-Time Compute for Humanoid Behavior Foundation Models

> Weiji Xie, Junsong Wu, Zibo Zhou, Yueru Chen, Xingyi Wang, Zhenhua Xiong, Weinan Zhang, Chenjia Bai · 2026
> [arXiv](https://arxiv.org/abs/2610.14896) · [PDF](https://arxiv.org/pdf/2610.14896)

## Abstract

Humanoid Behavior Foundation Models (BFMs) can execute impressive motions, but downstream applications such as loco-manipulation demand high whole-body positional accuracy. Existing BFMs suffer from a systematic command-execution gap, where executed motions deviate from desired ones. We show that additional test-time compute can improve execution without retraining the BFM. First, we introduce Test-Time Command Optimization (TTCO), which adapts the input command to the specific BFM to produce an executed trajectory closer to the desired motion. TTCO finds such commands by sampling-based optimization through closed-loop simulations of the BFM and robot dynamics. Across three BFMs on the AMASS dataset, TTCO reduces mean global body-position error by 79-84% in simulation. Second, we analyze test-time compute scaling and derive an approximate compute-optimal strategy that can sustain performance gains as the compute budget increases. Third, TTCO can generate BFM-specific action labels from recorded robot trajectories without requiring the original teleoperation body-motion commands. Simulation and real-robot experiments show that these labels are effective for training high-level loco-manipulation policies. This method also supports reusing existing demonstrations across BFMs.

## TL;DR

Humanoid Behavior Foundation Models (BFMs) can execute impressive motions, but downstream applications such as loco-manipulation demand high whole-body positional accuracy. Existing BFMs suffer from a systematic command-execution gap, where executed motions deviate from desired ones.

## Related
<!-- [[other-paper-citekey]] -->
