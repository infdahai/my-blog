---
citekey: "vatsReachabilityBasedSafetyCertificateDynamicalSystemMotionPolicies2026"
title: "A Reachability-based Safety Certificate for Dynamical System Motion Policies"
authors: ["Aditya Vats", "Tianyi Xia", "Nadia Figueroa"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38421"
doi: "10.48550/arXiv.2609.38421"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# A Reachability-based Safety Certificate for Dynamical System Motion Policies

> Aditya Vats, Tianyi Xia, Nadia Figueroa · 2026
> [arXiv](https://arxiv.org/abs/2609.38421) · [PDF](https://arxiv.org/pdf/2609.38421)

## Abstract

Dynamical Systems (DS) are reactive motion policies representing vector fields trained with theoretical guarantees of stability and convergence. To ensure safety during deployment in unknown environments they must be locally reshaped, either through modulation or geometric control barrier function strategies. However, depending on the geometry of the obstacles and the complexity of the DS, these local strategies can lead the system to unavoidable collisions or spurious attractors. In this work, we certify safety with a value function drawn from the notion of backward reachability tube, which measures the worst-case safety along a rollout trajectory of the nominal DS. Usually, such a value function is intractable for a controlled system due to curse of dimensionality. We show that in the DS-based learning-from-demonstration setting, the absence of a control input collapses the reachability problem to a deterministic rollout, and the presence of certain stability conditions truncates the infinite horizon to a finite one, resulting in a well-defined value function. We further show that the value function we devised is the maximal forward-invariant subset of the obstaclefree region for the nominal DS flow. The application of this certificate function is validated across five DS constructions - analytical, Neural ODE, diffeomorphic latent space, LPV-DS, SE(3)and validate it on a Franka manipulator. Modulation and geometric CBFs also suffer from saddle point in cases of headon approach towards an unsafe zone. We show that CBF-on-V avoids this pitfall entirely.

## TL;DR

Dynamical Systems (DS) are reactive motion policies representing vector fields trained with theoretical guarantees of stability and convergence. To ensure safety during deployment in unknown environments they must be locally reshaped, either through modulation or geometric control barrier function strategies.

## Related
<!-- [[other-paper-citekey]] -->
