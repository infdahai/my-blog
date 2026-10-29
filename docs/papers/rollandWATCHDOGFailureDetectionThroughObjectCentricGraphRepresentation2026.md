---
citekey: "rollandWATCHDOGFailureDetectionThroughObjectCentricGraphRepresentation2026"
title: "Robot-WATCHDOG : failure detection through object-centric graph representation"
authors: ["Quentin Rolland", "Fabrice Mayran de Chamisso", "Jean-Baptiste Mouret"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13403"
doi: "10.48550/arXiv.2610.13403"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Robot-WATCHDOG : failure detection through object-centric graph representation

> Quentin Rolland, Fabrice Mayran de Chamisso, Jean-Baptiste Mouret · 2026
> [arXiv](https://arxiv.org/abs/2610.13403) · [PDF](https://arxiv.org/pdf/2610.13403)

## Abstract

Reliable real-time failure detection is critical for deploying learned robotic policies, yet defining failures explicitly is infeasible in open-world settings. This motivates failure detection from nominal demonstrations alone. Existing methods, however, struggle to balance robustness to benign variations with the ability to capture semantic and interaction-level errors. We introduce Robot-WATCHDOG, a self-supervised framework that models manipulation scenes as object-centric spatio-temporal graphs. Building on this representation, we investigate two complementary failure scores: Trajectory Projection and Correlation (TPC), a non-parametric measure of geometric deviation and relational consistency, and GnnT, a Graph Attention Network with a Transformer that predicts future object states. We evaluate both on a public benchmark and on a new dataset of semantically complex manipulation tasks, across six tasks and ten random seeds. Both scores outperform image-based failure detectors, particularly on semantic and interaction-level failures. TPC provides the strongest performance in AUPR and MCC on both dataset averages, with low variance across seeds. Qualitative results are made available at https://cea-list.github.io/Robot-WATCHDOG/.

## TL;DR

Reliable real-time failure detection is critical for deploying learned robotic policies, yet defining failures explicitly is infeasible in open-world settings. This motivates failure detection from nominal demonstrations alone.

## Related
<!-- [[other-paper-citekey]] -->
