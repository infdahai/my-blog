---
citekey: "ohPolyMorphLearningLocomotionPolicyCrossEmbodimentAdaptation2026"
title: "PolyMorph: Learning Locomotion Policy for Cross-Embodiment Adaptation"
authors: ["Hyunsik Oh", "Seunghun Jeon", "Donghoon Youm", "Jungwoo Hur", "Hyeongjun Kim", "Jeong Hyun Lee", "Moonkyu Jung", "Jemin Hwangbo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19615"
doi: "10.48550/arXiv.2610.19615"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# PolyMorph: Learning Locomotion Policy for Cross-Embodiment Adaptation

> Hyunsik Oh, Seunghun Jeon, Donghoon Youm, Jungwoo Hur, Hyeongjun Kim, Jeong Hyun Lee, Moonkyu Jung, Jemin Hwangbo · 2026
> [arXiv](https://arxiv.org/abs/2610.19615) · [PDF](https://arxiv.org/pdf/2610.19615)

## Abstract

Reinforcement learning has enabled robust locomotion for legged robots, but learned policies are typically tied to a specific robot morphology and require additional engineering when the number of legs, actuators, or mechanical properties change. We present PolyMorph, a morphology-conditioned framework that learns a single locomotion policy for heterogeneous legged robots. PolyMorph converts each robot's URDF into joint-link modules and combines a recurrent encoder, graph-based Transformer, and per-joint decoder to generate actions across variable leg counts and joint configurations. To improve training stability, PolyMorph uses morphology-normalized rewards, adaptive robot sampling, and URDF-derived PD-gain initialization. We evaluate PolyMorph in simulation across bipedal, tripedal, and quadrupedal robots, including unseen morphology variants and platforms, and deploy the policy on real quadruped platforms operated in multiple configurations. The results show that a single PolyMorph policy generalizes across diverse robot morphologies without per-robot policy retraining.

## TL;DR

Reinforcement learning has enabled robust locomotion for legged robots, but learned policies are typically tied to a specific robot morphology and require additional engineering when the number of legs, actuators, or mechanical properties change. We present PolyMorph, a morphology-conditioned framework that learns a single locomotion policy for heterogeneous legged robots.

## Related
<!-- [[other-paper-citekey]] -->
