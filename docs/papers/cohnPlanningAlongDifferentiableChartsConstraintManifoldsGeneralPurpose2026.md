---
citekey: "cohnPlanningAlongDifferentiableChartsConstraintManifoldsGeneralPurpose2026"
title: "Planning along Differentiable Charts of Constraint Manifolds with General-Purpose IK Solvers"
authors: ["Thomas Cohn", "Seiji Shaw", "Harel Biggie", "Travis Manderson", "Nicholas Roy", "Russ Tedrake"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.10905"
doi: "10.48550/arXiv.2609.10905"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# Planning along Differentiable Charts of Constraint Manifolds with General-Purpose IK Solvers

> Thomas Cohn, Seiji Shaw, Harel Biggie, Travis Manderson, Nicholas Roy, Russ Tedrake · 2026
> [arXiv](https://arxiv.org/abs/2609.10905) · [PDF](https://arxiv.org/pdf/2609.10905)

## Abstract

Planning trajectories for robot manipulators under kinematic equality constraints restricts feasible motions to a measure-zero submanifold of the configuration space, requiring special algorithmic treatment. A promising strategy is parametrizing the set of feasible configurations using analytic inverse kinematics (IK). Bespoke analytic IK functions can be written to be differentiable, a necessary property for gradient-based trajectory optimization. But the vast majority of IK functions are computed by automated meta-solvers like IKFast, and are difficult to modify for differentiability. We present a new approach for computing gradients of analytic IK parameterizations: we leverage the inverse function theorem to recover the desired gradients from the ordinary forward kinematic Jacobian. Furthermore, we present a least-squares domain extension and an optimization-amenable description of the reachability constraint, which preserves gradient signal outside the reachable workspace. We demonstrate the efficacy of our approach through numerical experiments and downstream tasks, including a hardware demonstration of an RB-Y1 picking up a box and placing it on a table. Project website: https://cohnt.github.io/inverse-function-theorem-parameterization/

## TL;DR

Planning trajectories for robot manipulators under kinematic equality constraints restricts feasible motions to a measure-zero submanifold of the configuration space, requiring special algorithmic treatment. A promising strategy is parametrizing the set of feasible configurations using analytic inverse kinematics (IK).

## Related
<!-- [[other-paper-citekey]] -->
