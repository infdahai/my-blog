---
citekey: "zhangYOCOYouOnlyCalibrateOnceFastMocapCalibration2026"
title: "YOCO: You Only Calibrate Once! Fast Mocap Calibration for Dexterous Teleoperation"
authors: ["Yu Zhang", "Yunqi Li", "Yushi Du", "Yi Ma", "Yanchao Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.11657"
doi: "10.48550/arXiv.2610.11657"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# YOCO: You Only Calibrate Once! Fast Mocap Calibration for Dexterous Teleoperation

> Yu Zhang, Yunqi Li, Yushi Du, Yi Ma, Yanchao Yang · 2026
> [arXiv](https://arxiv.org/abs/2610.11657) · [PDF](https://arxiv.org/pdf/2610.11657)

## Abstract

Dexterous teleoperation requires reliable human-hand state estimations. However, common low-cost motion-capture gloves and markerless trackers often exhibit biases that vary across users, glove fit, and recording sessions, degrading retargeting and demonstration quality. We present YOCO, a fast few-shot, fine-tuning-free calibration framework that corrects biased hand-pose streams from a small set of paired raw and target poses. Instead of optimizing a separate model for every operator or session, YOCO conditions a calibration HyperNet on the paired examples and predicts LoRA-style updates for a frozen MANO hand-estimation module, turning per-user calibration into a lightweight feed-forward adaptation step while preserving the geometric prior of MANO and the efficiency of a compact estimator. We train YOCO with synthetic drift augmentations on InterHand2.6M and evaluate on augmented InterHand sequences, offline real glove data, and dexterous teleoperation tasks. Across these settings, YOCO improves calibration efficiency, hand-state estimation quality and teleoperation performance compared with uncalibrated input and standard calibration baselines.

## TL;DR

Dexterous teleoperation requires reliable human-hand state estimations. However, common low-cost motion-capture gloves and markerless trackers often exhibit biases that vary across users, glove fit, and recording sessions, degrading retargeting and demonstration quality.

## Related
<!-- [[other-paper-citekey]] -->
