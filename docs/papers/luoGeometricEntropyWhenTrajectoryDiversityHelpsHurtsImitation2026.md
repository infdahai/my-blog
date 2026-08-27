---
citekey: "luoGeometricEntropyWhenTrajectoryDiversityHelpsHurtsImitation2026"
title: "Geometric Entropy: When Trajectory Diversity Helps and Hurts in Imitation Learning"
authors: ["Qian Luo", "Ruizhe Liu", "Pei Zhou", "Xunzhe Zhou", "Yanchao Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.20871"
doi: "10.48550/arXiv.2606.20871"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Geometric Entropy: When Trajectory Diversity Helps and Hurts in Imitation Learning

> Qian Luo, Ruizhe Liu, Pei Zhou, Xunzhe Zhou, Yanchao Yang · 2026
> [arXiv](https://arxiv.org/abs/2606.20871) · [PDF](https://arxiv.org/pdf/2606.20871)

## Abstract

We study how trajectory-shape diversity in demonstrations affects imitation learning (IL) performance across models, tasks, and data scales. We introduce Geometric Entropy (H_G), a task-agnostic metric that quantifies the intrinsic diversity of transit trajectories after normalizing away extrinsic variation, such as goal pose and workspace scale, via target-frame alignment. Across multiple IL architectures and both simulated and real-robot contact-rich manipulation tasks, we observe a consistent inverted-U relationship between success and H_G: increasing geometric diversity improves robustness in low-diversity regimes but degrades performance once diversity induces strategy ambiguity. Moreover, the optimal entropy shifts toward lower values as task mastery increases through more data, easier tasks, or stronger priors, and for a pretrained vision-language-action model the trend becomes effectively monotonic decreasing. Practically, H_G enables fast pre-training auditing of demonstration datasets and offers a simple guideline for calibrating demonstrations toward the learnable regime.

## TL;DR

We study how trajectory-shape diversity in demonstrations affects imitation learning (IL) performance across models, tasks, and data scales. We introduce Geometric Entropy (H_G), a task-agnostic metric that quantifies the intrinsic diversity of transit trajectories after normalizing away extrinsic variation, such as goal pose and workspace scale, via target-frame alignment.

## Related
<!-- [[other-paper-citekey]] -->
