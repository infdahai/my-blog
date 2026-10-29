---
citekey: "guoSG2SLAMSpatialGeometryInformed3DGaussianSplatting2026"
title: "SG^2SLAM: Spatial Geometry-Informed 3D Gaussian Splatting SLAM for Monocular Outdoor Navigation"
authors: ["Ziang Guo", "Didar Seyidov", "Yixiao Zhou", "Xuefeng Zhang", "Ali Alridha Abdulkarim", "Chen Min", "Zufeng Zhang", "Dzmitry Tsetserukou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36312"
doi: "10.48550/arXiv.2610.36312"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# SG^2SLAM: Spatial Geometry-Informed 3D Gaussian Splatting SLAM for Monocular Outdoor Navigation

> Ziang Guo, Didar Seyidov, Yixiao Zhou, Xuefeng Zhang, Ali Alridha Abdulkarim, Chen Min, Zufeng Zhang, Dzmitry Tsetserukou · 2026
> [arXiv](https://arxiv.org/abs/2610.36312) · [PDF](https://arxiv.org/pdf/2610.36312)

## Abstract

Monocular outdoor navigation requires robust camera motion estimation and a dense, navigable map, where 3D Gaussian Splatting SLAM serves this task through an explicit differentiable parameterization and closed-form projection. However, typically, the geometry is recovered by associating 2D pixels with 3D points, so a modular SLAM system absorbs tracking error into the map, leading to cascading degradation. To address these gaps, we present SG^2SLAM, which couples streaming spatial geometry with a ray-conditioned 3DGS kernel. Streaming spatial geometry replaces the per- frame cross-dimensional correspondence with a chunk-level metric prior that supervises tracking and mapping from one source. A ray-conditioned kernel extends each primitive with a viewing-direction subspace that senses the monocular camera viewpoints. The joint optimization over spatial geometry and poses ensures a globally consistent map and trajectory outcome. Experiments on the KITTI and Waymo Open datasets show that our SG^2SLAM surpasses the per-frame association baselines in the monocular outdoor navigation task. Code will be made publicly available upon acceptance.

## TL;DR

Monocular outdoor navigation requires robust camera motion estimation and a dense, navigable map, where 3D Gaussian Splatting SLAM serves this task through an explicit differentiable parameterization and closed-form projection. However, typically, the geometry is recovered by associating 2D pixels with 3D points, so a modular SLAM system absorbs tracking error into the map, leading to cascading degradation.

## Related
<!-- [[other-paper-citekey]] -->
