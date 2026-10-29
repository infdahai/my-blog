---
citekey: "castillaarquilloMAREOpenSourceLunarRoverSimulatorShadowGround2026"
title: "MARE: An Open-Source Lunar Rover Simulator with Shadow Ground Truth for Perception and Autonomy"
authors: ["Raúl Castilla-Arquillo", "Miguel Olivares-Mendez"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28465"
doi: "10.48550/arXiv.2610.28465"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# MARE: An Open-Source Lunar Rover Simulator with Shadow Ground Truth for Perception and Autonomy

> Raúl Castilla-Arquillo, Miguel Olivares-Mendez · 2026
> [arXiv](https://arxiv.org/abs/2610.28465) · [PDF](https://arxiv.org/pdf/2610.28465)

## Abstract

Lunar surface exploration increasingly relies on autonomous rovers that must perceive and traverse unstructured terrain under extreme illumination conditions. Near the lunar poles, low sun elevations produce long, high-contrast shadows that challenge stereo vision, terrain segmentation, and localization. Developing perception and navigation algorithms for these conditions requires large amounts of sensor data with accurate ground truth, which field campaigns and analog facilities can only provide at high cost and with limited variety. This paper presents MARE (Modular Autonomy and Rendering Environment), an open-source simulation suite for lunar rover perception and autonomy built on Unreal Engine 5 and ROS 2. MARE consists of three integrated components. Terrain Studio generates cratered and rocky lunar Digital Elevation Maps (DEMs) to build simulation scenes. A dedicated Unreal Engine project hosts two physics-based rovers with plugins for stereo, lidar, event, and Single-Photon Avalanche Diode (SPAD) cameras, streaming time-stamped sensor data and pixel-accurate ground truth. Lastly, a Guidance, Navigation, and Control (GNC) stack provides web-based mission control. Validation shows a mean Intersection over Union (IoU) of 0.79 between predicted and rendered shadows at low sun elevations, and stereo depth analysis verifies decreased pixel coverage in shadowed regions relative to sunlit terrain.

## TL;DR

Lunar surface exploration increasingly relies on autonomous rovers that must perceive and traverse unstructured terrain under extreme illumination conditions. Near the lunar poles, low sun elevations produce long, high-contrast shadows that challenge stereo vision, terrain segmentation, and localization.

## Related
<!-- [[other-paper-citekey]] -->
