---
citekey: "wangEgoInfinityWebScale4DHandObjectInteractionData2026"
title: "EgoInfinity: A Web-Scale 4D Hand-Object Interaction Data Engine for Any-View Robot Retargeting and Video-to-Action Robot Learning"
authors: ["Gaotian Wang", "Kejia Ren", "Andrew Morgan", "Yiting Chen", "Howard H. Qian", "Podshara Chanrungmaneekul", "Kaiyu Hang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.17385"
doi: "10.48550/arXiv.2606.17385"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# EgoInfinity: A Web-Scale 4D Hand-Object Interaction Data Engine for Any-View Robot Retargeting and Video-to-Action Robot Learning

> Gaotian Wang, Kejia Ren, Andrew Morgan, Yiting Chen, Howard H. Qian, Podshara Chanrungmaneekul, Kaiyu Hang · 2026
> [arXiv](https://arxiv.org/abs/2606.17385) · [PDF](https://arxiv.org/pdf/2606.17385)

## Abstract

Internet videos constitute the largest reservoir of embodied human manipulation knowledge, yet converting arbitrary RGB footage into actionable robot training data remains a major bottleneck. Existing lab- or factory-collected datasets are narrow in scale and diversity, limiting open-world robot learning. Instead of proposing a static dataset, we introduce EgoInfinity, a universal 4D hand-object interaction data engine that enables web-scale data generation for robot retargeting and learning. EgoInfinity is a modular engine integrating perception, segmentation, reconstruction, interaction-aware refinement, and retargeting to automate this traditionally unscalable video-to-action problem without human-in-the-loop annotation. Its modular design lets the engine continuously benefit from advances in any incorporated component. With EgoInfinity, in-the-wild human manipulation videos are lifted into agent-agnostic, metric 4D hand-object representations, including hand trajectories, 6-DoF object poses, and contact-relevant states. Rather than naively connecting standalone components, EgoInfinity combines cross-module metric calibration with interaction-aware refinement to improve physical reliability, reducing drift and contact inconsistencies common in pure visual reconstruction. We further propose a novel motion retargeter that compiles the recovered 3D hand motions into executable joint trajectories for diverse robot morphologies, enabling video-to-action retargeting on any robot from arbitrary viewpoints and shot sizes (e.g., the human body is only partially visible). We validate EgoInfinity across perception fidelity, kinematic feasibility, contact consistency, cross-embodiment generalization, and real-robot skill acquisition (e.g., grasping, cutting, wiping, and pouring), demonstrating a scalable bridge from internet videos to executable robot behavior for open-world robot learning.

## TL;DR

Internet videos constitute the largest reservoir of embodied human manipulation knowledge, yet converting arbitrary RGB footage into actionable robot training data remains a major bottleneck. Existing lab- or factory-collected datasets are narrow in scale and diversity, limiting open-world robot learning.

## Related
<!-- [[other-paper-citekey]] -->
