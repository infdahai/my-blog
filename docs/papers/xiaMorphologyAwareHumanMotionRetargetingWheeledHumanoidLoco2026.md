---
citekey: "xiaMorphologyAwareHumanMotionRetargetingWheeledHumanoidLoco2026"
title: "Morphology-Aware Human Motion Retargeting for Wheeled-Humanoid Loco-Manipulation"
authors: ["Chenbo Xia", "Chao Ye"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11357"
doi: "10.48550/arXiv.2609.11357"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# Morphology-Aware Human Motion Retargeting for Wheeled-Humanoid Loco-Manipulation

> Chenbo Xia, Chao Ye · 2026
> [arXiv](https://arxiv.org/abs/2609.11357) · [PDF](https://arxiv.org/pdf/2609.11357)

## Abstract

Human-to-humanoid retargeting has largely been studied on legged platforms, while comparatively few wheeled-humanoid systems support coupled locomotion and manipulation from general human motion. Building on GMR's configurable general-motion retargeting and BeyondMimic's physically simulated R1 Pro learning framework, we present a reproducible pipeline that converts multi-dataset SMPLX motion into executable loco-manipulation behavior for the Galaxea R1 Pro wheeled humanoid. The robot has a planar three-wheel base, a serial torso, and two arms but no leg joints, so human lower-body motion must be redistributed across base motion and torso posture without sacrificing manipulation-relevant arm geometry. Our pipeline combines canonical body-shape preprocessing, planar-base normalization, morphology-aware differential inverse kinematics, shoulder-rooted hierarchical arm retargeting, and continuous torso substitution for bending and squatting. A reference-twist-driven planning layer then decodes planar base motion into continuous three-wheel steering and rolling commands subject to hysteresis, kinematic continuity, acceleration, and actuator-rate limits. Finally, a 21-dimensional BaseDecode policy is trained in Isaac Lab with directional joint-limit scaling, focused upper-body tracking, and a staged wheel-contact reward. The resulting system provides a complete bridge from human motion data to physically trackable wheeled-humanoid loco-manipulation rather than a visualization-only retargeter; quantitative policy comparisons remain scheduled for a later revision.

## TL;DR

Human-to-humanoid retargeting has largely been studied on legged platforms, while comparatively few wheeled-humanoid systems support coupled locomotion and manipulation from general human motion. Building on GMR's configurable general-motion retargeting and BeyondMimic's physically simulated R1 Pro learning framework, we present a reproducible pipeline that converts multi-dataset SMPLX motion into executable loco-manipulation behavior for the Galaxea R1 Pro wheeled humanoid.

## Related
<!-- [[other-paper-citekey]] -->
