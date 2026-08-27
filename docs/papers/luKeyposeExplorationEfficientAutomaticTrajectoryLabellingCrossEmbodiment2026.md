---
citekey: "luKeyposeExplorationEfficientAutomaticTrajectoryLabellingCrossEmbodiment2026"
title: "Keypose Exploration: Efficient Automatic Trajectory Labelling and Cross-Embodiment Policy Transfer"
authors: ["Yupu Lu", "Hang Xu", "Yizhou Chen", "Jia Pan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.29028"
doi: "10.48550/arXiv.2606.29028"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Keypose Exploration: Efficient Automatic Trajectory Labelling and Cross-Embodiment Policy Transfer

> Yupu Lu, Hang Xu, Yizhou Chen, Jia Pan · 2026
> [arXiv](https://arxiv.org/abs/2606.29028) · [PDF](https://arxiv.org/pdf/2606.29028)

## Abstract

Keypose-based manipulation decomposes tasks into critical waypoints to simplify policy learning for long-horizon tasks, but existing approaches rely on task-specific heuristics or manual annotation to extract keyposes from demonstrations. We present an automatic trajectory labelling pipeline for grasp-related tasks. This pipeline combines vision-language models (VLMs) for semantic event detection with classical trajectory analysis for precise temporal alignment, requiring VLM inference only on one single demo among repeating ones per task. Using the labelled data, we train a keypose-guided Diffusion Policy (DP) that exploits keypose conditioning to intervene demonstration distributions. We explore the possibility to apply this property for cross-embodiment transfer: candidate keyposes are sampled and filtered via a reachability map, steering the policy toward kinematically feasible keyposes for the target robot. As a preliminary feasibility study, experiments on two robomimic tasks show that the labelled data produces policies matching a standard DP baseline, and that reachability-filtered keypose conditioning may benefit zero-shot transfer on the multimodal insertion task when feasible candidates are available.

## TL;DR

Keypose-based manipulation decomposes tasks into critical waypoints to simplify policy learning for long-horizon tasks, but existing approaches rely on task-specific heuristics or manual annotation to extract keyposes from demonstrations. We present an automatic trajectory labelling pipeline for grasp-related tasks.

## Related
<!-- [[other-paper-citekey]] -->
