---
citekey: "steinerWeaveRLWeavingReconstructionSceneAwareFabricsPerceptiveReinforcement2026"
title: "WeaveRL: Weaving Reconstruction into Scene-Aware Fabrics for Perceptive Reinforcement Learning"
authors: ["Remo Steiner", "Vikram Ramasamy", "David Tingdahl", "Sam Mady", "Karl Van Wyk", "Nathan Ratliff", "David Recasens Lafuente", "Soha Pouya", "Tuur Stuyck", "Alex Millane"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18685"
doi: "10.48550/arXiv.2609.18685"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# WeaveRL: Weaving Reconstruction into Scene-Aware Fabrics for Perceptive Reinforcement Learning

> Remo Steiner, Vikram Ramasamy, David Tingdahl, Sam Mady, Karl Van Wyk, Nathan Ratliff, David Recasens Lafuente, Soha Pouya, Tuur Stuyck, Alex Millane · 2026
> [arXiv](https://arxiv.org/abs/2609.18685) · [PDF](https://arxiv.org/pdf/2609.18685)

## Abstract

Reinforcement learning allows robots to acquire complex skills, but producing policies for geometrically complex manipulation remains difficult. A promising approach is to learn on top of collision-avoidant controllers, such as geometric fabrics. However, these approaches have relied on static, hand-specified representations of the scene. Integrating active, online 3D perception into massively parallel RL training has so far been inaccessible. We introduce a GPU-accelerated method that reconstructs the scene as a collection of surfels across thousands of parallel simulation instances during active rollouts. This lets policies operate over sensor-derived, rather than hand-specified, geometry. On a suite of collision-dense manipulation tasks, our surfel fabrics enable policies to tackle geometrically complex scenes where primitive-based baselines fail, while maintaining sim-to-real transfer. Furthermore, policies learned with a scene-aware fabric are more robust to the introduction of novel geometry at test time, improving collision-free task completion under unseen obstacles from 35% to 61%. We release our reconstruction system, training code and test dataset to spur research in this direction.

## TL;DR

Reinforcement learning allows robots to acquire complex skills, but producing policies for geometrically complex manipulation remains difficult. A promising approach is to learn on top of collision-avoidant controllers, such as geometric fabrics.

## Related
<!-- [[other-paper-citekey]] -->
