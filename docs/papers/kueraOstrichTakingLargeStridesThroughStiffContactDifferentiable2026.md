---
citekey: "kueraOstrichTakingLargeStridesThroughStiffContactDifferentiable2026"
title: "Ostrich: Taking Large Strides Through Stiff Contact in Differentiable Dynamics"
authors: ["Aleš Kučera", "Karel Zimmermann"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.08800"
doi: "10.48550/arXiv.2609.08800"
tags: [paper, embodied-ai, "cs.GR", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# Ostrich: Taking Large Strides Through Stiff Contact in Differentiable Dynamics

> Aleš Kučera, Karel Zimmermann · 2026
> [arXiv](https://arxiv.org/abs/2609.08800) · [PDF](https://arxiv.org/pdf/2609.08800)

## Abstract

Three properties determine whether a differentiable simulator can drive gradient-based optimization through contact: simulation accuracy, gradient reliability, and per-iteration cost. Tape-based engines such as MJX and Newton Semi-Implicit require timesteps small enough to keep contacts numerically tractable, and their backpropagation memory grows linearly with the number of timesteps T. Surrogate models bound memory by approximating contact away, but the resulting gradients lose the geometry the optimization depends on. We present Ostrich, a GPU-accelerated rigid-body simulator that resolves hard contacts and friction with non-smooth Newton iteration at large timesteps (h ~ 0.1 s), and differentiates the converged residual via the implicit function theorem, reusing the forward Schur complement to compute the adjoint at O(1) memory per timestep. On real-robot trajectories over a pallet obstacle, Ostrich holds MuJoCo's sim-to-real accuracy up to a 50x larger timestep. Its gradients converge from random initializations where MJX descends slowly and Newton Semi-Implicit stalls; a warm iteration runs 211x faster than MJX's and 4.7x faster than Semi-Implicit's. On the same scene Ostrich differentiates 8,192 parallel worlds on a single 24 GB GPU, sustaining 29x checkpointed MJX's optimization throughput; without checkpointing both baselines exhaust memory at far fewer worlds. We close with a gradient-based trajectory optimization demonstration over triangle-mesh terrain across a 10 s horizon, a setting where prior engines either restrict to primitive geometry or face the convergence and memory limits shown above.

## TL;DR

Three properties determine whether a differentiable simulator can drive gradient-based optimization through contact: simulation accuracy, gradient reliability, and per-iteration cost. Tape-based engines such as MJX and Newton Semi-Implicit require timesteps small enough to keep contacts numerically tractable, and their backpropagation memory grows linearly with the number of timesteps T.

## Related
<!-- [[other-paper-citekey]] -->
