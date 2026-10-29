---
citekey: "niuMORPHSelfOrganisingMultiTaskAllocationNeuroplasticityInspired2026"
title: "MORPH: Self-Organising Multi-Robot Task Allocation via Neuroplasticity-Inspired Adaptive Topology"
authors: ["Xuezhi Niu", "Didem Gürdür Broo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.32745"
doi: "10.48550/arXiv.2609.32745"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# MORPH: Self-Organising Multi-Robot Task Allocation via Neuroplasticity-Inspired Adaptive Topology

> Xuezhi Niu, Didem Gürdür Broo · 2026
> [arXiv](https://arxiv.org/abs/2609.32745) · [PDF](https://arxiv.org/pdf/2609.32745)

## Abstract

Multi-robot task allocation (MRTA) in dynamic environments faces a fundamental tension: effective coordination requires learned structure, but that structure must adapt when conditions change. Existing methods resolve this by assuming prior task knowledge, a utility function, a cost matrix, or a trained policy making them brittle when deployed without such knowledge or when task distributions shift. We present MORPH(Multi-agent Online Rewiring through Plasticity-guided Hierarchy), a training-free MRTA framework where global allocation quality emerges from 4 local plasticity rules (synaptic, homeostatic, structural, and metaplasticity) applied to a directed pairwise preference matrix updated from runtime co-occurrence and task-completion feedback. MORPH requires no task model, no bid computation, and no offline training; response decisions use learned AGV-to-Picker preferences rather than a fixed proximity rule. Within the Gerkey-Mataric MRTA taxonomy, MORPH is the first method in the single-task, single-robot, instantaneous-assignment class to learn directed pairwise allocation preferences online. Evaluated on the TA-RWARE warehouse benchmark (8-24 agents, 4 maps, 800 steps per episode, 5 seeds), MORPH achieves 110% of all-to-all throughput at N=24 while using only 21% of possible coordination links as an efficiency advantage that grows monotonically with fleet size. Under spatial task distribution shift, MORPH degrades 3x less than proximity-based methods while its learned preferences remain uncorrelated with Manhattan distance. Systematic ablation confirms all four plasticity rules contribute measurably. Two allocation properties emerge without programming: cross-type preference dominance and progressive preference sparsification, mirroring the developmental refinement of biological neural circuits. Learned preferences are driven by task co-occurrence history, not spatial proximity.

## TL;DR

Multi-robot task allocation (MRTA) in dynamic environments faces a fundamental tension: effective coordination requires learned structure, but that structure must adapt when conditions change. Existing methods resolve this by assuming prior task knowledge, a utility function, a cost matrix, or a trained policy making them brittle when deployed without such knowledge or when task distributions shift.

## Related
<!-- [[other-paper-citekey]] -->
