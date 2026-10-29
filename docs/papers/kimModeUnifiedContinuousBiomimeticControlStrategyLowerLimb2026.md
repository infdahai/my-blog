---
citekey: "kimModeUnifiedContinuousBiomimeticControlStrategyLowerLimb2026"
title: "A Mode-Unified, Continuous, and Biomimetic Control Strategy of a Robotic Lower Limb Prosthesis"
authors: ["Hanjun Kim", "Sixu Zhou", "John Shim", "Xinyuan Guo", "Kinsey R. Herrin", "Aaron J. Young"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19183"
doi: "10.48550/arXiv.2610.19183"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# A Mode-Unified, Continuous, and Biomimetic Control Strategy of a Robotic Lower Limb Prosthesis

> Hanjun Kim, Sixu Zhou, John Shim, Xinyuan Guo, Kinsey R. Herrin, Aaron J. Young · 2026
> [arXiv](https://arxiv.org/abs/2610.19183) · [PDF](https://arxiv.org/pdf/2610.19183)

## Abstract

Existing biomimetic lower-limb prosthesis controllers are commonly designed for discrete locomotion modes, requiring separate parameterizations for level walking, ramps, and stairs. We present a mode-unified prosthesis control framework that represents knee and ankle biomechanics continuously as functions of terrain slope and gait phase across those locomotion conditions. Locally optimized ascent and descent polynomial models were unified using radial basis function (RBF) interpolation, preserving the accuracy of the partitioned models while outperforming a global polynomial representation. The resulting biomechanics were transformed into continuous and slope-dependent impedance parameters and implemented within a single finite-state-machine (FSM) controller using bilateral sensing for gait-state estimation. Experiments with 10 individuals with transfemoral amputation demonstrated terrain-adaptive locomotion from level walking through ramps and stairs up to 35 degrees, including 13 degree ramp and 15 degree stair conditions absent from the underlying able-bodied (AB) dataset. Experimental results reproduced the principal slope-dependent biomechanical trends predicted by the unified model, with high agreement for knee-related measures (r-square = 0.82 - 0.99) and ankle kinematics (r-square= 0.78 - 0.96). These findings demonstrated that unified biomechanical parameterization enables a prosthesis control architecture across diverse terrain conditions while preserving key features of AB biomechanics without requiring independently tuned impedance parameter sets for each locomotion mode.

## TL;DR

Existing biomimetic lower-limb prosthesis controllers are commonly designed for discrete locomotion modes, requiring separate parameterizations for level walking, ramps, and stairs. We present a mode-unified prosthesis control framework that represents knee and ankle biomechanics continuously as functions of terrain slope and gait phase across those locomotion conditions.

## Related
<!-- [[other-paper-citekey]] -->
