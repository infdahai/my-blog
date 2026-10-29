---
citekey: "liuAdversarialCalibrationAttackAutonomousVehicles2026"
title: "Adversarial Calibration Attack on Autonomous Vehicles"
authors: ["Liangkai Liu", "Qingzhao Zhang", "Kang G. Shin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28778"
doi: "10.48550/arXiv.2608.28778"
tags: [paper, embodied-ai, "cs.CV", "cs.ET", "cs.LG", "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-09-02
---

# Adversarial Calibration Attack on Autonomous Vehicles

> Liangkai Liu, Qingzhao Zhang, Kang G. Shin · 2026
> [arXiv](https://arxiv.org/abs/2608.28778) · [PDF](https://arxiv.org/pdf/2608.28778)

## Abstract

Autonomous vehicles (AVs) rely on accurate camera-LiDAR calibration for multimodal sensor fusion. In practice, calibration can drift due to vibration, temperature variation, or minor sensor displacement, motivating online calibration algorithms that detect and correct misalignment at runtime while allowing the vehicle to continue operating without a factory visit. Existing AV attacks largely assume correct calibration. We instead identify online sensor calibration as a new attack plane. A corrupted calibration update can persist across subsequent fusion operations, causing system-wide errors that propagate from perception to planning and control. We present Adversarial Calibration Attack (ACA), the first physical attack against camera-LiDAR online calibration. Using a single adversarial poster, ACA first spoofs the miscalibration detector to trigger the calibration process and then steers the calibration estimator toward an incorrect transformation. A unified optimization jointly designs the poster's geometry and texture for both objectives. We evaluate ACA across benchmark datasets, simulation, and physical experiments. On benchmark datasets such as KITTI and nuScenes, ACA induces up to 33.9 degrees mean rotational calibration error, thereby severely degrading object detection. In the CARLA simulator, the attack causes a collision when the corrupted calibration is accepted in vulnerable scenarios crafted by the attacker. On a real Husky robot, a printed adversarial poster successfully reproduces the calibration error. These results demonstrate that online calibration is a practical and safety-critical attack surface for AVs.

## TL;DR

Autonomous vehicles (AVs) rely on accurate camera-LiDAR calibration for multimodal sensor fusion. In practice, calibration can drift due to vibration, temperature variation, or minor sensor displacement, motivating online calibration algorithms that detect and correct misalignment at runtime while allowing the vehicle to continue operating without a factory visit.

## Related
<!-- [[other-paper-citekey]] -->
