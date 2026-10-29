---
citekey: "eschmannHyperDroneSimulationRealityTransferMillionsFramesPerSecond2026"
title: "HyperDrone: Simulation-to-Reality Transfer at Millions of Frames per Second"
authors: ["Jonas Eschmann", "Giuseppe Loianno"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28950"
doi: "10.48550/arXiv.2610.28950"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-10-24
---

# HyperDrone: Simulation-to-Reality Transfer at Millions of Frames per Second

> Jonas Eschmann, Giuseppe Loianno · 2026
> [arXiv](https://arxiv.org/abs/2610.28950) · [PDF](https://arxiv.org/pdf/2610.28950)

## Abstract

We present HyperDrone, an extremely fast quadrotor simulator focused on high-performance batch rendering that is more than 20x faster than existing state-of-the-art batch quadrotor simulators. HyperDrone combines highly optimized multirotor dynamics with HyperLux, a new ray-tracing engine that supports Nvidia OptiX, Vulkan, Apple Metal and WebGPU backends that takes full advantage of modern ray-tracing hardware, capable of running both components entirely on the GPU. HyperLux renders RGB, depth, semantic/instance segmentation, surface normals and optical flow observations at configurable levels of fidelity, including reflections, realistic lighting, motion blur, anti-aliasing, and Physically Based Rendering (PBR). Even in the highest-fidelity settings, HyperLux achieves millions of Frames Per Second (FPS) on consumer-grade GPUs while rendering realistic 3D scenes. We demonstrate the merits of HyperDrone by training a vision-based yaw-control policy purely in simulation and transferring it to a real small-scale quadrotor (Crazyflie) with a camera, running completely onboard.

## TL;DR

We present HyperDrone, an extremely fast quadrotor simulator focused on high-performance batch rendering that is more than 20x faster than existing state-of-the-art batch quadrotor simulators. HyperDrone combines highly optimized multirotor dynamics with HyperLux, a new ray-tracing engine that supports Nvidia OptiX, Vulkan, Apple Metal and WebGPU backends that takes full advantage of modern ray-tracing hardware, capable of running both components entirely on the GPU.

## Related
<!-- [[other-paper-citekey]] -->
