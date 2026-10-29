---
citekey: "liEnablingUnifiedCrossDomainRepresentationTwoFingerGripper2026"
title: "Enabling a Unified Cross-Domain Representation for Two-Finger Gripper Manipulation via Interaction-Centric Modeling"
authors: ["Guanlin Li", "Shifeng Bao", "Yihan Zhao", "Haitao Shen", "Haoyang Li", "Chen Zhao", "Tong Yang", "Jie Tang", "Jing Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.31207"
doi: "10.48550/arXiv.2609.31207"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# Enabling a Unified Cross-Domain Representation for Two-Finger Gripper Manipulation via Interaction-Centric Modeling

> Guanlin Li, Shifeng Bao, Yihan Zhao, Haitao Shen, Haoyang Li, Chen Zhao, Tong Yang, Jie Tang, Jing Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.31207) · [PDF](https://arxiv.org/pdf/2609.31207)

## Abstract

Achieving robust cross-embodiment generalization in imitation learning demands overcoming a critical representation flaw that inextricably entangles task semantics with hardware-specific visual geometry. We propose an interaction-centric framework that leverages the shared structure of two-finger grippers via a parameterized universal gripper abstraction, yielding a canonical gripper-frame representation. Given language and RGB-D observations, a VLM infers the subtask and grounds an interaction triplet (gripper, held, target), while SAM~2.1 tracks masks to reduce VLM queries. We design concise hybrid features that combine target/collision artificial potential fields for global guidance with segmented gripper-frame point clouds for local geometry, and use a Flow-Matching Transformer to predict smooth 7-DoF action chunks. Experiments in simulation and real-world tasks demonstrate that ours is the first imitation learning approach to simultaneously achieve competitive benchmark scores and extreme cross-embodiment/cross-viewpoint zero-shot sim-to-real transfer to completely distinct, heterogeneous robot platforms.

## TL;DR

Achieving robust cross-embodiment generalization in imitation learning demands overcoming a critical representation flaw that inextricably entangles task semantics with hardware-specific visual geometry. We propose an interaction-centric framework that leverages the shared structure of two-finger grippers via a parameterized universal gripper abstraction, yielding a canonical gripper-frame representation.

## Related
<!-- [[other-paper-citekey]] -->
