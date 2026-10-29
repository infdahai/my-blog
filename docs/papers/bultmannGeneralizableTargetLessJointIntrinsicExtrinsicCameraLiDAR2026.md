---
citekey: "bultmannGeneralizableTargetLessJointIntrinsicExtrinsicCameraLiDAR2026"
title: "Generalizable Target-Less Joint Intrinsic-Extrinsic Camera-LiDAR Calibration using Deep Pixel-Point Correspondences"
authors: ["Simon Bultmann", "Daniele Cattaneo", "Abhinav Valada"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.37350"
doi: "10.48550/arXiv.2610.37350"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# Generalizable Target-Less Joint Intrinsic-Extrinsic Camera-LiDAR Calibration using Deep Pixel-Point Correspondences

> Simon Bultmann, Daniele Cattaneo, Abhinav Valada · 2026
> [arXiv](https://arxiv.org/abs/2610.37350) · [PDF](https://arxiv.org/pdf/2610.37350)

## Abstract

Accurate camera-LiDAR calibration is an essential prerequisite for robust multi-modal perception in robotics. Recent target-less methods based on learned pixel-point correspondences achieve high extrinsic calibration accuracy and generalize across environments. However, they operate on rectified images with known camera intrinsics, restricting their applicability to systems whose cameras have already been individually calibrated. We present a fully automatic, target-less framework that jointly estimates camera intrinsics, radial-tangential distortion, and camera-LiDAR extrinsics from raw images and LiDAR scans. Our method generalizes deep correspondence-based calibration from rectified images to raw cameras through intrinsic- and distortion-aware correspondence learning via synthetic augmentations. During calibration, we iteratively couple correspondence prediction and nonlinear optimization to jointly refine the camera parameters and relative sensor transformation. We evaluate our approach on an unseen camera-LiDAR configuration from the KITTI dataset and on three real robotic platforms in a zero-shot manner. The results demonstrate that joint calibration with our generalized pixel-point correspondence network improves extrinsic accuracy over correspondence-based methods using pre-calibrated cameras, while additionally recovering accurate intrinsics.

## TL;DR

Accurate camera-LiDAR calibration is an essential prerequisite for robust multi-modal perception in robotics. Recent target-less methods based on learned pixel-point correspondences achieve high extrinsic calibration accuracy and generalize across environments.

## Related
<!-- [[other-paper-citekey]] -->
