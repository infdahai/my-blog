---
citekey: "zhuBenchmarkingVisualInertialOdometrySubterraneanEnvironmentsSensorDegradation2026"
title: "Benchmarking Visual-Inertial Odometry in Subterranean Environments Under Sensor Degradation, Miscalibration, and Dynamic Occlusion"
authors: ["Yueying Zhu", "Xiang Li", "Thien-Minh Nguyen", "Xuehe Wang", "Shenghai Yuan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18628"
doi: "10.48550/arXiv.2609.18628"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# Benchmarking Visual-Inertial Odometry in Subterranean Environments Under Sensor Degradation, Miscalibration, and Dynamic Occlusion

> Yueying Zhu, Xiang Li, Thien-Minh Nguyen, Xuehe Wang, Shenghai Yuan · 2026
> [arXiv](https://arxiv.org/abs/2609.18628) · [PDF](https://arxiv.org/pdf/2609.18628)

## Abstract

Visual-inertial odometry (VIO) is a core capability for autonomous operation in GPS-denied subterranean environments, yet its reliability can degrade sharply under sensor drift, calibration errors, and dynamic occlusion. Existing evaluations mainly emphasize nominal-condition accuracy, offering limited insight into when practical deployment failures occur. In this work, we present a failure-centric stress-test benchmark for VIO in underground environments using the CERBERUS dataset. We systematically evaluate four representative VIO systems spanning filtering-, optimization-, and learning-based paradigms under nine practical perturbation settings, including IMU bias and noise variation, camera intrinsic and extrinsic drift, and dynamic scene occlusion. Beyond conventional trajectory error, we analyze robustness limits through coverage ratio and failure thresholds, revealing breakdown behaviors that are not captured by nominal-condition performance alone. Our study shows distinct vulnerability patterns across VIO paradigms: some methods are more sensitive to inertial degradation, while others are more affected by geometric miscalibration or dynamic interference. These results provide deployment-oriented guidance for VIO selection, calibration prioritization, and reliable operation in challenging underground scenarios. To support reproducible evaluation and future extensions, we will release the full benchmark scripts and evaluation pipeline.

## TL;DR

Visual-inertial odometry (VIO) is a core capability for autonomous operation in GPS-denied subterranean environments, yet its reliability can degrade sharply under sensor drift, calibration errors, and dynamic occlusion. Existing evaluations mainly emphasize nominal-condition accuracy, offering limited insight into when practical deployment failures occur.

## Related
<!-- [[other-paper-citekey]] -->
