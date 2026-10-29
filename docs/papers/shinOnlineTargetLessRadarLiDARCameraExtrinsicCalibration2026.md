---
citekey: "shinOnlineTargetLessRadarLiDARCameraExtrinsicCalibration2026"
title: "Online Target-less Radar-LiDAR-Camera Extrinsic Calibration via Joint Optimization"
authors: ["Gunhee Shin", "Yunsoo Kim", "Chanhyuk Lee", "Wanhee Kim", "Minwoo Lee", "Sungwoo Han", "Jeongwoo Woo", "Hyuntai Chin", "Minha Park", "Hyun Myung"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04552"
doi: "10.48550/arXiv.2610.04552"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Online Target-less Radar-LiDAR-Camera Extrinsic Calibration via Joint Optimization

> Gunhee Shin, Yunsoo Kim, Chanhyuk Lee, Wanhee Kim, Minwoo Lee, Sungwoo Han, Jeongwoo Woo, Hyuntai Chin, Minha Park, Hyun Myung · 2026
> [arXiv](https://arxiv.org/abs/2610.04552) · [PDF](https://arxiv.org/pdf/2610.04552)

## Abstract

Fusing radar, LiDAR, and camera enables robust perception in diverse and adverse conditions, but the fusion performance critically depends on accurate extrinsic calibration among the three sensors. In this paper, we address the problem of online target-less extrinsic calibration for the radar-LiDAR-camera system. Existing target-less methods are mostly designed for a single sensor pair, and composing the pairwise results does not guarantee consistency across the three sensors. Moreover, the sparse and noisy radar measurements make the radar-involving pairs unreliable. To tackle these challenges, we propose a joint calibration framework that constructs residuals for each sensor pair and optimizes the extrinsics of all pairs together to minimize the overall residual. Furthermore, we introduce an adaptive radar noise filter that rejects spurious radar returns using a range-dependent margin, and a correspondence accumulation strategy that aggregates sparse radar correspondences over frames. We validate our method on an in-house radar-LiDAR-camera dataset covering diverse urban environments, where it reduces calibration errors across all sensor pairs over a state-of-the-art camera-LiDAR baseline.

## TL;DR

Fusing radar, LiDAR, and camera enables robust perception in diverse and adverse conditions, but the fusion performance critically depends on accurate extrinsic calibration among the three sensors. In this paper, we address the problem of online target-less extrinsic calibration for the radar-LiDAR-camera system.

## Related
<!-- [[other-paper-citekey]] -->
