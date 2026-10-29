---
citekey: "wangNavArenaAutomatedConstructionGoalOrientedNavigationBenchmarks3D2026"
title: "NavArena: Automated Construction of Goal-Oriented Navigation Benchmarks from 3D Gaussian Splatting Reconstructions"
authors: ["Junhui Wang", "Wei Yang", "Xinyao Li", "Ningjing Fan", "Yuehao Yin", "Xuecheng Chen", "Chao Gao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04602"
doi: "10.48550/arXiv.2609.04602"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# NavArena: Automated Construction of Goal-Oriented Navigation Benchmarks from 3D Gaussian Splatting Reconstructions

> Junhui Wang, Wei Yang, Xinyao Li, Ningjing Fan, Yuehao Yin, Xuecheng Chen, Chao Gao · 2026
> [arXiv](https://arxiv.org/abs/2609.04602) · [PDF](https://arxiv.org/pdf/2609.04602)

## Abstract

Fixed 3D Gaussian Splatting (3DGS) reconstructions provide realistic novel views but lack the traversability constraints, valid goals, and closed-loop protocols required for navigation evaluation. We introduce NavArena, an automated framework that transforms fixed 3DGS reconstructions into benchmarks for goal-oriented visual navigation. NavArena integrates a frozen 3DGS model for egocentric RGB-D rendering, an occupancy costmap derived from Gaussian density and height statistics for reachability and collision queries, and semantic goal candidates lifted from multi-view open-vocabulary masks. These components support the automatic generation and unified closed-loop evaluation of goal-oriented navigation episodes. Across more than 2{,}000 scenes, NavArena generates 22.2 million expert trajectories. Spatial and semantic evaluations assess the derived navigation representations, while policy rollouts demonstrate the diagnostic value of the unified evaluation protocol. NavArena enables scalable and reproducible navigation evaluation on large-scale 3DGS reconstructions, and all benchmark-generation tools, evaluation protocols, and derived assets will be released publicly.

## TL;DR

Fixed 3D Gaussian Splatting (3DGS) reconstructions provide realistic novel views but lack the traversability constraints, valid goals, and closed-loop protocols required for navigation evaluation. We introduce NavArena, an automated framework that transforms fixed 3DGS reconstructions into benchmarks for goal-oriented visual navigation.

## Related
<!-- [[other-paper-citekey]] -->
