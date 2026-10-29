---
citekey: "liARSTAGAgenticReal2Sim2RealSystemTaskSpecificDataGeneration2026"
title: "ARSTAG: An Agentic Real2Sim2Real System for Task-Specific Robot Data Generation"
authors: ["Bowei Li", "Yuner Zhang", "Changliu Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24563"
doi: "10.48550/arXiv.2609.24563"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# ARSTAG: An Agentic Real2Sim2Real System for Task-Specific Robot Data Generation

> Bowei Li, Yuner Zhang, Changliu Liu · 2026
> [arXiv](https://arxiv.org/abs/2609.24563) · [PDF](https://arxiv.org/pdf/2609.24563)

## Abstract

Adapting visuomotor policies to new manipulation tasks often requires substantial manual engineering or teleoperated data collection. Simulation can provide task-specific data at scale, but constructing the scene, designing expert behavior, and configuring data generation still require significant per-task effort. We present ARSTAG, an agentic Real2Sim2Real system that turns a single RGB image and a natural-language instruction directly into robot policy-learning data. A hierarchy of language agents constructs a task-scoped simulation scene, generates robot-feasible demonstrations, and expands the training distribution through task-consistent randomization, while a coordinator agent manages cross-stage feedback and recovery. Across seven manipulation tasks spanning grasping, placement, and stacking, the ARSTAG-generated demonstrations enable sim-to-real transfer of three visuomotor policy architectures to a dual-arm robot, with pi0.5 achieving an average real-world success rate of 74.6%. Ablations show that task-consistent randomization substantially improves robustness, and policy performance increases with generated dataset size. Project webpage: https://boweili666.github.io/ARSTAG/.

## TL;DR

Adapting visuomotor policies to new manipulation tasks often requires substantial manual engineering or teleoperated data collection. Simulation can provide task-specific data at scale, but constructing the scene, designing expert behavior, and configuring data generation still require significant per-task effort.

## Related
<!-- [[other-paper-citekey]] -->
