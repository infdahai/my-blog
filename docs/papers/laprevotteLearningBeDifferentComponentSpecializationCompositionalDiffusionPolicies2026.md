---
citekey: "laprevotteLearningBeDifferentComponentSpecializationCompositionalDiffusionPolicies2026"
title: "Learning to Be Different: Component Specialization for Compositional Diffusion Policies"
authors: ["Alec Laprevotte", "Haonan Chen", "Xiaoshen Han", "Yilun Du"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27194"
doi: "10.48550/arXiv.2610.27194"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Learning to Be Different: Component Specialization for Compositional Diffusion Policies

> Alec Laprevotte, Haonan Chen, Xiaoshen Han, Yilun Du · 2026
> [arXiv](https://arxiv.org/abs/2610.27194) · [PDF](https://arxiv.org/pdf/2610.27194)

## Abstract

Diffusion policies with linearly composed scores have emerged as a promising approach to multitask robotic learning by combining separate factors to enable modular, task-wise adaptation, compositional generalization, and interpretable functional decomposition. However, current training objectives do not encourage factor specialization, often resulting in uninterpretable denoisers whose composed prediction is an average over identical copies, undermining their architectural premise. To address this, we propose a drop-in score-decorrelation auxiliary loss, motivated by projective composition theory. Our approach encourages specialization by penalizing overlap directly between component noise predictions, with little architectural change or computational overhead. We demonstrate across multiple benchmarks that our decorrelation loss consistently reduces measurable double-counting between components, improves task decomposition, and produces behaviorally meaningful specialization without compromising multitask performance. Website: https://al3cl1.github.io/robotics-score-decorrelation.

## TL;DR

Diffusion policies with linearly composed scores have emerged as a promising approach to multitask robotic learning by combining separate factors to enable modular, task-wise adaptation, compositional generalization, and interpretable functional decomposition. However, current training objectives do not encourage factor specialization, often resulting in uninterpretable denoisers whose composed prediction is an average over identical copies, undermining their architectural premise.

## Related
<!-- [[other-paper-citekey]] -->
