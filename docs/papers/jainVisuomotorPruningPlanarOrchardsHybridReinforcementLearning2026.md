---
citekey: "jainVisuomotorPruningPlanarOrchardsHybridReinforcementLearning2026"
title: "Visuomotor Robotic Pruning in Planar Orchards Using Hybrid Reinforcement Learning"
authors: ["Abhinav Jain", "Cindy Grimm", "Stefan Lee"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24906"
doi: "10.48550/arXiv.2609.24906"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Visuomotor Robotic Pruning in Planar Orchards Using Hybrid Reinforcement Learning

> Abhinav Jain, Cindy Grimm, Stefan Lee · 2026
> [arXiv](https://arxiv.org/abs/2609.24906) · [PDF](https://arxiv.org/pdf/2609.24906)

## Abstract

Dormant tree pruning is labor-intensive yet essential for maintaining modern high-productivity fruit orchards. In this work, we focus on pruning of modern planar tree training systems - V-Trellis apples and UFO cherries - where trunks and primary branches are trained into approximately planar walls. We introduce an end-to-end pipeline to learn a closed-loop visuomotor controller for robotic pruning. This controller is trained entirely using simulation and synthetically generated data and deployed in real orchards in a zero-shot manner. The pipeline comprises synthetic generation of planar orchard tree meshes, construction of a physics-based orchard simulator, automated collection of successful pruning trajectories via motion planning, and policy learning with a novel hybrid reinforcement-learning algorithm that combines offline demonstrations with online simulated rollouts. The controller uses optical-flow inputs from a wrist-mounted camera - avoiding the need for full 3D-reconstruction - and continuously guides the cutter through cluttered branch environments to a specified cutpoint with correct tool orientation. In exhaustive simulated task-space evaluations over 3,000 pruning points, the policy attains 49.9% success on V-Trellis apples and 46.0% on UFO cherries. We validate the learned controller across 38 physical trials - comprising 28 outdoor field trials in commercial and experimental orchards and 10 indoor laboratory tests - demonstrating zero-shot sim-to-real transfer. The learned policy also outperforms a classical RRT-Connect baseline on physical hardware in laboratory trials.

## TL;DR

Dormant tree pruning is labor-intensive yet essential for maintaining modern high-productivity fruit orchards. In this work, we focus on pruning of modern planar tree training systems - V-Trellis apples and UFO cherries - where trunks and primary branches are trained into approximately planar walls.

## Related
<!-- [[other-paper-citekey]] -->
