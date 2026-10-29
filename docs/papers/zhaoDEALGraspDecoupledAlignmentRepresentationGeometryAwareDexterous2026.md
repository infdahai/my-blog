---
citekey: "zhaoDEALGraspDecoupledAlignmentRepresentationGeometryAwareDexterous2026"
title: "DEAL-Grasp: Decoupled Alignment Representation for Geometry-Aware Dexterous Grasp Generation"
authors: ["Fuqiang Zhao", "Qian Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28131"
doi: "10.48550/arXiv.2609.28131"
tags: [paper, embodied-ai, "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# DEAL-Grasp: Decoupled Alignment Representation for Geometry-Aware Dexterous Grasp Generation

> Fuqiang Zhao, Qian Liu · 2026
> [arXiv](https://arxiv.org/abs/2609.28131) · [PDF](https://arxiv.org/pdf/2609.28131)

## Abstract

Synthesizing realistic articulated hand-object interactions is a fundamental problem in virtual reality, embodied intelligence, and digital human applications. Existing methods for dexterous grasp synthesis typically regress or denoise poses in a joint space that couples global rigid motion with local articulation, which often yields unstable samples and physically implausible contacts. We introduce DEAL-Grasp, built upon the Decoupled Alignment (DEAL) representation, which reformulates grasp synthesis as alignment-space generation: the interaction state comprises task-space geometric anchors and articulation parameters, from which the rigid transform is recovered via closed-form Procrustes alignment while preserving local articulation. On this mixed state, we model grasp generation using heterogeneous-state flow matching with component-wise vector fields, incorporating time-adaptive physical regularization during training. At inference, grasps are synthesized solely by integrating the learned vector field, without test-time optimization or auxiliary physical guidance. Across MultiDex and zero-shot RealDex benchmarks, DEAL-Grasp attains high force-perturbation success rates alongside minimal penetration and high diversity of generated grasps, while substantially reducing native inference latency compared to optimization-heavy baselines. The project page is available at https://wmtlab.github.io/DEAL-Grasp/.

## TL;DR

Synthesizing realistic articulated hand-object interactions is a fundamental problem in virtual reality, embodied intelligence, and digital human applications. Existing methods for dexterous grasp synthesis typically regress or denoise poses in a joint space that couples global rigid motion with local articulation, which often yields unstable samples and physically implausible contacts.

## Related
<!-- [[other-paper-citekey]] -->
