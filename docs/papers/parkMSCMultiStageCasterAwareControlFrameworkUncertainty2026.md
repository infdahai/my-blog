---
citekey: "parkMSCMultiStageCasterAwareControlFrameworkUncertainty2026"
title: "MSC: Multi-Stage Caster-aware Control Framework with Uncertainty-Aware NMPC and RL-based Execution Layer"
authors: ["Jinho Park", "Jeongtae Lee", "Jeonghyeok Lim", "Keun Ha Choi", "Kyung-Soo Kim"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.16199"
doi: "10.48550/arXiv.2610.16199"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# MSC: Multi-Stage Caster-aware Control Framework with Uncertainty-Aware NMPC and RL-based Execution Layer

> Jinho Park, Jeongtae Lee, Jeonghyeok Lim, Keun Ha Choi, Kyung-Soo Kim · 2026
> [arXiv](https://arxiv.org/abs/2610.16199) · [PDF](https://arxiv.org/pdf/2610.16199)

## Abstract

Freely swiveling casters are widely adopted in industrial AMRs/SDVs for their mechanical simplicity and load capacity. However, caster misalignment during low-speed or high-curvature maneuvers induces strong contact nonlinearities, widening the planning-execution gap between commanded $(v, ω)$ and realized motion. Existing caster-aware strategies are highly sensitive to state-estimation reliability, causing unstable execution in uncertain transition regimes. To address this, we present Multi-Stage Caster-aware Control (MSC), a planning-execution integrated hierarchical framework featuring two core mechanisms. First, an uncertainty-aware NMPC (CU-MPC) dynamically schedules caster-aware costs and input regularization using predictive uncertainty to suppress overly aggressive maneuvers. Second, a reinforcement learning-based execution layer estimates and predicts caster states under partial observability, transforming high-level velocity commands into physically executable wheel speeds adapted to current contact conditions. Validations in Isaac Sim and real robots demonstrate that MSC offers a clear comparative advantage over existing decoupled compensation approaches by significantly improving caster-state estimation accuracy, minimizing misalignment, and enhancing tracking robustness in caster-sensitive maneuvers.

## TL;DR

Freely swiveling casters are widely adopted in industrial AMRs/SDVs for their mechanical simplicity and load capacity. However, caster misalignment during low-speed or high-curvature maneuvers induces strong contact nonlinearities, widening the planning-execution gap between commanded $(v, ω)$ and realized motion.

## Related
<!-- [[other-paper-citekey]] -->
