---
citekey: "rothenhauslerComfortConstructionAdaptiveComfortBoundedActionSpacesLearned2026"
title: "Comfort by Construction: Adaptive, Comfort-Bounded Action Spaces for Learned Driving Policies"
authors: ["Anna Rothenh\\\"ausler", "Daniel Jost", "Raghu Rajan", "Faris Janjos", "Oliver Scheel", "Andreas Look", "Joschka Boedecker"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.13011"
doi: "10.48550/arXiv.2609.13011"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# Comfort by Construction: Adaptive, Comfort-Bounded Action Spaces for Learned Driving Policies

> Anna Rothenh\"ausler, Daniel Jost, Raghu Rajan, Faris Janjos, Oliver Scheel, Andreas Look, Joschka Boedecker · 2026
> [arXiv](https://arxiv.org/abs/2609.13011) · [PDF](https://arxiv.org/pdf/2609.13011)

## Abstract

Data-driven driving simulators command accelerations and steering rates from a fixed grid without constraining the realized accelerations and jerks. As a result, reinforcement-learning policies inflate safety metrics through abrupt, last-second maneuvers that lie far outside the range of human driving and would be unacceptable to occupants of a real vehicle, so the metrics measure simulator permissiveness rather than policy quality. Enforcing comfort bounds naively is not enough: lateral limits shrink quadratically with speed, so clamping a static grid saturates it and destroys fine-grained control ("grid collapse"). We propose an adaptive action parameterization that rediscretizes the grid at every step to span exactly the per-step feasible control set, via closed-form inversion of the lateral-jerk constraint. We further present PufferDrive-Editor, a browser-based tool to audit realized kinematics and author kinematically challenging scenes. On the Waymo Open Motion Dataset and a hand-authored slalom, our adaptive model holds comfort violations below 1% while outperforming clipped-grid and direct-jerk baselines in navigability.

## TL;DR

Data-driven driving simulators command accelerations and steering rates from a fixed grid without constraining the realized accelerations and jerks. As a result, reinforcement-learning policies inflate safety metrics through abrupt, last-second maneuvers that lie far outside the range of human driving and would be unacceptable to occupants of a real vehicle, so the metrics measure simulator permissiveness rather than policy quality.

## Related
<!-- [[other-paper-citekey]] -->
