---
citekey: "naiWholeBodyUMITransferringUMIManipulationSkillsHumanoid2026"
title: "Whole-Body UMI: Transferring UMI Manipulation Skills to Humanoid Whole-Body Manipulation via Real-Time Motion Generation"
authors: ["Yuxuan Nai", "Leixin Chang", "Liangjing Yang", "Shuo Yang", "Zhongyu Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22829"
doi: "10.48550/arXiv.2609.22829"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Whole-Body UMI: Transferring UMI Manipulation Skills to Humanoid Whole-Body Manipulation via Real-Time Motion Generation

> Yuxuan Nai, Leixin Chang, Liangjing Yang, Shuo Yang, Zhongyu Li · 2026
> [arXiv](https://arxiv.org/abs/2609.22829) · [PDF](https://arxiv.org/pdf/2609.22829)

## Abstract

Collecting whole-body demonstrations for humanoid manipulation mostly relies on teleoperation, which is costly and hard to scale up. The Universal Manipulation Interface (UMI) provides a scalable data collection paradigm, but end-effector trajectories alone underdetermine humanoid whole-body coordination, which is insufficient for whole-body demonstration collection. Therefore, we introduce Whole-Body UMI (WB-UMI), a task-agnostic, real-time and end-effector conditioned motion generator that decouples whole-body coordination learning from task semantics learning through a shared end-effector interface. A diffusion policy learns from native UMI demonstrations, while WB-UMI learns independently from retargeted motion capture, requiring no body trackers or paired image--whole-body demonstrations during task-specific data collection. In real deployment, an asynchronous hierarchy integrates the diffusion policy, motion generator, and a whole-body controller with latency compensation and measured-state feedback. Real-robot experiments on G1 support real-time closed-loop transfer across four tasks, achieving 90% success in drawer closing, 80% in shelf pick-and-place, 30% in ball toss, and 40% in Loco-PnP, which shows the effectiveness of this hierarchy in transferring native UMI skills to humanoid whole-body manipulation.

## TL;DR

Collecting whole-body demonstrations for humanoid manipulation mostly relies on teleoperation, which is costly and hard to scale up. The Universal Manipulation Interface (UMI) provides a scalable data collection paradigm, but end-effector trajectories alone underdetermine humanoid whole-body coordination, which is insufficient for whole-body demonstration collection.

## Related
<!-- [[other-paper-citekey]] -->
