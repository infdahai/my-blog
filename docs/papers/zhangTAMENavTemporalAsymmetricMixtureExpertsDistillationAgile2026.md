---
citekey: "zhangTAMENavTemporalAsymmetricMixtureExpertsDistillationAgile2026"
title: "TAME-Nav: Temporal Asymmetric Mixture-of-Experts Distillation for Agile and Versatile Robot Navigation"
authors: ["Lingjie Zhang", "Jun Xue", "Shanze Wang", "Haoyu Xi", "Xinming Zhang", "Xiaoyu Shen", "Wei Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12877"
doi: "10.48550/arXiv.2610.12877"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# TAME-Nav: Temporal Asymmetric Mixture-of-Experts Distillation for Agile and Versatile Robot Navigation

> Lingjie Zhang, Jun Xue, Shanze Wang, Haoyu Xi, Xinming Zhang, Xiaoyu Shen, Wei Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.12877) · [PDF](https://arxiv.org/pdf/2610.12877)

## Abstract

Agile and reliable navigation is a core capability for embodied robots navigating complex spatial constraints and dynamic interactions. However, a single policy often struggles to accommodate the distinct decision-making demands of diverse scenarios. We present TAME-Nav, an asymmetric Teacher-Student navigation framework built around a temporal soft mixture of experts (Soft-MoE). The Teacher combines clean observations with causally maintained dynamic-obstacle tracks to construct privileged representations, while the Student learns complementary navigation features from corrupted observation histories through temporal encoding, soft expert routing, and latent distillation. Procedural scenario generation and parallel task-level simulation broaden training coverage, while deployment-informed asymmetric domain randomization supports sim-to-real transfer. Across in-distribution and unseen compositional scenarios, TAME-Nav achieves higher success rates, lower collision rates, and higher navigation scores than representative baselines. On a real quadruped robot, it completes all twenty trials across local-trap escape and narrow-passage navigation with sudden dynamic obstacles, with only one minor contact.

## TL;DR

Agile and reliable navigation is a core capability for embodied robots navigating complex spatial constraints and dynamic interactions. However, a single policy often struggles to accommodate the distinct decision-making demands of diverse scenarios.

## Related
<!-- [[other-paper-citekey]] -->
