---
citekey: "kuriharaEgoRevealLearningActiveVisionObjectManipulationPartialOcclusions2026"
title: "EgoReveal: Learning Active Vision and Object Manipulation under Partial Occlusions from Egocentric Demonstrations"
authors: ["Hiromu Kurihara", "Kazutoshi Tanaka", "Masashi Hatano", "Tadashi Kozuno", "Hideo Saito", "Mariko Isogawa"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12999"
doi: "10.48550/arXiv.2610.12999"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# EgoReveal: Learning Active Vision and Object Manipulation under Partial Occlusions from Egocentric Demonstrations

> Hiromu Kurihara, Kazutoshi Tanaka, Masashi Hatano, Tadashi Kozuno, Hideo Saito, Mariko Isogawa · 2026
> [arXiv](https://arxiv.org/abs/2610.12999) · [PDF](https://arxiv.org/pdf/2610.12999)

## Abstract

Learning from Demonstrations (LfD) enables robots to learn object manipulation directly from human demonstrations. In contrast to resource-intensive and labor-intensive teleoperation, egocentric demonstrations are easy to collect, enabling scalable data collection. Manipulated objects are often partially occluded in everyday environments, yet prior egocentric demonstration-based methods that require no robots or specialized teaching devices do not explicitly address occlusions. To fill this gap, we propose EgoReveal, a framework that learns viewpoint-repositioning together with manipulation actions from egocentric human demonstrations to reposition the viewpoint and obtain target visibility under partial occlusions. EgoReveal instantiates this as two imitation policies: one predicts the future camera-arm pose sequence from the current view and camera-arm pose, and the other predicts the future control commands from object keypoints and a history of control commands. EgoReveal switches between the two based on target visibility. In experiments where the manipulated object is partially occluded initially, EgoReveal repositions the camera to obtain visibility and completes the task more reliably than fixed-camera baselines.

## TL;DR

Learning from Demonstrations (LfD) enables robots to learn object manipulation directly from human demonstrations. In contrast to resource-intensive and labor-intensive teleoperation, egocentric demonstrations are easy to collect, enabling scalable data collection.

## Related
<!-- [[other-paper-citekey]] -->
