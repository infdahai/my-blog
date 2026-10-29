---
citekey: "weiMUCOManiUnitStructuredManipulationFrameworkCompositionalLong2026"
title: "MUCO: A Mani-Unit-Structured Manipulation Framework for Compositional Long-Horizon Robot Tasks"
authors: ["Xiangyi Wei", "Hanzhe Yao", "Jingwen Shang", "Zhenhong Wu", "Yang Li", "Changbo Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19913"
doi: "10.48550/arXiv.2610.19913"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# MUCO: A Mani-Unit-Structured Manipulation Framework for Compositional Long-Horizon Robot Tasks

> Xiangyi Wei, Hanzhe Yao, Jingwen Shang, Zhenhong Wu, Yang Li, Changbo Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.19913) · [PDF](https://arxiv.org/pdf/2610.19913)

## Abstract

Learning and executing long-horizon robot manipulation as complete task trajectories raises data-collection costs, lim?its capability reuse, and causes local failures to cascade into later task stages. We introduce manipulation units (MUs) as reusable operations, each defined by a local goal, an initi?ation condition, and observable success and failure criteria. MUs are learned and verified individually. During execution, consecutive MUs remain coupled through shared environ?ment dynamics. We formulate MU-Structured Manipulation (MUSM) and realize it through MU-Centric Orchestration (MUCO). Given language and vision, MUCO constructs an MU sequence, matches each MU to compatible policy models in a frozen capability registry, and dispatches the model with the highest calibrated success rate. Visual verification checks MU outcomes against success and failure criteria and governs transitions, enabling retry or fallback to another model from the current state without re-executing verified MUs. Canonical keys enable checkpoint reuse for equivalent MUs across tasks without new demonstrations or updates. We evaluate MUCO on RLBench, RoboTwin 2.0, and five real-world tasks. MUCO achieves higher complete-task success and verified progress, stronger failure containment, and lower error propagation than baselines. Results demonstrate cross-task MU reuse and het?erogeneous policy composition without joint training, shared backbones, or common action representations.

## TL;DR

Learning and executing long-horizon robot manipulation as complete task trajectories raises data-collection costs, lim?its capability reuse, and causes local failures to cascade into later task stages. We introduce manipulation units (MUs) as reusable operations, each defined by a local goal, an initi?ation condition, and observable success and failure criteria.

## Related
<!-- [[other-paper-citekey]] -->
