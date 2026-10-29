---
citekey: "kramerTransformerBasedMonteCarloLocalizationConstructionMeshes2026"
title: "Transformer-based Monte Carlo Localization in Construction Meshes"
authors: ["Linus Kramer", "William Talbot", "Olga Vysotska", "Marco Hutter"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.31357"
doi: "10.48550/arXiv.2609.31357"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# Transformer-based Monte Carlo Localization in Construction Meshes

> Linus Kramer, William Talbot, Olga Vysotska, Marco Hutter · 2026
> [arXiv](https://arxiv.org/abs/2609.31357) · [PDF](https://arxiv.org/pdf/2609.31357)

## Abstract

To be able to perform inspection or digitization tasks, mobile robots on construction sites must be able to localize themselves reliably with respect to a global reference frame that is shared with a building map. Similar room layouts and low-texture surfaces pose a challenge for existing LiDAR- and vision-based localization methods. We approach this problem with a LiDAR-based global relocalization system that estimates the robot's pose relative to a building mesh and combines a PointNet++ encoder with a place recognition decoder, whose outputs serve as a learned observation model within a Monte Carlo Localization (MCL) framework. The pipeline is trained exclusively on synthetic LiDAR scans obtained by simulating the robot's sensors inside the building mesh. Our approach is robust in ambiguous environments due to an uncertainty-aware decoder that scales positional likelihoods and a resampling strategy that injects model hypotheses into the particle set, enabling recovery from potential particle depletion. Evaluations on real-world datasets show that our method outperforms both diffusion-based and ScanContext++ baselines while maintaining fast inference (18 ms per call), demonstrating the practicality of synthetic-data training for mesh-referenced global localization in construction robotics.

## TL;DR

To be able to perform inspection or digitization tasks, mobile robots on construction sites must be able to localize themselves reliably with respect to a global reference frame that is shared with a building map. Similar room layouts and low-texture surfaces pose a challenge for existing LiDAR- and vision-based localization methods.

## Related
<!-- [[other-paper-citekey]] -->
