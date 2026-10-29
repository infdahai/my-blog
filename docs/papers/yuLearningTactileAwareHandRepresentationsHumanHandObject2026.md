---
citekey: "yuLearningTactileAwareHandRepresentationsHumanHandObject2026"
title: "Learning Tactile-Aware Hand Representations from Human Hand-Object Interaction Data"
authors: ["Yeonguk Yu", "Jaehong Kim", "Byungok Han"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27995"
doi: "10.48550/arXiv.2610.27995"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Learning Tactile-Aware Hand Representations from Human Hand-Object Interaction Data

> Yeonguk Yu, Jaehong Kim, Byungok Han · 2026
> [arXiv](https://arxiv.org/abs/2610.27995) · [PDF](https://arxiv.org/pdf/2610.27995)

## Abstract

Tactile representation learning for dexterous manipulation often requires substantial robot-side data collection, limiting its scalability across different hands and sensors. We explore whether large-scale human hand-object interaction (HOI) data can provide a useful prior for robotic tactile learning. To this end, we propose HuTact, a framework that pretrains tactile-aware hand representations from human HOI data without requiring real tactile signals during pretraining. HuTact transfers the interaction structure learned from human hand motions to robotic tactile observations and can be further adapted with a small amount of unlabeled robot interaction data. We evaluate HuTact on tactile perception and manipulation tasks, including grasp prediction, slip detection, object classification, and tactile-conditioned policy learning. Across these tasks, human HOI pretraining improves data efficiency and provides a strong initialization for downstream learning. Notably, with HOI pretraining followed by midtraining on unlabeled robot play data, HuTact achieves 88.26% Macro-F1 on grasp prediction using only 25\% of the labeled downstream data, comparable to training from scratch on the full labeled dataset (88.23%). These results suggest that human interaction data can serve as a scalable complementary source for robotic tactile representation learning.

## TL;DR

Tactile representation learning for dexterous manipulation often requires substantial robot-side data collection, limiting its scalability across different hands and sensors. We explore whether large-scale human hand-object interaction (HOI) data can provide a useful prior for robotic tactile learning.

## Related
<!-- [[other-paper-citekey]] -->
