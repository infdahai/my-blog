---
citekey: "liuRACERResidualAdaptiveClosedLoopEstimationSamplingBased2026"
title: "RACER: Residual-Adaptive Closed-Loop Estimation for Sampling-Based Planning in Wheeled-Quadruped Racing"
authors: ["Yuxiang Liu", "Marla Eisman", "Lizhi Yang", "Aaron Ames", "Francesco Borrelli"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07409"
doi: "10.48550/arXiv.2610.07409"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# RACER: Residual-Adaptive Closed-Loop Estimation for Sampling-Based Planning in Wheeled-Quadruped Racing

> Yuxiang Liu, Marla Eisman, Lizhi Yang, Aaron Ames, Francesco Borrelli · 2026
> [arXiv](https://arxiv.org/abs/2610.07409) · [PDF](https://arxiv.org/pdf/2610.07409)

## Abstract

We present RACER, a hierarchical control framework for wheel-based quadruped racing that combines an MPPI planner with a learned residual dynamics model and a low-level RL velocity tracker. The planner augments a nominal unicycle kinematic model with a neural residual term to capture the closed-loop tracking behavior of the RL policy. To train this residual model under limited real-world data, we propose Low-Rank Residual Adaptation (LoRRA), a two-stage approach that pre-trains on large-scale simulation data for broad coverage and then fine-tunes on a small real-world dataset with a low-rank constraint. In simulation, we empirically validate our engineering choices by showing (A) Residual dynamics improve the overall performance of our pipeline by capturing the tracking error of RL velocity tracker at high-speed cornering. (B) Residual dynamics trained with both source-domain and target-domain data gives racing performance significantly better than the residual dynamics trained with only target-domain data. (C) Low-rank constraint at target-domain adaptation gives higher success rates and higher performance than full-tune and from-scratch when domain gap in ground coefficient or joint gain increases.

## TL;DR

We present RACER, a hierarchical control framework for wheel-based quadruped racing that combines an MPPI planner with a learned residual dynamics model and a low-level RL velocity tracker. The planner augments a nominal unicycle kinematic model with a neural residual term to capture the closed-loop tracking behavior of the RL policy.

## Related
<!-- [[other-paper-citekey]] -->
