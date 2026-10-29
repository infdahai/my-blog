---
citekey: "sarkarTreadVisuoInertialFrameworkTerrainLocomotionContextAware2026"
title: "Tread: A Visuo-Inertial Framework for Terrain and Locomotion Context-Aware Gait-Phase and Speed Estimation in Wearable Robotics"
authors: ["Debadrata Sarkar", "Akash Bachhar", "Aman Arora"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19067"
doi: "10.48550/arXiv.2610.19067"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Tread: A Visuo-Inertial Framework for Terrain and Locomotion Context-Aware Gait-Phase and Speed Estimation in Wearable Robotics

> Debadrata Sarkar, Akash Bachhar, Aman Arora · 2026
> [arXiv](https://arxiv.org/abs/2610.19067) · [PDF](https://arxiv.org/pdf/2610.19067)

## Abstract

A wearable assistive robot must continuously estimate terrain, locomotion mode, gait phase, and walking speed. These quantities are commonly addressed by separate, terrain-specific models, with datasets rarely collected under a common protocol. This paper presents a visuo-inertial framework that connects these estimates through a causal pipeline using a chest-mounted camera and four lower-limb inertial measurement units (IMUs). Anticipatory Terrain Perception (ATP) classifies incoming terrain with 96.3% accuracy and anticipates terrain transitions by 1.46 s on average. Terrain-Aware Locomotion Mode Identification (TALMI) achieves 93.7% and 98.8% accuracy for its level-ground and stairs experts respectively, with mean transition latencies being below 200 ms. The relevant TALMI posterior is retained as a Probabilistic Locomotion Context (PLC) vector and provided to a shared Gait Kinematic Encoder (GKE), which supports 50-Hz bilateral gait-phase estimation and 2-Hz walking-speed estimation. Leave-one-subject-out evaluation yields gait-phase RMSEs of 1.75%, 2.97%, and 4.55% for level walking, stair ascent, and stair descent respectively while estimating speed over 3.5-5.5 km/h with a RMSE of 0.218 km/h. All inertial sensing based models use sensor-fused Euler angles as input rather than raw accelerometer and gyroscope signals, reducing dependence on sensor mounting variation.

## TL;DR

A wearable assistive robot must continuously estimate terrain, locomotion mode, gait phase, and walking speed. These quantities are commonly addressed by separate, terrain-specific models, with datasets rarely collected under a common protocol.

## Related
<!-- [[other-paper-citekey]] -->
