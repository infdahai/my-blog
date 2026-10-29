---
citekey: "tatschSGESemanticallyGuidedExplorationUnstructuredEnvironmentsImageSpace2026"
title: "SGE: Semantically-Guided Exploration for Unstructured Environments via Image-Space Waypoint Sampling"
authors: ["Christopher Tatsch", "Yu Gu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29315"
doi: "10.48550/arXiv.2608.29315"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# SGE: Semantically-Guided Exploration for Unstructured Environments via Image-Space Waypoint Sampling

> Christopher Tatsch, Yu Gu · 2026
> [arXiv](https://arxiv.org/abs/2608.29315) · [PDF](https://arxiv.org/pdf/2608.29315)

## Abstract

This work introduces Semantically-Guided Exploration (SGE), a modular exploration framework for ground vehicles that integrates pixel-level semantic segmentation into sampling-based waypoint selection and receding-horizon route optimization. Unlike conventional geometric exploration methods, SGE evaluates candidate exploration goals directly in the image space using a semantic-aware utility function that accounts for terrain traversability, obstacle proximity, objects of interest, and depth-based exploration reward. Sampled waypoints are projected into 3D and ordered through a real-time Traveling Salesman Problem (TSP) formulation, enabling receding-horizon goal selection. To address real-world navigation uncertainty, the framework introduces mechanisms, including temporary taboo regions to handle navigation failures and a graph-based relocation strategy for efficient backtracking across explored areas. We evaluate SGE in standardized simulation benchmarks against state-of-the-art exploration planners and demonstrate competitive performance in volumetric coverage, while enabling semantic task biasing that cannot be achieved by purely geometric methods. The framework is further validated through real-world experiments using multiple robotic platforms in indoor campus buildings and in limestone and coal mines. Results show consistent performance and adaptability across platforms and domains.

## TL;DR

This work introduces Semantically-Guided Exploration (SGE), a modular exploration framework for ground vehicles that integrates pixel-level semantic segmentation into sampling-based waypoint selection and receding-horizon route optimization. Unlike conventional geometric exploration methods, SGE evaluates candidate exploration goals directly in the image space using a semantic-aware utility function that accounts for terrain traversability, obstacle proximity, objects of interest, and depth-based exploration reward.

## Related
<!-- [[other-paper-citekey]] -->
