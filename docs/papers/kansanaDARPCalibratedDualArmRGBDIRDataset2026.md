---
citekey: "kansanaDARPCalibratedDualArmRGBDIRDataset2026"
title: "DARP: A Calibrated Dual-Arm RGB-D-IR Dataset for Multi-View Robotic Perception"
authors: ["Manish Kansana", "Mohammed Yusuf Mujawar", "Sudip Mittal", "Shahram Rahimi", "Noorbakhsh Amiri Golilarz"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.31002"
doi: "10.48550/arXiv.2608.31002"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-04
---

# DARP: A Calibrated Dual-Arm RGB-D-IR Dataset for Multi-View Robotic Perception

> Manish Kansana, Mohammed Yusuf Mujawar, Sudip Mittal, Shahram Rahimi, Noorbakhsh Amiri Golilarz · 2026
> [arXiv](https://arxiv.org/abs/2608.31002) · [PDF](https://arxiv.org/pdf/2608.31002)

## Abstract

Robotic perception from a single viewpoint is often limited by self-occlusion and incomplete surface visibility. This paper presents DARP(Dual-Arm Robotic Perception) https://doi.org/10.21227/rmv3-be47, a calibrated dual-arm RGB-D-IR dataset for object-centered robotic perception using two independently moving eye-in-hand manipulators positioned on opposite sides of a shared tabletop workspace. Each arm carries an Intel RealSense sensor that continuously records RGB, depth, and stereo infrared data while synchronized robot joint states are logged for pose recovery. Objects are placed without fixed poses or marked locations, and the acquisition procedure performs automatic localization, cross-arm confirmation, adaptive viewpoint generation, and continuous multimodal recording. DARP contains ten unique tabletop objects and preserves the original sensor recordings, robot-state logs, object-level metadata, and calibration information required to reconstruct camera trajectories in a shared metric frame. To evaluate the geometric consistency of the acquisition, we implement a deterministic multi-view fusion pipeline that converts calibrated RGB-D observations into complementary partial point clouds and measured surface meshes without using learned or generative completion methods. Evaluation on 224 held-out RGB-D keyframes comprising 1,563,466 three-dimensional query points yields a median point-to-mesh distance of 2.13~mm and an RMSE of 4.04~mm, with 96.56\% of points within 10~mm of the measured-surface mesh. DARP is intended as a reusable resource for multi-view reconstruction, collaborative robotic perception, multimodal fusion, active perception, and future learning-based reasoning over partial object observations.

## TL;DR

Robotic perception from a single viewpoint is often limited by self-occlusion and incomplete surface visibility. This paper presents DARP(Dual-Arm Robotic Perception) https://doi.org/10.21227/rmv3-be47, a calibrated dual-arm RGB-D-IR dataset for object-centered robotic perception using two independently moving eye-in-hand manipulators positioned on opposite sides of a shared tabletop workspace.

## Related
<!-- [[other-paper-citekey]] -->
