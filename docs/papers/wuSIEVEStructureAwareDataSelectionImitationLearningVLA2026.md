---
citekey: "wuSIEVEStructureAwareDataSelectionImitationLearningVLA2026"
title: "SIEVE: Structure-Aware Data Selection for Imitation Learning with VLA Models"
authors: ["Changti Wu", "Bin Yu", "Zhaolong Shen", "Shijie Lian", "Xiaopeng Lin", "Cong Huang", "Zhirui Zhang", "Lei Zhang", "Kai Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.06442"
doi: "10.48550/arXiv.2607.06442"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# SIEVE: Structure-Aware Data Selection for Imitation Learning with VLA Models

> Changti Wu, Bin Yu, Zhaolong Shen, Shijie Lian, Xiaopeng Lin, Cong Huang, Zhirui Zhang, Lei Zhang, Kai Chen · 2026
> [arXiv](https://arxiv.org/abs/2607.06442) · [PDF](https://arxiv.org/pdf/2607.06442)

## Abstract

Vision-Language-Action (VLA) models are typically trained by imitation learning on large-scale robot demonstration datasets, but more data does not necessarily yield better policies due to redundancy, noise, and uneven coverage. Existing data selection methods often assess demonstrations at either the trajectory or state-action level, missing the reusable structures that compose long-horizon behaviors. In this paper, we propose SIEVE, a structure-aware data selection method for VLA imitation learning. SIEVE views demonstrations as compositions of reusable primitives and transition interfaces. It first discovers visuo-motor primitives from segmented trajectories, then allocates selection budgets to composition patterns by maximizing reuse-aware structural exposure under diminishing returns. Finally, it selects medoid trajectories within each composition-pattern bucket to retain central, stable, and imitation-friendly demonstrations. Experiments across multiple datasets, benchmarks, and VLA models show that SIEVE consistently outperforms competitive data selection baselines. Notably, SIEVE can surpass full-data training while using only 50% of demonstrations and 50% of training steps, suggesting that reusable structure, captured through primitives and transitions, is an important signal for efficient VLA imitation learning.

## TL;DR

Vision-Language-Action (VLA) models are typically trained by imitation learning on large-scale robot demonstration datasets, but more data does not necessarily yield better policies due to redundancy, noise, and uneven coverage. Existing data selection methods often assess demonstrations at either the trajectory or state-action level, missing the reusable structures that compose long-horizon behaviors.

## Related
<!-- [[other-paper-citekey]] -->
