---
citekey: "leeRAINTaskGeneralizationRegionAwareInteractionNetworks2026"
title: "RAIN: Robotic Task Generalization with Region-Aware Interaction Networks"
authors: ["Seunghun Lee", "Kyuhwan Shim", "Yeogyeong Song", "Seung Hwan Kim", "Sihaeng Lee", "Byoung-Tak Zhang", "Sunghoon Im", "Gunhee Lee"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14039"
doi: "10.48550/arXiv.2610.14039"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# RAIN: Robotic Task Generalization with Region-Aware Interaction Networks

> Seunghun Lee, Kyuhwan Shim, Yeogyeong Song, Seung Hwan Kim, Sihaeng Lee, Byoung-Tak Zhang, Sunghoon Im, Gunhee Lee · 2026
> [arXiv](https://arxiv.org/abs/2610.14039) · [PDF](https://arxiv.org/pdf/2610.14039)

## Abstract

Existing vision-language-action (VLA) models benefit from large-scale vision-language pretraining, but tend to memorize training trajectories, limiting their ability to adapt learned interactions to new task and scene configurations. To address this problem, we propose \textbf{Region-Aware Interaction Networks (RAIN)}, which formulates a task as a sequence of goal-conditioned subtasks, each specified by an action type and a target-region mask. This formulation allows learned skills to be reused across different objects and scene layouts and composed into task sequences not seen during training. Its Target-adaptive Cross-View Encoder (TCE) conditions multi-view features on target masks and exchanges information across views, while PlanDiT predicts target-directed trajectories and actions. A Transition Head estimates subtask completion to enable automatic transitions. We also introduce a \textbf{Reference-based Retargeting Strategy (RRS)}, which uses recorded trajectories to synthesize smooth approaches to reference interactions with alternative target regions, without collecting additional data. Experiments on \textbf{LIBERO-Analogy}, our new benchmark for robotic task generalization, and real-world tabletop tasks demonstrate that RAIN generalizes more robustly than existing VLA baselines.

## TL;DR

Existing vision-language-action (VLA) models benefit from large-scale vision-language pretraining, but tend to memorize training trajectories, limiting their ability to adapt learned interactions to new task and scene configurations. To address this problem, we propose \textbf{Region-Aware Interaction Networks (RAIN)}, which formulates a task as a sequence of goal-conditioned subtasks, each specified by an action type and a target-region mask.

## Related
<!-- [[other-paper-citekey]] -->
