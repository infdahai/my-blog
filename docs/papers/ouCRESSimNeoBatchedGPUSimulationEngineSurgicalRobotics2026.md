---
citekey: "ouCRESSimNeoBatchedGPUSimulationEngineSurgicalRobotics2026"
title: "CRESSim-Neo: A Batched GPU Simulation Engine for Surgical Robotics and Robot Learning"
authors: ["Yafei Ou", "Ahnaf Naheen", "Tleukhan Mussin", "Hans Jarales", "Melwin Moncy", "Mahdi Tavakoli"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25192"
doi: "10.48550/arXiv.2608.25192"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# CRESSim-Neo: A Batched GPU Simulation Engine for Surgical Robotics and Robot Learning

> Yafei Ou, Ahnaf Naheen, Tleukhan Mussin, Hans Jarales, Melwin Moncy, Mahdi Tavakoli · 2026
> [arXiv](https://arxiv.org/abs/2608.25192) · [PDF](https://arxiv.org/pdf/2608.25192)

## Abstract

We introduce CRESSim-Neo, a batched GPU simulation engine for surgical robotics and robot learning. CRESSim-Neo combines position-based simulation of rigid bodies, deformable tissues, fluids, and strands with batched rendering, surgery-specific sensing, and a GPU-resident data pipeline. The engine supports applications including tissue manipulation, fluid suction, suturing, cable-driven robots, and ultrasound image synthesis. Direct access to physics and rendering buffers enables GPU-resident robot learning and zero-copy PyTorch integration using DLPack. We demonstrate CRESSim-Neo across rigid-body, deformable-body, and fluid simulation tasks, including vision-based and surgical robot-learning scenarios. On an NVIDIA RTX 4090, the engine achieves up to 2.03 million environment steps per second for 8192 parallel CartPole environments, and scales to batched surgical scenarios involving tissue deformation, fluid interaction, and ultrasound sensing. Overall, CRESSim-Neo provides a unified and scalable platform for surgical simulation, synthetic data generation, and surgical robot learning.

## TL;DR

We introduce CRESSim-Neo, a batched GPU simulation engine for surgical robotics and robot learning. CRESSim-Neo combines position-based simulation of rigid bodies, deformable tissues, fluids, and strands with batched rendering, surgery-specific sensing, and a GPU-resident data pipeline.

## Related
<!-- [[other-paper-citekey]] -->
