---
citekey: "wenRoboFin3DSimRealPlatformSurfaceFinishing2026"
title: "RoboFin3D: A Sim-to-Real Platform for Robotic Surface Finishing"
authors: ["Haowei Wen", "Shangtao Li", "Vaibhav Sanjay", "Philip Huang", "Jiaoyang Li", "Changliu Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.37560"
doi: "10.48550/arXiv.2609.37560"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# RoboFin3D: A Sim-to-Real Platform for Robotic Surface Finishing

> Haowei Wen, Shangtao Li, Vaibhav Sanjay, Philip Huang, Jiaoyang Li, Changliu Liu · 2026
> [arXiv](https://arxiv.org/abs/2609.37560) · [PDF](https://arxiv.org/pdf/2609.37560)

## Abstract

Grinding and sanding are fundamental processes in industrial robotic surface finishing. However, physical trials are expensive and consume workpieces, making reproducible experiments difficult. We present RoboFin3D, a sim-to-real platform built on Isaac Sim and the Newton physics engine, that provides physics-based grinding and sanding simulation for cheap and repeatable robotic surface finishing experiments. RoboFin3D utilizes a signed distance field (SDF) to model the changing geometry of the workpiece, enabling contact computation, live updates and rendering without an intermediate mesh. It additionally uses a separate surface field to model progressive surface appearance change during sanding. We also introduce WeldGen, a weld sampling module, to generate weld beads on 8,918 real-world workpiece meshes for providing diverse simulation assets. The simulation parameters are calibrated on real experimental results and our evaluation demonstrates our simulation's fidelity against the real world. We also demonstrate that simulation-generated data can be used to improve the performance of perception models. Simulation-only fine-tuning of SAM2 improves IoU for segmentation of unsanded regions from 77.15% to 84.47%, while combined synthetic and real training reaches 97.41%.

## TL;DR

Grinding and sanding are fundamental processes in industrial robotic surface finishing. However, physical trials are expensive and consume workpieces, making reproducible experiments difficult.

## Related
<!-- [[other-paper-citekey]] -->
