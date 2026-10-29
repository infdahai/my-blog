---
citekey: "guptaEigenDEXploreStructuredExplorationDexterousManipulationHumanPriors2026"
title: "EigenDEXplore: Structured Exploration for Dexterous Manipulation with Human Priors"
authors: ["Harsh Gupta", "Tyler Ga Wei Lum", "Changhao Wang", "Chuer Pan", "C. Karen Liu", "Jeannette Bohg", "Shuran Song"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07681"
doi: "10.48550/arXiv.2610.07681"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# EigenDEXplore: Structured Exploration for Dexterous Manipulation with Human Priors

> Harsh Gupta, Tyler Ga Wei Lum, Changhao Wang, Chuer Pan, C. Karen Liu, Jeannette Bohg, Shuran Song · 2026
> [arXiv](https://arxiv.org/abs/2610.07681) · [PDF](https://arxiv.org/pdf/2610.07681)

## Abstract

Dexterous manipulation poses a challenging high-dimensional optimization problem, as useful behaviors require coordinated motion across many hand joints. In reinforcement learning (RL) and sampling-based trajectory optimization, exploration commonly relies on independent robot joint perturbations, making coordinated behaviors difficult to discover. Prior work reduces this search space for grasp learning using low-dimensional spaces of coordinated joint motions learned from human hand data, but this restricts the expressivity required for general manipulation. Some combine learned and joint-space actions to restore expressivity, but this increases dimensionality and introduces redundancy. We study these effects across diverse manipulation settings, varying action dimensionality, exploration strategy, and the source of human data. Our experiments suggest that human-motion priors are most effective when used to structure exploration rather than change the action representation. Motivated by this finding, we propose EigenDEXplore, which induces correlated exploration by adding perturbations along human-derived eigenvectors to independent joint-space noise, leaving the action space unchanged. Across multiple dexterous hands, EigenDEXplore consistently outperforms joint-space and learned action-space baselines in grasping, in-hand reorientation, and contact-rich manipulation. These gains span unstructured and reference-guided RL, trajectory optimization, and sim-to-real deployment, and are largest in settings with less reward shaping and curriculum design.

## TL;DR

Dexterous manipulation poses a challenging high-dimensional optimization problem, as useful behaviors require coordinated motion across many hand joints. In reinforcement learning (RL) and sampling-based trajectory optimization, exploration commonly relies on independent robot joint perturbations, making coordinated behaviors difficult to discover.

## Related
<!-- [[other-paper-citekey]] -->
