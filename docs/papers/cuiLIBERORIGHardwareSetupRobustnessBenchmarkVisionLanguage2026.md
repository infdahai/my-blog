---
citekey: "cuiLIBERORIGHardwareSetupRobustnessBenchmarkVisionLanguage2026"
title: "LIBERO-RIG: A Hardware-Setup Robustness Benchmark for Vision-Language-Action Models"
authors: ["Andrea Yaoyun Cui", "Hanyu Wang", "Xinyi Wang", "Bangzheng Li", "Lin Zhang", "Zhenggang Tang", "Shyamal Buch", "Dejia Xu", "Matthew Tancik"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.18843"
doi: "10.48550/arXiv.2610.18843"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# LIBERO-RIG: A Hardware-Setup Robustness Benchmark for Vision-Language-Action Models

> Andrea Yaoyun Cui, Hanyu Wang, Xinyi Wang, Bangzheng Li, Lin Zhang, Zhenggang Tang, Shyamal Buch, Dejia Xu, Matthew Tancik · 2026
> [arXiv](https://arxiv.org/abs/2610.18843) · [PDF](https://arxiv.org/pdf/2610.18843)

## Abstract

Robot policies are expected to generalize across deployment environments, including variations in the robot itself: cameras are bumped and remounted, calibrations drift, controllers run at different rates, and end-effector pads wear down. We present LIBERO-RIG, a benchmark that perturbs only the robot's hardware and setup while holding every LIBERO task fixed. The benchmark spans eleven perturbation axes, including camera mounting and optics, camera-to-arm calibration, actuation gain, control rate, proprioceptive noise, base pose, table height, and gripper pads. Each axis has five severity levels, yielding 210 conditions across the four LIBERO suites. We evaluate nine recent vision-language-action models using 500 episodes per condition and substantiate each finding with rigorous statistical tests. Pooled success falls from 0.932 to 0.767 at the middle severity and 0.509 at the highest severity. Performance degradation varies substantially across perturbation axes and action interfaces, and training on visual perturbations does not mitigate faults that leave camera images unchanged. We release the benchmark together with manifests specifying the fixed perturbation parameters for each episode.

## TL;DR

Robot policies are expected to generalize across deployment environments, including variations in the robot itself: cameras are bumped and remounted, calibrations drift, controllers run at different rates, and end-effector pads wear down. We present LIBERO-RIG, a benchmark that perturbs only the robot's hardware and setup while holding every LIBERO task fixed.

## Related
<!-- [[other-paper-citekey]] -->
