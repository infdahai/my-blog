---
citekey: "pengLearningNavigationMultimodalDemonstrationsGeometricCandidateModes2026"
title: "Learning Navigation from Multimodal Demonstrations with Geometric Candidate Modes"
authors: ["Chengyang Peng", "Zhihao Zhang", "Upama Pant", "Yiming Wang", "Keith A. Redmill", "Ayonga Hereid"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20241"
doi: "10.48550/arXiv.2610.20241"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# Learning Navigation from Multimodal Demonstrations with Geometric Candidate Modes

> Chengyang Peng, Zhihao Zhang, Upama Pant, Yiming Wang, Keith A. Redmill, Ayonga Hereid · 2026
> [arXiv](https://arxiv.org/abs/2610.20241) · [PDF](https://arxiv.org/pdf/2610.20241)

## Abstract

Offline navigation demonstrations are multimodal, because one observation often allows several valid actions, such as passing an obstacle on either side. Behavior cloning averages these actions, potentially leading to unsafe routes. Multimodal policies must discover the alternatives from the data, but similar states can lead to different routes whose current actions overlap. In navigation, the alternatives have a geometric cause and can be computed from one observation. We propose a hierarchical neural-network policy that computes candidate modes from local geometry and learns from demonstrations which mode to follow and how. A high-level policy selects a mode using the goal and its previous choice among a set of candidate modes, and a low-level policy turns it into an action. In simulation, the policy succeeds in over 95\% of seen and unseen test cases, compared with at most 43\% and 20\% for four offline learning baselines and 79\% and 67\% for a heuristic that uses the same modes without learning. The simulation-trained policy also transfers to a LimX Tron 1 bipedal robot.

## TL;DR

Offline navigation demonstrations are multimodal, because one observation often allows several valid actions, such as passing an obstacle on either side. Behavior cloning averages these actions, potentially leading to unsafe routes.

## Related
<!-- [[other-paper-citekey]] -->
