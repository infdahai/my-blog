---
citekey: "danPRISMProjectionIntegratedSamplingBasedMPCBayesianCost2026"
title: "PRISM: Projection-Integrated Sampling-Based MPC with Bayesian Cost Tuning for Bimanual Manipulation"
authors: ["Alinjar Dan", "Iryna Hurova", "Karl Kruusamäe", "Arun Kumar Singh"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25666"
doi: "10.48550/arXiv.2608.25666"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# PRISM: Projection-Integrated Sampling-Based MPC with Bayesian Cost Tuning for Bimanual Manipulation

> Alinjar Dan, Iryna Hurova, Karl Kruusamäe, Arun Kumar Singh · 2026
> [arXiv](https://arxiv.org/abs/2608.25666) · [PDF](https://arxiv.org/pdf/2608.25666)

## Abstract

Bimanual manipulation in cluttered, contact-rich environments remains challenging because it requires coordinated motion generation, interaction-aware planning, and reliable execution under tight kinematic constraints. We present PRISM, a projection-integrated sampling-based Model Predictive Control (MPC) framework that uses a GPU-accelerated physics simulator as an online world model for complex dual-arm manipulation. The main algorithmic contribution is a QP-guided control sampling strategy that decouples trajectory exploration from kinematic feasibility. At each MPC step, sampled joint-velocity trajectories are projected onto the set of motions satisfying joint position, velocity, acceleration, and jerk bounds, together with an initial-velocity boundary condition, before rollout evaluation. This enables broad yet feasible exploration of coordinated bimanual behaviors. To support efficient online execution, we derive a custom ADMM/Bregman-splitting QP solver that exploits joint-wise separability and reusable matrix factorizations. We further use Bayesian optimization to tune task-cost weights offline, reducing manual parameter selection. We evaluate PRISM on challenging variants of PerAct$^{2}$ tasks, including obstacle-constrained ball transport, tray transport, cube handover, and box lifting. Experiments show improved robustness and task success relative to representative sampling-based baselines, while maintaining real-time or near-real-time execution. We also demonstrate successful sim-to-real transfer on dual UR5e manipulators, highlighting the practical potential of physics-based online planning for contact-rich bimanual manipulation. Project details, including code and supplementary videos, are available at \href{https://sites.google.com/view/prismbimanual}{\texttt{https://sites.google.com/view/prismbimanual}}.

## TL;DR

Bimanual manipulation in cluttered, contact-rich environments remains challenging because it requires coordinated motion generation, interaction-aware planning, and reliable execution under tight kinematic constraints. We present PRISM, a projection-integrated sampling-based Model Predictive Control (MPC) framework that uses a GPU-accelerated physics simulator as an online world model for complex dual-arm manipulation.

## Related
<!-- [[other-paper-citekey]] -->
