---
citekey: "chenGJKCBFControlBarrierFunctionsConvexRigidBody2026"
title: "GJK-CBF: Control Barrier Functions for Convex Rigid Body Collision Avoidance on SE(3)"
authors: ["Yi-Hsuan Chen", "Shuo Liu", "Wei Xiao", "Michael Otte", "Calin Belta"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04910"
doi: "10.48550/arXiv.2610.04910"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-07
---

# GJK-CBF: Control Barrier Functions for Convex Rigid Body Collision Avoidance on SE(3)

> Yi-Hsuan Chen, Shuo Liu, Wei Xiao, Michael Otte, Calin Belta · 2026
> [arXiv](https://arxiv.org/abs/2610.04910) · [PDF](https://arxiv.org/pdf/2610.04910)

## Abstract

Collision avoidance among convex bodies is a fundamental problem in robotics. Control Barrier Functions (CBFs) provide a practical framework for real-time safety filtering due to their computational efficiency. For general convex bodies, exact separation measures, such as distance or scaling factor, are typically computed through optimization. Existing CBF formulations often obtain the required gradient via differentiable optimization (diffOpt), adding computational overhead. In contrast, we leverage the Gilbert-Johnson-Keerthi (GJK) algorithm to obtain the current witness pair---the pair of points realizing the minimum distance or penetration depth---and formulate a CBF, termed GJK-CBF, whose gradient is constructed directly from the relative rigid-body motion of the witness pair, without resorting to diffOpt. This formulation applies to both 2D and 3D environments across a broad class of convex body pairs, provided that at least one in each one-to-one interaction is strictly convex. The proposed GJK-CBF is validated in various scenarios, including multi-robot position swapping in both 2D and 3D, navigation through a vertical slit in 3D, and its applicability to manipulators. The results demonstrate collision-free motion across all scenarios while reducing the conservativeness introduced by geometric approximations, particularly in narrow environments.

## TL;DR

Collision avoidance among convex bodies is a fundamental problem in robotics. Control Barrier Functions (CBFs) provide a practical framework for real-time safety filtering due to their computational efficiency.

## Related
<!-- [[other-paper-citekey]] -->
