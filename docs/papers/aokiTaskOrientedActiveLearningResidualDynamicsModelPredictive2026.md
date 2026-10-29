---
citekey: "aokiTaskOrientedActiveLearningResidualDynamicsModelPredictive2026"
title: "Task-Oriented Active Learning of Residual Dynamics for Model Predictive Path Integral Control"
authors: ["Nobuaki Aoki", "Hojin Lee", "Stefan Sosnowski", "Sandra Hirche"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.19378"
doi: "10.48550/arXiv.2609.19378"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-18
---

# Task-Oriented Active Learning of Residual Dynamics for Model Predictive Path Integral Control

> Nobuaki Aoki, Hojin Lee, Stefan Sosnowski, Sandra Hirche · 2026
> [arXiv](https://arxiv.org/abs/2609.19378) · [PDF](https://arxiv.org/pdf/2609.19378)

## Abstract

Online residual learning can reduce model mismatch in predictive control, but passive data collection may fail to adequately cover states that become important later in the task. Task-agnostic active learning targets uncertain or informative regions, but information acquired in such regions does not necessarily improve task performance. This paper introduces Task-Oriented Information Acquisition (ToIA), an active-learning criterion for model predictive path integral control (MPPI) with online Gaussian process (GP) residual learning. For each sampled control sequence, ToIA estimates how much an observation obtained early in the rollout would reduce predictive uncertainty at later states on the same rollout, and weights this reduction by the rollout's relevance to the task. The score is evaluated over the existing MPPI rollout batch without sampling future observations or re-optimizing control under hypothetical posterior updates. In simulated off-road navigation across held-out maps with heterogeneous terrain, ToIA improved the goal-reaching success rate over passive GP learning by 19.3 and 27.4 percentage points and outperformed task-agnostic active-learning baselines across dense and sparse online-learning intervals. An ablation study indicates that task relevance is particularly important under sparse model updates. The implementation supports online control at 20 Hz on an NVIDIA RTX 2080 Ti.

## TL;DR

Online residual learning can reduce model mismatch in predictive control, but passive data collection may fail to adequately cover states that become important later in the task. Task-agnostic active learning targets uncertain or informative regions, but information acquired in such regions does not necessarily improve task performance.

## Related
<!-- [[other-paper-citekey]] -->
