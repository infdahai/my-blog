---
citekey: "yongTrajectoryPlanningWithoutTrajectoryDataManifoldGuidedApproach2026"
title: "Trajectory Planning without Trajectory Data: A Manifold-Guided Approach"
authors: ["Silong Yong", "Anji Liu", "Cunxi Dai", "Carl Busart", "Guanya Shi", "Yilun Du", "Katia Sycara", "Yaqi Xie"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.08863"
doi: "10.48550/arXiv.2610.08863"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Trajectory Planning without Trajectory Data: A Manifold-Guided Approach

> Silong Yong, Anji Liu, Cunxi Dai, Carl Busart, Guanya Shi, Yilun Du, Katia Sycara, Yaqi Xie · 2026
> [arXiv](https://arxiv.org/abs/2610.08863) · [PDF](https://arxiv.org/pdf/2610.08863)

## Abstract

A common way for trajectory planning is to leverage generative models trained on large collections of expert trajectories. At inference time, the model generates executable trajectories by conditioning on task goal constraints. However, trajectory-based methods rely on costly supervision, scale poorly with sequence length, and often generalize poorly to unseen constraints such as novel start-goal pairs. We propose an alternative to learn the underlying state-space manifold and use the geometry of the manifold for trajectory planning. This approach requires only state observations and enables generalization to unseen constraints by con- structing trajectories on the learned manifold of the state space. Experiments on Maze2D and robotic motion-planning benchmarks show that Ariadne constructs feasible paths from state-only supervision and generalizes to unseen start-goal combinations. On high-dimensional dual-arm planning, it remains competitive with trajectory-supervised and classical planners, while requiring no trajectory data for training.

## TL;DR

A common way for trajectory planning is to leverage generative models trained on large collections of expert trajectories. At inference time, the model generates executable trajectories by conditioning on task goal constraints.

## Related
<!-- [[other-paper-citekey]] -->
