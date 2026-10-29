---
citekey: "janwaniMultiObjectiveHumanLoopBayesianOptimizationLowerLimb2026"
title: "Multi-Objective Human-in-the-Loop Bayesian Optimization of a Lower-Limb Exoskeleton"
authors: ["Neil Janwani", "Matthew T. Lerner", "Aaron J. Young", "Maegan Tucker"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.30695"
doi: "10.48550/arXiv.2609.30695"
tags: [paper, embodied-ai, "cs.HC", "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# Multi-Objective Human-in-the-Loop Bayesian Optimization of a Lower-Limb Exoskeleton

> Neil Janwani, Matthew T. Lerner, Aaron J. Young, Maegan Tucker · 2026
> [arXiv](https://arxiv.org/abs/2609.30695) · [PDF](https://arxiv.org/pdf/2609.30695)

## Abstract

Human-in-the-loop optimization (HILO) is a common approach for optimizing the control of assistive devices to account for the wearer's unique biomechanics and subjective preferences. However, despite research suggesting that a person may have a different prioritization of objectives depending on time-varying factors such as the environment, their mood, or energy levels, existing HILO approaches only consider a single objective or enforce a fixed weighting on a set of objectives. Neither approach is capable of representing an individual's preferences over objectives. In this work, we propose Multi-Objective Human-in-the-loop Bayesian Optimization (MO-HILBO), which builds on explicit multi-objective Bayesian optimization to efficiently infer a personalized set of Pareto-optimal controllers. We compare our approach with an existing multi-objective HILO method and experimentally demonstrate MO-HILBO on a lower-limb exoskeleton across two objectives: metabolic cost (efficiency) and ordinal human feedback (comfort). We find that MO-HILBO (1) discovers Pareto-optimal controllers, and (2) that the pairwise ordering of points on the Pareto front itself is consistent with validation trials. Lastly, we open-source mohilo, a Python package for running both HILO and MO-HILBO on wearable devices: https://dynamicmobility.github.io/mohilo/.

## TL;DR

Human-in-the-loop optimization (HILO) is a common approach for optimizing the control of assistive devices to account for the wearer's unique biomechanics and subjective preferences. However, despite research suggesting that a person may have a different prioritization of objectives depending on time-varying factors such as the environment, their mood, or energy levels, existing HILO approaches only consider a single objective or enforce a fixed weighting on a set of objectives.

## Related
<!-- [[other-paper-citekey]] -->
