---
citekey: "mukherjeeResilientDecentralizedRadarLiDARInertialOdometryChallengingSubterranean2026"
title: "Resilient Decentralized Radar-LiDAR-Inertial Odometry in Challenging Subterranean Environments"
authors: ["Moumita Mukherjee", "Avijit Banerjee", "Anton Koval", "George Nikolakopoulos"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.35363"
doi: "10.48550/arXiv.2610.35363"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# Resilient Decentralized Radar-LiDAR-Inertial Odometry in Challenging Subterranean Environments

> Moumita Mukherjee, Avijit Banerjee, Anton Koval, George Nikolakopoulos · 2026
> [arXiv](https://arxiv.org/abs/2610.35363) · [PDF](https://arxiv.org/pdf/2610.35363)

## Abstract

Accurate localization in GPS-denied and visually degraded environments affected by smoke, dust, or fog remains a critical challenge for autonomous systems. While LiDAR provides high-resolution spatial perception, its performance deteriorates under particulate occlusion. In contrast, frequency-modulated continuous-wave (FMCW) radar offers robustness under such conditions but suffers from sparse measurements and outliers. This article presents a resilient decentralized LiDAR Radar Inertial Odometry (LRIO) framework that fuses the complementary strengths of LiDAR, radar, and inertial sensing to achieve robust pose estimation in challenging subterranean environments. At the core of the framework is an Adaptive Residual Thresholding (ART) mechanism that autonomously detects temporal sensor degradation and selectively adjusts the fusion process to minimize unreliable measurements. Building on this, a Robust Error-Tolerant Optimal Information Filter (RETOIF) is employed within a decentralized fusion architecture to integrate LiDAR-inertial and multiple radar-inertial odometry estimates in a fault-aware manner, enhancing resilience to environmental disturbances and intermittent sensor failures. The proposed framework is evaluated using real-world sensor data collected in GPS-denied subterranean tunnels under smoke-free and smoke-degraded conditions. In the smoke-free experiment, the proposed RETOIF framework achieves a root mean square localization error (RMSE) of 2.1733, compared with 2.9929 for the conventional centralized LRIO approach, corresponding to a 27.4\% reduction in RMSE. Experimental results further demonstrate the framework's ability to maintain pose estimation under smoke-induced sensor degradation, highlighting its potential for resilient autonomous navigation and mapping in challenging subterranean environments.

## TL;DR

Accurate localization in GPS-denied and visually degraded environments affected by smoke, dust, or fog remains a critical challenge for autonomous systems. While LiDAR provides high-resolution spatial perception, its performance deteriorates under particulate occlusion.

## Related
<!-- [[other-paper-citekey]] -->
