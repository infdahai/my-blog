---
citekey: "wangAligned3DGaussianSplattingPreciseReachingWristCamera2026"
title: "Robot-Aligned 3D Gaussian Splatting for Precise Reaching with Wrist-Camera VLA Policies"
authors: ["Zuoxu Wang", "Xiao Liang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.35626"
doi: "10.48550/arXiv.2610.35626"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# Robot-Aligned 3D Gaussian Splatting for Precise Reaching with Wrist-Camera VLA Policies

> Zuoxu Wang, Xiao Liang · 2026
> [arXiv](https://arxiv.org/abs/2610.35626) · [PDF](https://arxiv.org/pdf/2610.35626)

## Abstract

Efficient robotic data collection remains a major bottleneck for vision-language-action (VLA) policy learning, especially for tasks requiring accurate end-effector positioning and camera-action alignment. This challenge is particularly severe in electronic-waste disassembly, where robots operate in cluttered assemblies of densely packed, visually similar components. Full digital-twin simulation is difficult because many parts are thin, reflective, or mechanically complex, making accurate object-level meshes and contact models difficult to obtain. In this work, we focus on pre-contact reaching and propose a 3D Gaussian Splatting (3DGS)-based data generation pipeline for wrist-camera VLA adaptation. Our method reconstructs the real workspace with 3DGS and renders diverse wrist-camera observations from robot-aligned poses. These observations are paired with smooth, structured reaching trajectories to provide robot-aligned visual-action supervision for VLA fine-tuning. We further augment the VLA policy with an instruction-conditioned reach verifier that estimates target proximity and provides reliable termination before physical interaction. Experiments in motherboard disassembly demonstrate precise VLA-based reaching using wrist-camera observations alone, without an external side-view camera. With $π$0.5, 1,500 generated trajectories achieve 80.0\% precise-reaching success across three targets, compared with 58.7\% using 150 teleoperated demonstrations, while requiring less than 10 minutes of active human capture. Project website: https://001-wang.github.io/PrecisionReach-GS/

## TL;DR

Efficient robotic data collection remains a major bottleneck for vision-language-action (VLA) policy learning, especially for tasks requiring accurate end-effector positioning and camera-action alignment. This challenge is particularly severe in electronic-waste disassembly, where robots operate in cluttered assemblies of densely packed, visually similar components.

## Related
<!-- [[other-paper-citekey]] -->
