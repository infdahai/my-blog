---
citekey: "zhangSpacecraftPoseTrackingKinematicPredictionSelectiveEventCorrection2026"
title: "Spacecraft Pose Tracking via Kinematic Prediction and Selective Event Correction"
authors: ["Yonglong Zhang", "Guanning Yao", "Shuo Zhang", "Yifan Yang", "Yang Liu{\\dag}", "Zongwu Xie"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19465"
doi: "10.48550/arXiv.2610.19465"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Spacecraft Pose Tracking via Kinematic Prediction and Selective Event Correction

> Yonglong Zhang, Guanning Yao, Shuo Zhang, Yifan Yang, Yang Liu{\dag}, Zongwu Xie · 2026
> [arXiv](https://arxiv.org/abs/2610.19465) · [PDF](https://arxiv.org/pdf/2610.19465)

## Abstract

In initialized spacecraft tracking, a short-horizon motion prediction remains available as event support changes. Observation-Aligned Event Innovation (OA-EI) uses events to correct selected components of this prediction. A constant-body-twist model propagates the complete pose; the event encoder proposes rotational and normalized image-plane translation corrections, retaining propagated axial depth. Candidate magnitudes come from a bounded Scale Gate and a deterministic activity factor, with empty windows returning the prediction unchanged. Evaluation uses four FRESH physical-event trajectories, twenty rollout starts, and three training seeds. Each rollout starts from two reference poses and then uses self-estimates. At 7.7 seconds, rotation and translation errors fall from 41.63{\deg}/57.28 mm for prediction alone to 15.73{\deg}/22.41 mm for OA-EI, reductions of 62.2% and 60.9%. Failure rates fall from 20.0% to 1.67%. Matched ablations favor the rotation-bearing interface for overall pose accuracy; combining scaling with activity support gives the lowest errors at every tested event-retention level. On Jetson Orin Nano, the measured in-memory update takes 44.56 milliseconds at the median and 58.77 milliseconds at P95.

## TL;DR

In initialized spacecraft tracking, a short-horizon motion prediction remains available as event support changes. Observation-Aligned Event Innovation (OA-EI) uses events to correct selected components of this prediction.

## Related
<!-- [[other-paper-citekey]] -->
