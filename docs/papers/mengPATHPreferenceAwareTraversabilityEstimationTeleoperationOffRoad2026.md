---
citekey: "mengPATHPreferenceAwareTraversabilityEstimationTeleoperationOffRoad2026"
title: "PATH: Preference-Aware Traversability Estimation for Robotic Teleoperation in Off-Road Navigation"
authors: ["Xianghao Meng", "Wenshuo Wang", "Cheng Shao", "Lewei Feng", "Qingxiao Liu", "Canyu Wang", "Junqiang Xi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.30605"
doi: "10.48550/arXiv.2610.30605"
tags: [paper, embodied-ai, "cs.HC", "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# PATH: Preference-Aware Traversability Estimation for Robotic Teleoperation in Off-Road Navigation

> Xianghao Meng, Wenshuo Wang, Cheng Shao, Lewei Feng, Qingxiao Liu, Canyu Wang, Junqiang Xi · 2026
> [arXiv](https://arxiv.org/abs/2610.30605) · [PDF](https://arxiv.org/pdf/2610.30605)

## Abstract

Traversability estimation is critical for ground vehicle teleoperation, yet existing methods often neglect the human operator's preferences for speed and risk tolerance. To address this gap, we propose PATH-Net, a Preference-Aware Traversability estimation Hierarchical Network that adaptively generates preference-conditioned traversability cost maps and speed profiles for off-road teleoperation. Our framework integrates visual and geometric bird's-eye-view features with short-term historical vehicle states through a multi-head shared-backbone architecture. Our PATH-Net infers traversability cost maps while optimizing speed recommendations by using maximum entropy inverse reinforcement learning and sparse speed supervision. Our method incorporates operator preference via an asymmetric feature aggregation mechanism, splitting inference into a cost branch that prioritizes high-risk traversability regions and a speed branch that outputs preference-adjusted recommended speeds. Experiments with 15 operators across 225 teleoperated trajectories show alignment with user-specific navigation strategies, achieving modified Hausdorff distance of 0.17 m (aggressive) and 0.15 m (conservative). In the questionnaire assessment, participants reported lower NASA-TLX workload scores with PATH-Net recommendations than without recommendations, decreasing from 34.7 to 22.2. These results support preference-conditioned trajectory and speed recommendation for off-road teleoperation.

## TL;DR

Traversability estimation is critical for ground vehicle teleoperation, yet existing methods often neglect the human operator's preferences for speed and risk tolerance. To address this gap, we propose PATH-Net, a Preference-Aware Traversability estimation Hierarchical Network that adaptively generates preference-conditioned traversability cost maps and speed profiles for off-road teleoperation.

## Related
<!-- [[other-paper-citekey]] -->
