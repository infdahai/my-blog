---
citekey: "fuSocioGestureRealTimeAdaptiveSocialGesturePerceptionHuman2026"
title: "SocioGesture: Real-Time and Adaptive Social Gesture Perception for Human-Robot Interaction"
authors: ["Wenjin Fu", "Li-Fan Wu", "Jerin Peter", "Chip Huyen", "Boyuan Chen", "Jan Liphardt"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04545"
doi: "10.48550/arXiv.2609.04545"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# SocioGesture: Real-Time and Adaptive Social Gesture Perception for Human-Robot Interaction

> Wenjin Fu, Li-Fan Wu, Jerin Peter, Chip Huyen, Boyuan Chen, Jan Liphardt · 2026
> [arXiv](https://arxiv.org/abs/2609.04545) · [PDF](https://arxiv.org/pdf/2609.04545)

## Abstract

Robots interacting with people must recognize not only explicit commands, but also social cues such as invitations, refusals, and unavailability. In real deployments, these cues must be inferred from noisy onboard perception under partial occlusion, changing viewpoints, and strict latency constraints. We present SocioGesture, a real-time adaptive social gesture perception system for human-robot interaction (HRI). SocioGesture uses a compact confidence-aware body-hand skeleton representation and a lightweight dual-stream model that fuses body motion with hand articulation for low-latency onboard recognition. To improve deployment robustness, we train the model with occlusion-aware skeleton corruption, exposing it to missing hands, occluded arms, and temporally unstable keypoints without increasing the inference cost. On a social gesture dataset collected in mixed indoor-outdoor HRI scenarios, SocioGesture achieves strong held-out-subject recognition, substantially improves robustness under structured joint occlusion, and runs in real time on a robot-mounted edge device. During deployment, uncertain interaction segments are saved for offline labeling and adaptation, enabling SocioGesture to expand its gesture vocabulary while preserving performance in the original classes. These results demonstrate a practical path toward robust, efficient, and adaptive social perception for interactive robots.

## TL;DR

Robots interacting with people must recognize not only explicit commands, but also social cues such as invitations, refusals, and unavailability. In real deployments, these cues must be inferred from noisy onboard perception under partial occlusion, changing viewpoints, and strict latency constraints.

## Related
<!-- [[other-paper-citekey]] -->
