---
citekey: "kyawGeodexLibraryMotionPlanningRiemannianManifolds2026"
title: "geodex: A Library for Motion Planning on Riemannian Manifolds"
authors: ["Phone Thiha Kyaw", "Ben Wei", "Sepehr Samavi", "Miguel Angel Rogel Garcia", "Jonathan Kelly"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09165"
doi: "10.48550/arXiv.2610.09165"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# geodex: A Library for Motion Planning on Riemannian Manifolds

> Phone Thiha Kyaw, Ben Wei, Sepehr Samavi, Miguel Angel Rogel Garcia, Jonathan Kelly · 2026
> [arXiv](https://arxiv.org/abs/2610.09165) · [PDF](https://arxiv.org/pdf/2610.09165)

## Abstract

Planning motions that respect the intrinsic geometry of a robot's configuration space, including its curvature and a configuration-dependent notion of cost, yields shorter, lower-energy, and more natural trajectories than planning under the ambient flat metric. Existing libraries for optimization on manifolds provide rich geometric primitives but do not plan around obstacles. While general-purpose motion planning libraries support many state spaces and custom distance functions, they do not yet treat a configuration-dependent Riemannian metric as the geometry that drives distance, interpolation, and geodesics. We present geodex, an open-source C++20 library with Python bindings. The library exposes the manifold, its Riemannian metric, the retraction, and the sampler as independent, interchangeable components through a single sampling-based motion planning interface. The same planner runs unchanged on canonical spaces $\mathbb{R}^n$, $\mathbb{T}^n$, $\mathbb{S}^n$, matrix Lie groups such as $SO(2)$, $SE(2)$, $SO(3)$, and $SE(3)$, products of these spaces, and articulated-robot configuration spaces, each equipped with a user-defined Riemannian metric. We make geodex publicly available with documentation, tests, and a reproducible benchmark suite.

## TL;DR

Planning motions that respect the intrinsic geometry of a robot's configuration space, including its curvature and a configuration-dependent notion of cost, yields shorter, lower-energy, and more natural trajectories than planning under the ambient flat metric. Existing libraries for optimization on manifolds provide rich geometric primitives but do not plan around obstacles.

## Related
<!-- [[other-paper-citekey]] -->
