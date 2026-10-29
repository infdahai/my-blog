---
citekey: "kimMarsLabMartianRoverSimulatorPlanetaryRoverAutonomousNavigation2026"
title: "MarsLab: A Martian Rover Simulator for Planetary Rover Autonomous Navigation"
authors: ["Hoyun Kim", "Beomsu Kim", "Giseop Kim"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34702"
doi: "10.48550/arXiv.2609.34702"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# MarsLab: A Martian Rover Simulator for Planetary Rover Autonomous Navigation

> Hoyun Kim, Beomsu Kim, Giseop Kim · 2026
> [arXiv](https://arxiv.org/abs/2609.34702) · [PDF](https://arxiv.org/pdf/2609.34702)

## Abstract

Future Mars missions will require rover autonomy that can operate across unstructured terrain, changing illumination, atmospheric dust, and limited communication. Simulation is a practical way to study these conditions before deployment, but existing Mars-relevant resources differ in scope, including mission-oriented simulators, fixed analog datasets, task-specific environments, and open robotics interfaces. In this context, we present MarsLab, an open-source, ROS2-native Mars rover simulator for autonomy and navigation algorithm development. MarsLab combines HiRISE-derived and procedural terrain with customizable rock, crater, solar-illumination, and atmospheric-dust settings, and runs a Perseverance-class rover model in NVIDIA Isaac Sim. The runtime publishes RGB, depth, RGB-D point clouds, LiDAR, IMU, wheel odometry, and Ground Truth (GT) pose data through standard ROS2 topics. We demonstrate MarsLab with Simultaneous Localization and Mapping (SLAM) benchmarks across sensing modalities, dust levels, scene geometry, and route length, and with Visual Place Recognition (VPR) benchmarks over repeated Mars Base traversals under illumination and dust changes. The results illustrate how controlled scene variation and shared GT trajectories can be used to compare trajectory-level estimation and image-level place recognition within the same simulator. Our Project Page: https://kimhoyun-robotair.github.io/MarsLab/.

## TL;DR

Future Mars missions will require rover autonomy that can operate across unstructured terrain, changing illumination, atmospheric dust, and limited communication. Simulation is a practical way to study these conditions before deployment, but existing Mars-relevant resources differ in scope, including mission-oriented simulators, fixed analog datasets, task-specific environments, and open robotics interfaces.

## Related
<!-- [[other-paper-citekey]] -->
