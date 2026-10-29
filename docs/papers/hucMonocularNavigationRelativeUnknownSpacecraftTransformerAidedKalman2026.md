---
citekey: "hucMonocularNavigationRelativeUnknownSpacecraftTransformerAidedKalman2026"
title: "Monocular Navigation Relative to Unknown Spacecraft Using a Transformer-Aided Kalman Filter"
authors: ["Pol Francesch Huc", "Simone D'Amico"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07231"
doi: "10.48550/arXiv.2610.07231"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Monocular Navigation Relative to Unknown Spacecraft Using a Transformer-Aided Kalman Filter

> Pol Francesch Huc, Simone D'Amico · 2026
> [arXiv](https://arxiv.org/abs/2610.07231) · [PDF](https://arxiv.org/pdf/2610.07231)

## Abstract

This work presents a novel learning-based pipeline for pose estimation of unknown spacecraft using only monocular images from a single servicer. The approach combines a transformer-based neural network with a Multi-State Constraint Kalman Filter (MSCKF) to estimate the pose (i.e., position and orientation of the target spacecraft relative to the camera) throughout rendezvous and proximity operations. Unlike existing vision-based methods that require prior knowledge of the target shape or inertia properties, rely on additional sensing modalities such as depth, lidar, or stereo, or only recover translation up to scale, the proposed pipeline generalizes to previously unseen spacecraft using a single monocular camera. The transformer network estimates the odometry, the change in pose between images up to scale, from SuperPoint features matched by LightGlue. The MSCKF uses these pseudo-measurements along with an orbit and attitude kinematics model to estimate the pose of the target. In particular, the relative orbit elements, the target's attitude with respect to the servicer's camera, and the associated angular velocity are estimated directly by the filter. Given the monocular approach and short distance to the target, the full observability of the range to the target is recovered via attitude maneuvers by the servicer. The method is trained and evaluated on a re-rendered high-resolution version of the SPE3R dataset, which includes synthetic images of 103 spacecraft. Eleven of these spacecraft are held out during training to evaluate the generalization to unseen targets. Monte Carlo simulations are then used to evaluate the navigation pipeline on rendered trajectories of the held out spacecraft. The results demonstrate that learned vision pipelines as a front-end for Kalman filters provide median errors of 3.7{\deg} in attitude and 2.2% of range in ROE when navigating about unknown targets.

## TL;DR

This work presents a novel learning-based pipeline for pose estimation of unknown spacecraft using only monocular images from a single servicer. The approach combines a transformer-based neural network with a Multi-State Constraint Kalman Filter (MSCKF) to estimate the pose (i.e., position and orientation of the target spacecraft relative to the camera) throughout rendezvous and proximity operations.

## Related
<!-- [[other-paper-citekey]] -->
