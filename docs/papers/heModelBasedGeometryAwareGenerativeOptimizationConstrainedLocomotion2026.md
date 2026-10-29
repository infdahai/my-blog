---
citekey: "heModelBasedGeometryAwareGenerativeOptimizationConstrainedLocomotion2026"
title: "Model-Based Geometry-Aware Generative Optimization for Constrained Locomotion Planning"
authors: ["Zhilin He", "Xinyuan Wang", "Changliu Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07772"
doi: "10.48550/arXiv.2610.07772"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Model-Based Geometry-Aware Generative Optimization for Constrained Locomotion Planning

> Zhilin He, Xinyuan Wang, Changliu Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.07772) · [PDF](https://arxiv.org/pdf/2610.07772)

## Abstract

Constrained Locomotion Planning (CLP) for quadrupeds and humanoids, where robots must satisfy collision avoidance, contact consistency, kinematic feasibility, and support constraints, is challenging under high-dimensional dynamics and highly non-convex environments. Recent Model-Based Diffusion (MBD) approaches recast trajectory optimization as posterior sampling over trajectories, using known dynamics and Monte Carlo rollouts to analytically estimate the denoising score function without demonstration learning. While constrained variants further incorporate feasibility into model-based score rollouts and show promising performance, they are still limited by (1) lacking a task-modulated active constraint geometry that shapes the score direction and reverse stochasticity, and (2) using deterministic DDPM-style reverse transport without adaptive scheduling across different generative transports. Therefore, we introduce Model-Based Geometry-Aware Generative Optimization (2GO) for constrained locomotion, which turns active constraint geometry into executable denoising operators through normal- induced metric shaping, tangent-space stochastic filtering, and CFS-based retraction. 2GO further decouples generative transport from reverse stochasticity through an adaptive diffusion and flow-like schedule. Experiments on constrained quadruped and humanoid locomotion demonstrate strong performance in discrete foothold selection and continuous posture planning, with higher success rates, fewer violations, and improved execution compatibility.

## TL;DR

Constrained Locomotion Planning (CLP) for quadrupeds and humanoids, where robots must satisfy collision avoidance, contact consistency, kinematic feasibility, and support constraints, is challenging under high-dimensional dynamics and highly non-convex environments. Recent Model-Based Diffusion (MBD) approaches recast trajectory optimization as posterior sampling over trajectories, using known dynamics and Monte Carlo rollouts to analytically estimate the denoising score function without demonstration learning.

## Related
<!-- [[other-paper-citekey]] -->
