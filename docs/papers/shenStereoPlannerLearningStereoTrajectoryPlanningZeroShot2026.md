---
citekey: "shenStereoPlannerLearningStereoTrajectoryPlanningZeroShot2026"
title: "Stereo-Planner: Learning Stereo-to-Trajectory Planning for Zero-Shot Sim-to-Real Quadrotor Navigation"
authors: ["Hongming Shen", "Junjie Lu", "Xun Chen", "Wei Wang", "Xinhang Xu", "Bailing Tian", "Lihua Xie"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.15560"
doi: "10.48550/arXiv.2610.15560"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Stereo-Planner: Learning Stereo-to-Trajectory Planning for Zero-Shot Sim-to-Real Quadrotor Navigation

> Hongming Shen, Junjie Lu, Xun Chen, Wei Wang, Xinhang Xu, Bailing Tian, Lihua Xie · 2026
> [arXiv](https://arxiv.org/abs/2610.15560) · [PDF](https://arxiv.org/pdf/2610.15560)

## Abstract

Existing navigation systems commonly rely on dedicated depth sensors or explicit depth reconstruction, while learning to generate trajectories directly from RGB images remains challenging due to the sim-to-real domain gap. In this work, we propose Stereo-Planner, an end-to-end vision-to-trajectory framework that enables zero-shot sim-to-real planning from stereo RGB observations. The key idea is to formulate trajectory generation as state- and scale-conditioned querying of latent stereo geometry. A Scene Representor incorporates a pretrained vision grounding foundation model to extract geometric cues shared across simulated and real-world environments, supporting generalization across visual domains. A lightweight Trajectory Decoder then translates these representations into trajectories through interleaved attention, separating trajectory-state interaction from scene-feature retrieval and incorporating the stereo baseline as a metric-scale cue. With these designs, Stereo-Planner is trained entirely on simulated data by minimizing differentiable trajectory costs and deployed directly in real-world environments without fine-tuning. Benchmark results demonstrate strong cross-scene generalization, with a 95% success rate in simulation environments at a commanded speed of 8 m/s, and competitive performance against depth-based planners using only stereo RGB observations for scene perception. Furthermore, deployment on a compact quadrotor equipped with an NVIDIA Orin NX enables autonomous flight at speeds of up to 7 m/s, with a mean onboard vision-to-action inference time of 24.27 ms. The software, simulation environments, and hardware designs will be open-sourced at https://github.com/Stereo-Planner/Stereo-Planner.

## TL;DR

Existing navigation systems commonly rely on dedicated depth sensors or explicit depth reconstruction, while learning to generate trajectories directly from RGB images remains challenging due to the sim-to-real domain gap. In this work, we propose Stereo-Planner, an end-to-end vision-to-trajectory framework that enables zero-shot sim-to-real planning from stereo RGB observations.

## Related
<!-- [[other-paper-citekey]] -->
