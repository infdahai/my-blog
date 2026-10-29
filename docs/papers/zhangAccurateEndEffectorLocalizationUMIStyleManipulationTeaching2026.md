---
citekey: "zhangAccurateEndEffectorLocalizationUMIStyleManipulationTeaching2026"
title: "Towards Accurate End-Effector Localization for UMI-Style Robotic Manipulation Teaching"
authors: ["Junjie Zhang", "Deteng Zhang", "Zhisong Xu", "Bo Sun", "Liuyang Li", "Yihong Tian", "Jie Yin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09857"
doi: "10.48550/arXiv.2610.09857"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Towards Accurate End-Effector Localization for UMI-Style Robotic Manipulation Teaching

> Junjie Zhang, Deteng Zhang, Zhisong Xu, Bo Sun, Liuyang Li, Yihong Tian, Jie Yin · 2026
> [arXiv](https://arxiv.org/abs/2610.09857) · [PDF](https://arxiv.org/pdf/2610.09857)

## Abstract

Robot demonstration learning requires accurate and temporally complete end-effector localization during close-range manipulation and camera occlusion. Existing SLAM benchmarks emphasize navigation motions, whereas manipulation datasets prioritize policy learning over localization evaluation. We introduce MILD, a Manipulation-Interface Localization Dataset with real-world and simulation sequences. The real-world subset provides 86 sensor sequences from Insta360 X5 and Insight9 across 15 repeated tabletop tasks, calibration assets, and a per-execution robot end-effector reference trajectory. The simulation subset, MILD-Sim, extends task coverage in Isaac Sim for controlled manipulation-replay studies. Benchmarking visual-inertial and fiducial-aided systems on instrumented real-world recordings reveals large differences in both TCP-relative trajectory error and temporal coverage, even under the same nominal task. To support marker-augmented teaching workspaces without a pre-surveyed fiducial map, we present AprilVINS, which combines fisheye visual-inertial estimation with sequence-local AprilTag geometry and separates prior admission from guarded export of the jointly optimized state. On Insta360 AprilTag4 recordings, AprilVINS(full) under a unified protocol with sequence-specific profiles reaches millimeter-level SE(3)-aligned TCP-relative APE RMSE with high time completion and lower reported error than the tested routes under their respective protocols, whereas fisheye VIO without tag factors remains at centimeter scale. Ablations separate accuracy from exportability, and a MILD-Sim replay study provides task-specific tolerance references for interpreting those error magnitudes. Together, MILD and AprilVINS provide a diagnostic benchmarking framework for UMI-style demonstration collection. Code, datasets, and evaluation manifests will be released upon acceptance.

## TL;DR

Robot demonstration learning requires accurate and temporally complete end-effector localization during close-range manipulation and camera occlusion. Existing SLAM benchmarks emphasize navigation motions, whereas manipulation datasets prioritize policy learning over localization evaluation.

## Related
<!-- [[other-paper-citekey]] -->
