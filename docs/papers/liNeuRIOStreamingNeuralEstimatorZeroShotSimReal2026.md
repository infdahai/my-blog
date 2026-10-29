---
citekey: "liNeuRIOStreamingNeuralEstimatorZeroShotSimReal2026"
title: "NeuRIO: A Streaming Neural Estimator for Zero-Shot Sim-to-Real Multi-Robot Relative Inertial Odometry"
authors: ["Zhehan Li", "Jiadong Lu", "Shengwei Ren", "Chao Xu", "Yanjun Cao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21707"
doi: "10.48550/arXiv.2609.21707"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# NeuRIO: A Streaming Neural Estimator for Zero-Shot Sim-to-Real Multi-Robot Relative Inertial Odometry

> Zhehan Li, Jiadong Lu, Shengwei Ren, Chao Xu, Yanjun Cao · 2026
> [arXiv](https://arxiv.org/abs/2609.21707) · [PDF](https://arxiv.org/pdf/2609.21707)

## Abstract

We present NeuRIO, a streaming neural estimator for anchor-free 6-DoF relative inertial odometry using only identified inter-robot bearings, ranges, and IMU measurements. NeuRIO canonicalizes measurements into gravity-aligned coordinates, represents robots as nodes and mutual observations as factors, and uses attention for spatial reasoning and GRUs for temporal modeling. As a graph network, NeuRIO applies shared node-wise and factor-wise operators throughout the network, enabling it to handle different team sizes and time-varying observation graphs. NeuRIO is trained on a simulator that couples various motion patterns, device-level sensor characteristics, and diverse, realistic modeled, and temporally persistent sensor corruptions. In this way, NeuRIO achieves zero-shot sim-to-real transfer. Across $24$ real-world sequences, NeuRIO achieves $14.1\,\mathrm{cm}$ position RMSE and $3.9^\circ$ rotation RMSE. More importantly, NeuRIO demonstrates strong computational scalability, maintaining an update cost below $20\,\mathrm{ms}$ with up to $400$ robots in simulation, while optimization-based methods exceed $20\,\mathrm{ms}$ at only $24$ robots. Moreover, even trained on limited team sizes, NeuRIO transfers directly to unseen larger teams without architectural or parameter changes.

## TL;DR

We present NeuRIO, a streaming neural estimator for anchor-free 6-DoF relative inertial odometry using only identified inter-robot bearings, ranges, and IMU measurements. NeuRIO canonicalizes measurements into gravity-aligned coordinates, represents robots as nodes and mutual observations as factors, and uses attention for spatial reasoning and GRUs for temporal modeling.

## Related
<!-- [[other-paper-citekey]] -->
