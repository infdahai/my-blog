---
citekey: "zhangOpticalCoherenceTomographyGuidedGeometricModelingSoftTissue2026"
title: "Robotic Optical Coherence Tomography-Guided Geometric Modeling of Soft Tissue: 3D Representations for Data-Driven Closed-Loop Shape Control"
authors: ["Chaoyu Zhang", "Guangshen Ma", "Mark Draelos"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32961"
doi: "10.48550/arXiv.2610.32961"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# Robotic Optical Coherence Tomography-Guided Geometric Modeling of Soft Tissue: 3D Representations for Data-Driven Closed-Loop Shape Control

> Chaoyu Zhang, Guangshen Ma, Mark Draelos · 2026
> [arXiv](https://arxiv.org/abs/2610.32961) · [PDF](https://arxiv.org/pdf/2610.32961)

## Abstract

In medical robotics, data-driven soft-tissue shape control requires deforming tissue toward desired morphologies through sequential physical interactions. This challenge is particularly important in microscale manipulation, where localized deformation is difficult to observe, represent, and control, while physics-based models can be computationally expensive and difficult to adapt to realistic environments. Optical coherence tomography (OCT) provides high-resolution volumetric perception of tissue deformation, but target-conditioned control requires effective representations of both observed and desired tissue states. In this work, we introduce an OCT-guided data-driven framework for tissue shape control, learned from user-guided demonstrations and executed with closed-loop OCT feedback. We study full-volume, tissue-masked sparse-volume, and voxelized point-cloud representations, with or without residual conditioning, using deterministic (Explicit) and generative diffusion (Diffusion) policies. Across 12 configurations and 576 phantom rollouts on 3-DoF depth and 6-DoF directional tasks, OCT-derived 3D representations support both Explicit and Diffusion policies, with performance depending on representation and residual conditioning. Residual conditioning reduces directional Shape RMSE from 0.748 to 0.555 mm for full-volume Diffusion, while voxelized point-cloud Explicit with residuals achieves 0.534 mm for depth and 0.443 mm for directional control, with comparable accuracy at intermediate unseen targets and consistent performance across deployments. We further evaluate the framework in 60 ex vivo porcine rollouts, extending to biological tissue with final geometric errors comparable to human demonstrations. These results establish volumetric OCT as current and goal representations for learned closed-loop tissue shape control across deterministic and generative action models.

## TL;DR

In medical robotics, data-driven soft-tissue shape control requires deforming tissue toward desired morphologies through sequential physical interactions. This challenge is particularly important in microscale manipulation, where localized deformation is difficult to observe, represent, and control, while physics-based models can be computationally expensive and difficult to adapt to realistic environments.

## Related
<!-- [[other-paper-citekey]] -->
