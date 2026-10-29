---
citekey: "caoHuMiTLowLatencyWholeBodyHumanoidTeleoperationCompact2026"
title: "HuMiT: Low-Latency Whole-Body Humanoid Teleoperation via Compact Reference Tracking"
authors: ["Liu Cao", "Botian Xu", "Ruoqu Chen", "Jiajun Liu", "Mingzhi Pei", "Zihao Wang", "Zhongyu Li", "Mengdi Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29903"
doi: "10.48550/arXiv.2610.29903"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# HuMiT: Low-Latency Whole-Body Humanoid Teleoperation via Compact Reference Tracking

> Liu Cao, Botian Xu, Ruoqu Chen, Jiajun Liu, Mingzhi Pei, Zihao Wang, Zhongyu Li, Mengdi Xu · 2026
> [arXiv](https://arxiv.org/abs/2610.29903) · [PDF](https://arxiv.org/pdf/2610.29903)

## Abstract

Real-time whole-body humanoid teleoperation remains challenging due to the computational latency introduced by optimization-based retargeting pipelines and future-frame conditioning. Existing motion tracking policies typically require dense reference targets including full joint positions, body-part transformations, and even future frames, which tightly couples the controller to expensive upstream modules. In this work, we present HuMiT, a whole-body teleoperation system built on a unified tracking policy that requires only a compact reference target, consisting of root height, root velocity, and the SE(3) poses of four sparse keypoints at the current frame, yet achieves competitive tracking fidelity compared to methods relying on more diverse reference states including complete joint positions, dense body-part transformations, and even future frames. Experiments show that our policy achieves a communication-to-inference latency of $\sim$20 ms measured between headset streaming and policy output and a video-based optical flow latency of 65 ms (median) across different motion types. We validate the system on a Unitree G1 humanoid, showcasing split-second reactive responses such as catching a tossed ball, as well as coordinated loco-manipulation capabilities. Project page: https://xiaohu-art.github.io/Track/.

## TL;DR

Real-time whole-body humanoid teleoperation remains challenging due to the computational latency introduced by optimization-based retargeting pipelines and future-frame conditioning. Existing motion tracking policies typically require dense reference targets including full joint positions, body-part transformations, and even future frames, which tightly couples the controller to expensive upstream modules.

## Related
<!-- [[other-paper-citekey]] -->
