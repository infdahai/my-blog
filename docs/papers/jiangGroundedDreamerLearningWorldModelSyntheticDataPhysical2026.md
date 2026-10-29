---
citekey: "jiangGroundedDreamerLearningWorldModelSyntheticDataPhysical2026"
title: "Grounded-Dreamer: Robot Learning from World Model Synthetic Data with Physical Grounding"
authors: ["Feng Jiang", "Shu Chen", "Yuanfei Wang", "Yuan Li", "Zhenhao Shen", "Jiaqi Liang", "Yang Chen", "Lei Wei", "Chen Xie", "Ruihai Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13164"
doi: "10.48550/arXiv.2610.13164"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Grounded-Dreamer: Robot Learning from World Model Synthetic Data with Physical Grounding

> Feng Jiang, Shu Chen, Yuanfei Wang, Yuan Li, Zhenhao Shen, Jiaqi Liang, Yang Chen, Lei Wei, Chen Xie, Ruihai Wu · 2026
> [arXiv](https://arxiv.org/abs/2610.13164) · [PDF](https://arxiv.org/pdf/2610.13164)

## Abstract

Scaling robot manipulation policies requires large amounts of diverse, action-labeled data, yet collecting such data in the real world remains expensive and difficult to scale. Existing methods either depend on human teleoperation, rely on simulation with limited visual realism, or use human videos that lack embodiment-specific annotations. In this paper, we introduce Grounded-Dreamer, a framework for synthesizing physically grounded robot manipulation data with video world models while avoiding human teleoperation demonstrations. Grounded-Dreamer combines the visual realism of generative video models with simulator physics engines. Starting from a small set of real images depicting robot task initial states, our method automatically reconstructs task-relevant objects and camera geometry, aligns them in simulation, and collects physically valid trajectories. These trajectories are used to post-train both a video world model and an inverse dynamics model, enabling the generation of visually realistic robot manipulation videos and corresponding robot actions from real images. To filter physically implausible rollouts, Grounded-Dreamer replays generated trajectories in the reconstructed simulation and retains only those that successfully complete the tasks. The real-world robot policies are trained solely on the grounded synthetic trajectories without any human demonstrations. Empirical results in real-world tasks demonstrate that Grounded-Dreamer can synthesize physically grounded data and substantially facilitate policy learning without requiring human teleoperation effort.

## TL;DR

Scaling robot manipulation policies requires large amounts of diverse, action-labeled data, yet collecting such data in the real world remains expensive and difficult to scale. Existing methods either depend on human teleoperation, rely on simulation with limited visual realism, or use human videos that lack embodiment-specific annotations.

## Related
<!-- [[other-paper-citekey]] -->
