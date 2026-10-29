---
citekey: "liuUMRUniversalManipulationRepresentation2026"
title: "UMR: Universal Manipulation Representation"
authors: ["Song Liu", "Linyi Li", "Yanshun Zhao", "Rxuan Li", "Xinrui Xu", "Yi Ju", "Yahui Deng", "Senge Zhang", "Guoyu Liu", "Yixuan Li", "Wuyang Zhang", "Yao Li", "Congcong Zhu", "Jingrun Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34256"
doi: "10.48550/arXiv.2609.34256"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# UMR: Universal Manipulation Representation

> Song Liu, Linyi Li, Yanshun Zhao, Rxuan Li, Xinrui Xu, Yi Ju, Yahui Deng, Senge Zhang, Guoyu Liu, Yixuan Li, Wuyang Zhang, Yao Li, Congcong Zhu, Jingrun Chen · 2026
> [arXiv](https://arxiv.org/abs/2609.34256) · [PDF](https://arxiv.org/pdf/2609.34256)

## Abstract

General-purpose embodied manipulation hinges on a unified action representation that generalizes across embodiments and scales readily. Yet existing policies rely on embodiment-specific action spaces, making cross-embodiment demonstrations difficult to leverage at scale and limiting transfer to new embodiments and spatial variations. To this end, we introduce Universal Manipulation Representation (UMR), a unified action representation that enables zero-shot skill transfer from human demonstrations to heterogeneous robots. UMR decomposes manipulation into two functionally distinct yet geometrically linked components: embodiment-agnostic World Flow, which describes task-relevant object motion in the world frame, and Ego Trajectory, which represents end-effector motion relative to the current pose. We instantiate UMR as World--Ego Point VLA (WEPVLA), a compact 0.5B-parameter policy that learns in the unified geometric action space through a dual-stream Point Action Adapter and a unified Point Action Expert, with an $SE(3)$ conjugation coupling the two components. To improve data efficiency, we complement UMR with a Data-Efficient Strategy (DES) that diversifies object configurations through stage-aware point-cloud editing while preserving demonstrated contact geometry. In simulation, WEPVLA achieves average success rates of 97.5\% on LIBERO and 85.7\% on the 10-task RLBench benchmark. In real-world experiments, a single policy trained on human demonstrations augmented by DES transfers zero-shot to diverse deployment conditions. With about 10 minutes of collected human demonstrations per task and no robot demonstrations, it achieves 91.7\% average success across six evaluation settings, compared with 60.8\% for HumanEgo. Code and additional materials are available at https://umr-wepvla.github.io/.

## TL;DR

General-purpose embodied manipulation hinges on a unified action representation that generalizes across embodiments and scales readily. Yet existing policies rely on embodiment-specific action spaces, making cross-embodiment demonstrations difficult to leverage at scale and limiting transfer to new embodiments and spatial variations.

## Related
<!-- [[other-paper-citekey]] -->
