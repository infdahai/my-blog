---
citekey: "sigurdsonOATHObjectAgnosticTrackingDexterousHandsEnablingRapid2026"
title: "OATH: Object-Agnostic Tracking for Dexterous Hands, Enabling Rapid Physics-based Retargeting"
authors: ["Solvin Sigurdson", "Prasanna Sriganesh", "Juan Borbon", "Joel Burdick", "Dingqi Zhang", "Jiuguang Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14379"
doi: "10.48550/arXiv.2610.14379"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# OATH: Object-Agnostic Tracking for Dexterous Hands, Enabling Rapid Physics-based Retargeting

> Solvin Sigurdson, Prasanna Sriganesh, Juan Borbon, Joel Burdick, Dingqi Zhang, Jiuguang Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.14379) · [PDF](https://arxiv.org/pdf/2610.14379)

## Abstract

Retargeting human demonstrations into dynamically feasible dexterous hand trajectories requires resolving complex contact physics, yet current methods either omit physical constraints or rely on computationally expensive sampling-based optimization in simulation. Reinforcement learning has previously been used to achieve planning and control through contact dynamics; however, standard policies require object-specific training and fail to generalize across arbitrary geometries. This work reframes physics-based retargeting as a residual learning problem, where we demonstrate that zero-shot generalization across objects relies on structured state representations. Specifically, formulating the observation space to include a localized contact-error signal guiding each robot link to its target coordinate on the object surface enables a single, unified residual policy to successfully grasp novel, unseen object geometries. Rolling out this policy in simulation on a kinematic reference trajectory yields a physics-based retargeter, OATH. Operating at 0.4 seconds of compute per second of reference, OATH achieves 2.4x faster-than-real-time performance and a 60-350x reduction in computational cost compared to sampling-based methods. The system recovers 58% of held-out and 54% of unseen-object DexYCB trajectories while maintaining a sub-2 cm tracking error.

## TL;DR

Retargeting human demonstrations into dynamically feasible dexterous hand trajectories requires resolving complex contact physics, yet current methods either omit physical constraints or rely on computationally expensive sampling-based optimization in simulation. Reinforcement learning has previously been used to achieve planning and control through contact dynamics; however, standard policies require object-specific training and fail to generalize across arbitrary geometries.

## Related
<!-- [[other-paper-citekey]] -->
