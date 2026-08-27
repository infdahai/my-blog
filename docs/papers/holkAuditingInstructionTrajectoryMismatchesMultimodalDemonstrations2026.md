---
citekey: "holkAuditingInstructionTrajectoryMismatchesMultimodalDemonstrations2026"
title: "Auditing Instruction-Trajectory Mismatches in Multimodal Robot Demonstrations"
authors: ["Simon Holk", "Ryosuke Takanami", "Tatsuya Matsushima", "Yusuke Iwasawa", "Yutaka Matsuo", "Yueh-Hua Wu", "Kei Ota"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.07895"
doi: "10.48550/arXiv.2608.07895"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Auditing Instruction-Trajectory Mismatches in Multimodal Robot Demonstrations

> Simon Holk, Ryosuke Takanami, Tatsuya Matsushima, Yusuke Iwasawa, Yutaka Matsuo, Yueh-Hua Wu, Kei Ota · 2026
> [arXiv](https://arxiv.org/abs/2608.07895) · [PDF](https://arxiv.org/pdf/2608.07895)

## Abstract

Robot demonstration datasets used to train vision-language-action policies can contain a subtle but harmful failure mode: trajectories that are behaviorally correct but paired with the wrong language instruction. We study post-hoc auditing of these Instruction-Trajectory Mismatches (ITMs). Unlike failed rollouts, ITMs often look plausible, and can corrupt the language-behavior mapping learned by the policy. We propose Multimodal Probabilistic Fusion (MMPF), a training-free auditing framework that treats each modality as an expert, estimates a task-label distribution from local neighborhood agreement and global prototype similarity, and then fuses modalities with predictive-entropy weighting in a product of experts. Across LIBERO benchmarks with injected instruction mismatches and noisy real-robot data, MMPF achieves the strongest overall ITM detection and label correction accuracy. We also show that auditing improves most downstream policy learning in settings where language is needed to disambiguate the task. We demonstrate in real robot experiments that our method can achieve improved policy performance and show the trade-off of filtering demonstrations compared to relabeling.

## TL;DR

Robot demonstration datasets used to train vision-language-action policies can contain a subtle but harmful failure mode: trajectories that are behaviorally correct but paired with the wrong language instruction. We study post-hoc auditing of these Instruction-Trajectory Mismatches (ITMs).

## Related
<!-- [[other-paper-citekey]] -->
