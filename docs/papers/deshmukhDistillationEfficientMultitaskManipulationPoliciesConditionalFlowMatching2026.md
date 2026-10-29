---
citekey: "deshmukhDistillationEfficientMultitaskManipulationPoliciesConditionalFlowMatching2026"
title: "Distillation for Efficient Multitask Manipulation Policies via Conditional Flow Matching"
authors: ["Shreya Deshmukh", "Imen Mahdi", "Nick Heppert", "Abhinav Valada"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28107"
doi: "10.48550/arXiv.2609.28107"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# Distillation for Efficient Multitask Manipulation Policies via Conditional Flow Matching

> Shreya Deshmukh, Imen Mahdi, Nick Heppert, Abhinav Valada · 2026
> [arXiv](https://arxiv.org/abs/2609.28107) · [PDF](https://arxiv.org/pdf/2609.28107)

## Abstract

Advances in generative modeling have recently been extensively employed in robotics for policy learning. In particular, Conditional Flow Matching (CFM) trained with expert demonstrations has been shown to outperform existing methods on robot manipulation benchmarks. While prior work has mainly focused on single-task settings, we study the problem from a multi-task perspective, as training independent models for each task is computationally expensive. Multi-Task policy learning comes with its own set of challenges, as naively training on a concatenated dataset of demonstrations would either require increased model capacity to accommodate the added complexity or result in drops in performance. We propose to distill knowledge from single-task CFM experts into a shared multi-task policy by transferring their learned velocity fields. We combine this distillation signal with the original CFM objective to retain fidelity to the demonstrations. Experiments on RLBench show that our approach improves multi-task policy performance over naive training while maintaining a fixed model size.

## TL;DR

Advances in generative modeling have recently been extensively employed in robotics for policy learning. In particular, Conditional Flow Matching (CFM) trained with expert demonstrations has been shown to outperform existing methods on robot manipulation benchmarks.

## Related
<!-- [[other-paper-citekey]] -->
