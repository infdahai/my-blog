---
citekey: "wangGAEGeneralActionExpertRealTimeHumanoidTeleoperation2026"
title: "GAE: General Action Expert for Real-Time Humanoid Teleoperation"
authors: ["Yuefan Wang", "Huaicheng Zhou", "Xiao He", "Zhijie He", "Mingchuan Yang", "Huayi Zhang", "Li Chai", "Jinxin Liu", "Donglin Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34233"
doi: "10.48550/arXiv.2609.34233"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# GAE: General Action Expert for Real-Time Humanoid Teleoperation

> Yuefan Wang, Huaicheng Zhou, Xiao He, Zhijie He, Mingchuan Yang, Huayi Zhang, Li Chai, Jinxin Liu, Donglin Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.34233) · [PDF](https://arxiv.org/pdf/2609.34233)

## Abstract

Humanoid avatars extend human physical presence beyond the body, enabling people to participate in social, service, and labor activities through remotely operated robots. This requires teleoperation systems capable of realizing diverse and dynamic whole-body behaviors while maintaining responsive human-robot synchronization. We present General Action Expert(GAE), a unified learning framework for general-purpose, low-latency humanoid whole-body teleoperation. To cover diverse human behaviors, GAE builds a large-scale human motion dataset from heterogeneous sources, including videos, animations, and motion capture, followed by standardization and augmentation. GAE then addresses the noise and embodiment mismatch in human motions with a two-stage training paradigm: a privileged generator policy first tracks human motion references in simulation and rolls out feasible humanoid trajectories; a deployable executor policy then learns to track these generated trajectories under curriculum domain randomization. For responsive human-robot synchronization, GAE introduces a latency-conditioned anticipation mechanism that adaptively compensates for end-to-end delay during real-time teleoperation. Simulation and real-world experiments on Unitree G1 and Westlake O1 robots demonstrate that GAE enables humanoids to smoothly mirror diverse, agile, and expressive human behaviors. Project website: https://wangyf0928.github.io/gae-wlrobotics/

## TL;DR

Humanoid avatars extend human physical presence beyond the body, enabling people to participate in social, service, and labor activities through remotely operated robots. This requires teleoperation systems capable of realizing diverse and dynamic whole-body behaviors while maintaining responsive human-robot synchronization.

## Related
<!-- [[other-paper-citekey]] -->
