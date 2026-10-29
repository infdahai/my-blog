---
citekey: "diuzhevMCDeTraMotionConsistentJointObjectDetectionSocially2026"
title: "MC-DeTra: Motion-Consistent Joint Object Detection and Socially-Aware Trajectory Forecasting in Bird's-Eye-View Images"
authors: ["Vladislav Diuzhev", "Dmitry Yudin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11717"
doi: "10.48550/arXiv.2609.11717"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# MC-DeTra: Motion-Consistent Joint Object Detection and Socially-Aware Trajectory Forecasting in Bird's-Eye-View Images

> Vladislav Diuzhev, Dmitry Yudin · 2026
> [arXiv](https://arxiv.org/abs/2609.11717) · [PDF](https://arxiv.org/pdf/2609.11717)

## Abstract

Unified models for object detection and trajectory forecasting aim to merge perception and prediction for autonomous driving, refining actor trajectories directly over shared bird's-eye-view (BEV) images rasterized from LiDAR and high-definition maps. Their accuracy on dynamic, moving actors, however, remains the hardest part of the task, and the strongest such model, DeTra, has no public implementation. We contribute an openly released DeTra reimplementation with documented approximations, and on top of it MC-DeTra: a family of motion-consistency mechanisms that add supervision through two annotation-derived auxiliary signals -- each actor's observed past motion and the occupancy of the surrounding traffic that forms its social context -- and one inter-output consistency constraint that aligns an actor's predicted heading with its predicted direction of motion. Every proposed loss is train-only and inference-safe: it shapes the shared BEV representation during training and is removed at test time, adding no inference latency. On the Waymo Open Dataset, evaluated under a strict, detection-conditioned forecasting protocol, MC-DeTra improves dynamic, socially-situated trajectory forecasting while preserving or improving detection accuracy; a gradient-based loss-calibration analysis exposes how the auxiliary objectives compete at the shared backbone, and our ablation identifies which signals contribute most. We release code, configurations, and evaluation tooling at https://github.com/diuzhevVlad/MC-DeTra.

## TL;DR

Unified models for object detection and trajectory forecasting aim to merge perception and prediction for autonomous driving, refining actor trajectories directly over shared bird's-eye-view (BEV) images rasterized from LiDAR and high-definition maps. Their accuracy on dynamic, moving actors, however, remains the hardest part of the task, and the strongest such model, DeTra, has no public implementation.

## Related
<!-- [[other-paper-citekey]] -->
