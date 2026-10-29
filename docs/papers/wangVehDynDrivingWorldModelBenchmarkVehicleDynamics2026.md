---
citekey: "wangVehDynDrivingWorldModelBenchmarkVehicleDynamics2026"
title: "VehDyn: A Driving World Model Benchmark for Vehicle Dynamics"
authors: ["Tianyi Wang", "Wangsheng Du", "Jiazhou Chen", "Tianyi Zeng", "Xiangyu Li", "Jiseop Byeon", "Yujin Wang", "Yiming Xu", "Yangyang Wang", "Bingzhao Gao", "Sikai Chen", "Zhaomiao Guo", "Junfeng Jiao", "Christian Claudel", "Alexandre Bayen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33264"
doi: "10.48550/arXiv.2609.33264"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.ET", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# VehDyn: A Driving World Model Benchmark for Vehicle Dynamics

> Tianyi Wang, Wangsheng Du, Jiazhou Chen, Tianyi Zeng, Xiangyu Li, Jiseop Byeon, Yujin Wang, Yiming Xu, Yangyang Wang, Bingzhao Gao, Sikai Chen, Zhaomiao Guo, Junfeng Jiao, Christian Claudel, Alexandre Bayen · 2026
> [arXiv](https://arxiv.org/abs/2609.33264) · [PDF](https://arxiv.org/pdf/2609.33264)

## Abstract

Video world models are emerging as data engines, action planners, and generative simulators for autonomous driving, but existing benchmarks primarily assess visual fidelity and coarse physical plausibility, providing limited evidence on whether generated driving futures obey realistic vehicle kinematics and dynamics. This limitation is further compounded by the lack of datasets in which vehicle, road, maneuver, and speed conditions are independently controlled, and ground-truth vehicle states are recorded in synchrony with videos. We introduce VehDyn, a driving world model benchmark for vehicle dynamics. VehDyn is built on a CARLA-CarSim co-simulation platform where photorealistic rendering is coupled with a validated multi-body dynamics model, and it contains 10,080 configurations from a full factorial design over five vehicle types, four tire-road friction coefficients, three maneuvers, four target speeds, 14 scenes, and three illuminations, each paired with synchronized position, velocity, and attitude sequences. Built on this dataset, VehDyn introduces a hierarchical evaluation framework that measures trajectory alignment, kinematic consistency, and dynamic consistency, and benchmarks 12 state-of-the-art video world models. We further assess the video quality using two established protocols and correlate it with the VehDyn score. Trajectory-level metrics are nearly saturated, with ten of twelve models within 20\% of ground truth, while no model reaches 92\% of ground truth on dynamic consistency, and visual-quality metrics are only weakly correlated with vehicle-dynamics fidelity. DrivingWorld achieves the highest VehDyn score, followed by Cosmos 3 Nano and LTX-Video 2.5, and the VehDyn score agrees closely with human judgment. VehDyn provides a systematic foundation for developing driving world models that are physically consistent and visually realistic.

## TL;DR

Video world models are emerging as data engines, action planners, and generative simulators for autonomous driving, but existing benchmarks primarily assess visual fidelity and coarse physical plausibility, providing limited evidence on whether generated driving futures obey realistic vehicle kinematics and dynamics. This limitation is further compounded by the lack of datasets in which vehicle, road, maneuver, and speed conditions are independently controlled, and ground-truth vehicle states are recorded in synchrony with videos.

## Related
<!-- [[other-paper-citekey]] -->
