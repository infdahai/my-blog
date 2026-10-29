---
citekey: "jinDynaForgePlanningGuidedResidualLearningDynamicManipulationDemonstration2026"
title: "DynaForge: Planning-Guided Residual Learning for Dynamic Manipulation Demonstration Generation"
authors: ["Yiyang Jin", "Yu Zheng", "Xiao He", "Hesheng Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25631"
doi: "10.48550/arXiv.2609.25631"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# DynaForge: Planning-Guided Residual Learning for Dynamic Manipulation Demonstration Generation

> Yiyang Jin, Yu Zheng, Xiao He, Hesheng Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.25631) · [PDF](https://arxiv.org/pdf/2609.25631)

## Abstract

Dynamic object manipulation is essential for robots operating in real-world environments, yet methods for generating high-quality demonstrations remain limited. Methods designed for static tasks do not readily transfer to dynamic settings. Among dynamic demonstration generators, planning-based methods can fail near contact, while DOMINO-style replay simplifies dynamic interactions and may limit the experience available for policy learning. We present DynaForge, a planning-guided framework that learns residual corrections for dynamic manipulation demonstration generation. DynaForge combines low-frequency global planning with high-frequency object-centric inverse kinematics across task phases, and applies a residual policy to correct actions during dynamic interaction. An implicit curriculum groups rollouts under matched conditions and selects mixed-success groups, focusing residual reinforcement learning on the evolving competence frontier. On Can and Bottle, it uses 0.73x as many optimizer steps as vanilla GRPO at the same nominal environment-step budget, with higher observed final success rates. Across nine simulation tasks, DynaForge increases mean demonstration-generation success from 41.30% of the planning prior to 78.37%. With 800 demonstrations per task, DP3 policies trained on DynaForge data achieve 49.11% mean success, compared with 7.07% for DOMINO data. On three real-world dynamic tasks, DynaForge-trained policies achieve 30-60% success, compared with 0-10% for DOMINO-trained policies, showing the ability of DynaForge for sim-to-real transfer.

## TL;DR

Dynamic object manipulation is essential for robots operating in real-world environments, yet methods for generating high-quality demonstrations remain limited. Methods designed for static tasks do not readily transfer to dynamic settings.

## Related
<!-- [[other-paper-citekey]] -->
