---
citekey: "harlacherCADBasedRelationLearningGeometricSymbolicPlanningAssembly2026"
title: "CAD-Based Relation Learning and Geometric-Symbolic Planning for Robotic Assembly"
authors: ["Fabian Harlacher", "Christian Friedrich"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.17263"
doi: "10.48550/arXiv.2609.17263"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# CAD-Based Relation Learning and Geometric-Symbolic Planning for Robotic Assembly

> Fabian Harlacher, Christian Friedrich · 2026
> [arXiv](https://arxiv.org/abs/2609.17263) · [PDF](https://arxiv.org/pdf/2609.17263)

## Abstract

Assembly Sequence Planning (ASP) remains a challenging problem due to its combinatorial nature, making exhaustive planning approaches impractical for complex industrial assemblies. Furthermore, many CAD models lack reliable semantic contact information or require extensive manual preprocessing, limiting the applicability of existing methods. This paper presents a hybrid ASP framework combining learning-based relation extraction with geometric-symbolic reasoning to generate feasible robotic disassembly sequences from imperfect CAD data. A neural network predicts semantic geometric relations from point clouds, while human-in-the-loop verification enables correction of uncertain predictions and planning failures. Extracted relations are transformed into a symbolic assembly graph, enabling a geometric-symbolic planner to efficiently compute locally valid sets of robotic manipulation primitives. A visibility-based ray-casting strategy guides the search for feasible disassembly directions without requiring an exhaustive combinatorial search, while the local solution space enables efficient sequence optimization. The framework is evaluated on an introduced assembly dataset and on the ASAP test dataset. On the ASAP test dataset, the proposed planner achieves an 85.83% planning success rate while reducing the median planning time by more than one order of magnitude across all assembly sizes and by more than a factor of 50 for assemblies with more than 30 components compared to the baseline. The results demonstrate that the proposed hybrid framework enables efficient robotic assembly sequence planning from imperfect CAD data while substantially reducing planning time. By combining learning-based feature segmentation, human-in-the-loop verification, and geometric-symbolic reasoning, the framework provides a practical foundation for scalable and adaptable robotic assembly and disassembly planning.

## TL;DR

Assembly Sequence Planning (ASP) remains a challenging problem due to its combinatorial nature, making exhaustive planning approaches impractical for complex industrial assemblies. Furthermore, many CAD models lack reliable semantic contact information or require extensive manual preprocessing, limiting the applicability of existing methods.

## Related
<!-- [[other-paper-citekey]] -->
