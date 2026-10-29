---
citekey: "rheeFoundationVIOEnforcingMetricScaleFeedForwardVisualInertial2026"
title: "FoundationVIO: Enforcing Metric Scale in Feed-forward Visual-Inertial Odometry"
authors: ["Jin Rhee", "Yuhao Zhang", "Frank Dellaert", "Maurice Fallon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14951"
doi: "10.48550/arXiv.2610.14951"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# FoundationVIO: Enforcing Metric Scale in Feed-forward Visual-Inertial Odometry

> Jin Rhee, Yuhao Zhang, Frank Dellaert, Maurice Fallon · 2026
> [arXiv](https://arxiv.org/abs/2610.14951) · [PDF](https://arxiv.org/pdf/2610.14951)

## Abstract

Feed-forward geometric foundation models (GFMs) directly predict dense geometry and camera poses from batches of images. Emerging visual SLAM methods chain together consecutive GFM batches to form dense point cloud maps. A core challenge is how to address the ambiguous geometric scale of GFM predictions: independent predictions are locally consistent up-to-scale but not constrained by any direct physical measurements. Models trained on data with known scale improve the consistency of GFM reconstructions but again do not directly measure it. Consequently, trajectories and 3D reconstructions from GFM-enabled SLAM methods inherit this issue. Motivated by parallels with classical visual-inertial odometry, we introduce FoundationVIO which integrates inertial sensing with GFM predictions to recover metric scale reconstruction using a factor-graph based approach. We demonstrate odometry estimates competitive with classical state-of-the-art VIO methods and accurate dense reconstructions that outperform GFM-enabled SLAM methods. We also add a minimal GFM-based loop-closure mechanism to create a full Visual-Inertial SLAM system capable of creating globally accurate reconstructions and pose estimates. We evaluate our method on three datasets with well known sensor systems and demonstrate its compatibility on ubiquitous camera and IMU sensors. The method runs at approximately real-time on a consumer-grade laptop GPU. Code: https://github.com/ori-drs/FoundationVIO.

## TL;DR

Feed-forward geometric foundation models (GFMs) directly predict dense geometry and camera poses from batches of images. Emerging visual SLAM methods chain together consecutive GFM batches to form dense point cloud maps.

## Related
<!-- [[other-paper-citekey]] -->
