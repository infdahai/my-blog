---
citekey: "weiAmbientDiffusionPolicyImitationLearningSuboptimalDataRobotics2026"
title: "Ambient Diffusion Policy: Imitation Learning from Suboptimal Data in Robotics"
authors: ["Adam Wei", "Nicholas Pfaff", "Thomas Cohn", "Arif Kerem Dayı", "Constantinos Daskalakis", "Giannis Daras", "Russ Tedrake"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.12365"
doi: "10.48550/arXiv.2606.12365"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Ambient Diffusion Policy: Imitation Learning from Suboptimal Data in Robotics

> Adam Wei, Nicholas Pfaff, Thomas Cohn, Arif Kerem Dayı, Constantinos Daskalakis, Giannis Daras, Russ Tedrake · 2026
> [arXiv](https://arxiv.org/abs/2606.12365) · [PDF](https://arxiv.org/pdf/2606.12365)

## Abstract

We propose Ambient Diffusion Policy, a simple and principled method for imitation learning from suboptimal data in robotics. High-quality, task-specific robot data is expensive and time-consuming to collect, while suboptimal datasets with lower-quality or out-of-distribution demonstrations are abundant. Existing methods that co-train on both data sources in robotics often fail to separate the meaningful and the harmful features in the suboptimal samples. In contrast, our method extracts only the useful features by introducing a new axis to co-training in robotics: noise-dependent data usage. Ambient Diffusion Policy restricts the contribution of suboptimal data during training to only the high and low diffusion times. To rigorously justify our approach, we first observe that robot action data exhibits a spectral power law. This induces two important properties on the optimal Diffusion Policy that we exploit: a global-to-local hierarchy and locality. We theoretically formalize this discussion using a simplified model. Our experiments validate Ambient Diffusion Policy on four types of suboptimal action data (noisy trajectories, sim-to-real gap, task mismatch, and large-scale data mixtures) across six tasks. The results show that it effectively learns from arbitrary sources of suboptimal data. Notably, it outperforms existing co-training baselines by up to 33% when scaled to Open X-Embodiment - a large dataset with heterogeneous data quality and unstructured distribution shifts. Overall, Ambient Diffusion Policy increases the utility of suboptimal demonstrations and expands the set of usable data sources in robotics.

## TL;DR

We propose Ambient Diffusion Policy, a simple and principled method for imitation learning from suboptimal data in robotics. High-quality, task-specific robot data is expensive and time-consuming to collect, while suboptimal datasets with lower-quality or out-of-distribution demonstrations are abundant.

## Related
<!-- [[other-paper-citekey]] -->
