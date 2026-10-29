---
citekey: "mastersHumanLoopGeospatialAnnotationRapidDatasetConstructionField2026"
title: "Human-in-the-Loop Geospatial Annotation for Rapid Dataset Construction in Field-Deployed UAV Systems"
authors: ["Morgan Masters", "Nikolaas Bender", "T. Luca Altaffer", "Colleen Josephson", "Steve McGuire"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28767"
doi: "10.48550/arXiv.2609.28767"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# Human-in-the-Loop Geospatial Annotation for Rapid Dataset Construction in Field-Deployed UAV Systems

> Morgan Masters, Nikolaas Bender, T. Luca Altaffer, Colleen Josephson, Steve McGuire · 2026
> [arXiv](https://arxiv.org/abs/2609.28767) · [PDF](https://arxiv.org/pdf/2609.28767)

## Abstract

Real-world perception systems must adapt to changing environments, but manual image annotation cannot scale to field data volumes. We present BirdsEye, which shifts expert annotation from images to the field: an operator records target locations in world coordinates using RTK positioning and calibrated projective geometry propagates each observation to all frames where the target is visible. To quantify how well physical annotations align with image observations, we derive a first-order mapping from camera-pose uncertainty to pixel uncertainty and validate it against Monte Carlo simulation. This mapping is linear in the six per-axis pose variances, so it inverts into a sensor design tool: we give a sufficient condition converting an annotation tolerance into a convex set of admissible pose-noise budgets, a closed-form largest admissible scaling of a deployed sensor suite, and a unique per-axis pose specification under an equal-budget-share allocation. We also analyze the planar-surface approximation underlying the projection, which holds up to 10 degrees of terrain slope. By direct measurement, we show that system projection accuracy is sub-decimeter (sub-30 pixel) at AGL altitudes of 10-20m under conditions excluding sustained yawing. During an in-field case study across three agricultural sites, two field workers produced 12,524 annotated frames carrying 55,600 labels in roughly 12 hours (25.5x per-worker rate increase over manual labeling). Detectors trained on imagery collected by this workflow recovered 56-89% of in-view surveyed targets at a geographically distinct farm, at pre-registered operating points; human review of the leading configuration estimates detection precision at 83-87%, spanning three tie-break conventions for clusters carrying contradictory human verdicts.

## TL;DR

Real-world perception systems must adapt to changing environments, but manual image annotation cannot scale to field data volumes. We present BirdsEye, which shifts expert annotation from images to the field: an operator records target locations in world coordinates using RTK positioning and calibrated projective geometry propagates each observation to all frames where the target is visible.

## Related
<!-- [[other-paper-citekey]] -->
