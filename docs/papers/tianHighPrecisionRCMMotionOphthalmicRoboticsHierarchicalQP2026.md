---
citekey: "tianHighPrecisionRCMMotionOphthalmicRoboticsHierarchicalQP2026"
title: "High-Precision RCM Motion for Ophthalmic Robotics via Hierarchical QP Control and Authority-Guided Recovery Planning"
authors: ["Huanyu Tian", "Adriana Namour", "Lingyun Zeng", "Zicong Wu", "Sebastien Ourselin", "Lyndon da Cruz", "Christos Bergeles"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27905"
doi: "10.48550/arXiv.2610.27905"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# High-Precision RCM Motion for Ophthalmic Robotics via Hierarchical QP Control and Authority-Guided Recovery Planning

> Huanyu Tian, Adriana Namour, Lingyun Zeng, Zicong Wu, Sebastien Ourselin, Lyndon da Cruz, Christos Bergeles · 2026
> [arXiv](https://arxiv.org/abs/2610.27905) · [PDF](https://arxiv.org/pdf/2610.27905)

## Abstract

General-purpose manipulators can position ophthalmic instruments under a software Remote Centre of Motion (RCM). However, at some reachable configurations that are nonsingular for the tip task alone, the RCM and tip-tracking objectives conflict and the servo oscillates. We formalise this failure as a constraint-induced task singularity: the RCM-projected tip Jacobian loses rank while the unprojected tip Jacobian stays well conditioned. Thus, the effective tip authority collapses although the target remains reachable. We present a high-precision RCM servo architecture with built-in singularity recovery: for each commanded target, an authority-guided planner selects a well-conditioned arm configuration that reaches it and plans an RCM-consistent route, executed by a fixed hierarchical-QP controller. On a 200-scenario kinematic benchmark, the complete nominal-and-recovery protocol reaches 128/128 near-singular targets and 71/72 near-joint-limit targets (100% and 99%, respectively), with the software-RCM residual below 0.142 mm. On a physical 6-DOF arm it executes across four RCM entry points, with a worst-case kinematically reconstructed RCM residual of 178 {\mu}m and a median tip-regulation error of 32{\mu}m, within the 200{\mu}m control requirement adopted for the ophthalmic task.

## TL;DR

General-purpose manipulators can position ophthalmic instruments under a software Remote Centre of Motion (RCM). However, at some reachable configurations that are nonsingular for the tip task alone, the RCM and tip-tracking objectives conflict and the servo oscillates.

## Related
<!-- [[other-paper-citekey]] -->
