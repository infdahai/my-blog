---
citekey: "xuInteractionStiffnessGuidedBasisAllocationDynamicMovementPrimitives2026"
title: "Interaction-Stiffness-Guided Basis Allocation in Dynamic Movement Primitives for Efficient Skill Transfer"
authors: ["Chan Xu", "Silu Chen", "Dehao Wang", "Xiyu Chen", "Dexin Jiang", "Chi Zhang", "Guilin Yang", "Chenguang Yang", "Zaojun Fang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01288"
doi: "10.48550/arXiv.2610.01288"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Interaction-Stiffness-Guided Basis Allocation in Dynamic Movement Primitives for Efficient Skill Transfer

> Chan Xu, Silu Chen, Dehao Wang, Xiyu Chen, Dexin Jiang, Chi Zhang, Guilin Yang, Chenguang Yang, Zaojun Fang · 2026
> [arXiv](https://arxiv.org/abs/2610.01288) · [PDF](https://arxiv.org/pdf/2610.01288)

## Abstract

Dynamic Movement Primitives (DMPs) provide a compact and stable formulation for trajectory representation and generalization in robot skill learning. However, their predefined basis layout limits the allocation of approximation capacity according to stage-dependent precision requirements. To address this issue, this article proposes Stage-Criticality-Guided Dynamic Movement Primitives (SC-DMPs) with adaptive basis allocation for precision-critical skill learning. Operator-robot interaction stiffness and a trajectory-consistency cue derived from cross-demonstration task-space variability are integrated to construct a stage-criticality index. Guided by this index, basis centers are redistributed in normalized time through inverse cumulative criticality and mapped to the canonical phase domain, while their bandwidths are refined to adjust local approximation support. This enables denser and more flexible representation at high-criticality stages while retaining sparser allocation elsewhere. Experiments on handwriting trajectories and three real-robot tasks show that the inferred criticality is concentrated in geometrically demanding and task-constrained regions. Comparisons with DMPs, ProMPs, ProDMP, GP-MP, and KMP demonstrate improved trajectory reproduction, endpoint generalization, and task-critical accuracy while retaining a compact model and the stable structure of classical DMPs.

## TL;DR

Dynamic Movement Primitives (DMPs) provide a compact and stable formulation for trajectory representation and generalization in robot skill learning. However, their predefined basis layout limits the allocation of approximation capacity according to stage-dependent precision requirements.

## Related
<!-- [[other-paper-citekey]] -->
