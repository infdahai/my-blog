---
citekey: "huangUNRIOUncertaintyAwareVelocityLearningRadarInertialOdometry2026"
title: "UNRIO: Uncertainty-Aware Velocity Learning for Radar-Inertial Odometry"
authors: ["Jui-Te Huang", "Tianshu Huang", "Anthony Rowe", "Michael Kaess"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2604.13584"
doi: "10.48550/arXiv.2604.13584"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# UNRIO: Uncertainty-Aware Velocity Learning for Radar-Inertial Odometry

> Jui-Te Huang, Tianshu Huang, Anthony Rowe, Michael Kaess · 2026
> [arXiv](https://arxiv.org/abs/2604.13584) · [PDF](https://arxiv.org/pdf/2604.13584)

## Abstract

mmWave radars are robust to darkness and occlusions such as dust and smoke, and can directly constrain ego-velocity from a single frame via Doppler measurements, making them attractive sensors for odometry in visually denied conditions. However, almost all existing radar-inertial odometry systems rely on lossy radar point clouds that are highly sparse, generally concentrated in a narrow angular band, and aliased at high speeds. We propose to instead estimate ego-velocity directly from unfiltered mmWave I/Q signals. Taking advantage of a foundation model for 4D radar spectrum, we develop a system that integrates uncertainty-aware velocity predictions with IMU measurements using an uncertainty-weighted sliding-window pose graph to accurately compute odometry even when provided radar data with aliasing or an unfavorable field of view. Evaluated on public benchmark datasets, our system, UNRIO, attains the lowest relative pose error on the majority of sequences across held-out environments, despite differing chirp configurations, motion patterns, and platforms with its strongest gains coming where point clouds fail most: lateral motion in IQ1M and heavily aliased Doppler in ColoRadar.

## TL;DR

mmWave radars are robust to darkness and occlusions such as dust and smoke, and can directly constrain ego-velocity from a single frame via Doppler measurements, making them attractive sensors for odometry in visually denied conditions. However, almost all existing radar-inertial odometry systems rely on lossy radar point clouds that are highly sparse, generally concentrated in a narrow angular band, and aliased at high speeds.

## Related
<!-- [[other-paper-citekey]] -->
