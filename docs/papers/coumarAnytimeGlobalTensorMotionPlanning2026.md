---
citekey: "coumarAnytimeGlobalTensorMotionPlanning2026"
title: "Anytime Global Tensor Motion Planning"
authors: ["Sai Coumar", "An T. Le", "Zachary Kingston"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25830"
doi: "10.48550/arXiv.2608.25830"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-28
---

# Anytime Global Tensor Motion Planning

> Sai Coumar, An T. Le, Zachary Kingston · 2026
> [arXiv](https://arxiv.org/abs/2608.25830) · [PDF](https://arxiv.org/pdf/2608.25830)

## Abstract

Global Tensor Motion Planning (GTMP) solves motion planning with batched tensor operations over a layered multipartite graph. We generalize GTMP so that adjacent-layer edges are realized by any black-box local planner (e.g., linear interpolation, splines, sampling-based planning, trajectory optimization, or generative sampling). We provide two anytime policies on top of this generalization: Anytime GTMP with random restarts at a fixed budget, which covers every homotopy class almost surely, and AO-GTMP with informed expansion with growing budgets, which converges to the optimal cost. We prove that a single sampled graph covers every endpoint-fixed homotopy class admitting a \(\delta\)-clear representative of bounded length. We also prove that additional samples per layer reduce the per-layer miss probability exponentially, whereas stronger local planners reduce the required layer count only sublinearly. On manipulation benchmarks the method matches state-of-the-art performance, and on 2D navigation it returns batches of topologically diverse solutions, while the informed baselines concentrate on one or two classes.

## TL;DR

Global Tensor Motion Planning (GTMP) solves motion planning with batched tensor operations over a layered multipartite graph. We generalize GTMP so that adjacent-layer edges are realized by any black-box local planner (e.g., linear interpolation, splines, sampling-based planning, trajectory optimization, or generative sampling).

## Related
<!-- [[other-paper-citekey]] -->
