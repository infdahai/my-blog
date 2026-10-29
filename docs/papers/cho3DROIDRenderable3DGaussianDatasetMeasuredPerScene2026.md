---
citekey: "cho3DROIDRenderable3DGaussianDatasetMeasuredPerScene2026"
title: "3DROID: A Renderable 3D Gaussian Dataset with Measured Per-Scene Reliability"
authors: ["Wonguen Cho", "Junhoo Lee", "Nojun Kwak"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01744"
doi: "10.48550/arXiv.2610.01744"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# 3DROID: A Renderable 3D Gaussian Dataset with Measured Per-Scene Reliability

> Wonguen Cho, Junhoo Lee, Nojun Kwak · 2026
> [arXiv](https://arxiv.org/abs/2610.01744) · [PDF](https://arxiv.org/pdf/2610.01744)

## Abstract

Robot manipulation models primarily reason from 2D observations while acting in the 3D physical world. To bridge this gap, recent work has augmented robot data with geometric priors such as depth, point clouds, and 3D trajectories, while renderable 3D Gaussian representations provide another promising form of 3D supervision. However, 3DGS representation is designed mainly for photometric fidelity and may not preserve real-world metric scale, particularly when the supplied camera extrinsics are unreliable. We study the effect of extrinsic reliability and pose conditioning on feed-forward 3DGS, and propose a calibration-aware pipeline that anchors reconstructed scenes to the robot's metric workspace. Our experiments show that pose conditioning improves novel-view fidelity, while its geometric benefit depends on the reliability of the injected extrinsics. Using this pipeline, we present a renderable, metric-pose-anchored dataset with scene-level reliability information for robot manipulation research. Our dataset is available at https://huggingface.co/datasets/wonguen/3DROID

## TL;DR

Robot manipulation models primarily reason from 2D observations while acting in the 3D physical world. To bridge this gap, recent work has augmented robot data with geometric priors such as depth, point clouds, and 3D trajectories, while renderable 3D Gaussian representations provide another promising form of 3D supervision.

## Related
<!-- [[other-paper-citekey]] -->
