---
citekey: "shiTopologicalNecessitiesMechanismInvariantStrategicSubgoalsCrossEmbodiment2026"
title: "Topological Necessities: Mechanism-Invariant Strategic Subgoals for Cross-Embodiment Goal-Conditioned Control"
authors: ["Hao Shi", "Xi Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11014"
doi: "10.48550/arXiv.2609.11014"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# Topological Necessities: Mechanism-Invariant Strategic Subgoals for Cross-Embodiment Goal-Conditioned Control

> Hao Shi, Xi Li · 2026
> [arXiv](https://arxiv.org/abs/2609.11014) · [PDF](https://arxiv.org/pdf/2609.11014)

## Abstract

Long-horizon goal-conditioned reinforcement learning delegates control to a high-level module that proposes subgoals, but existing subgoals are implicit byproducts of value functions or latent actions, tied to the executor that produced them. We study a different object: a route-conditioned order of unavoidable stages that every successful executor must traverse, recoverable from offline trajectories and belonging to none of them. Its defining properties are topological: an unskippable stage is a separating set that every admissible path must cross, and a loop in free space forces a route choice. We read the two by homology in dimensions 0 and 1 over a transport-weighted carrier built from successful trajectories, yielding an enumerable gate set with shell-level certificates; the certified gates are what we call topological necessities. Certified gates enter the decision loop as a recursive topological gate hierarchy. Under a fixed, isomorphic free space, the object survives executor replacement: gates frozen on PointMaze data transfer without retraining to Ant and Humanoid, attaining the highest Humanoid aggregate under a unified interface (96.1), with +36.0 over a map-privileged reference on the multi-route task (p=1.4e-5); the planner saturates PointMaze (100+/-0) and matches or exceeds the strongest baselines on AntMaze (giant +22.9) and Kitchen (+15.8/+12.6).

## TL;DR

Long-horizon goal-conditioned reinforcement learning delegates control to a high-level module that proposes subgoals, but existing subgoals are implicit byproducts of value functions or latent actions, tied to the executor that produced them. We study a different object: a route-conditioned order of unavoidable stages that every successful executor must traverse, recoverable from offline trajectories and belonging to none of them.

## Related
<!-- [[other-paper-citekey]] -->
