---
citekey: "santucciRootSLAMSquareRootBundleAdjustmentVisualInertialSLAM2026"
title: "RootSLAM: Square Root Bundle Adjustment for Visual-Inertial SLAM"
authors: ["Tom\\'as Santucci", "Mateo de Mayo", "Daniel Cremers", "Taih\\'u Pire"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.15157"
doi: "10.48550/arXiv.2610.15157"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# RootSLAM: Square Root Bundle Adjustment for Visual-Inertial SLAM

> Tom\'as Santucci, Mateo de Mayo, Daniel Cremers, Taih\'u Pire · 2026
> [arXiv](https://arxiv.org/abs/2610.15157) · [PDF](https://arxiv.org/pdf/2610.15157)

## Abstract

Efficient perception is a prerequisite for the small, low-power devices targeted by robotics, mixed reality, autonomous driving, and drone applications, all of which rely on Simultaneous Localization and Mapping (SLAM) to estimate their motion within their surroundings. Learning-based SLAM systems achieve state-of-the-art accuracy but are demanding in compute, whereas classical geometry-based methods retain a strong efficiency advantage with little to no loss in accuracy. In this work we present RootSLAM, a fully-featured visual-inertial SLAM system for multi-camera setups built on Basalt. RootSLAM achieves accuracy competitive with the state of the art while running up to 20 times faster, facilitating the deployment of perception systems in resource constrained environments. We adapt the square-root bundle adjustment formulation from structure from motion into the multi-camera visual-inertial SLAM setting through a novel reformulation that leverages the system's pose-graph, letting the global optimizer run in single-precision floating point, thus doubling its performance. We provide a thorough benchmark against the state of the art together with an ablation study of our contributions. Our new implementation, including its map management and loop detection module, pose-graph optimizer, and global mapping components, will be open-sourced.

## TL;DR

Efficient perception is a prerequisite for the small, low-power devices targeted by robotics, mixed reality, autonomous driving, and drone applications, all of which rely on Simultaneous Localization and Mapping (SLAM) to estimate their motion within their surroundings. Learning-based SLAM systems achieve state-of-the-art accuracy but are demanding in compute, whereas classical geometry-based methods retain a strong efficiency advantage with little to no loss in accuracy.

## Related
<!-- [[other-paper-citekey]] -->
