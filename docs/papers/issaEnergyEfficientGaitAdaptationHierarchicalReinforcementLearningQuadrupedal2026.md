---
citekey: "issaEnergyEfficientGaitAdaptationHierarchicalReinforcementLearningQuadrupedal2026"
title: "Energy-Efficient Gait Adaptation via Hierarchical Reinforcement Learning for Quadrupedal Locomotion Across Diverse Terrains"
authors: ["Ammar Issa", "Anubhav Singh", "Anton Tsaritsin", "Sergey Kolyubin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.10297"
doi: "10.48550/arXiv.2610.10297"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Energy-Efficient Gait Adaptation via Hierarchical Reinforcement Learning for Quadrupedal Locomotion Across Diverse Terrains

> Ammar Issa, Anubhav Singh, Anton Tsaritsin, Sergey Kolyubin · 2026
> [arXiv](https://arxiv.org/abs/2610.10297) · [PDF](https://arxiv.org/pdf/2610.10297)

## Abstract

While energy efficiency is a critical objective for legged-robot locomotion control, achieving low energy consumption while maintaining robust performance across different velocity ranges and terrain conditions remains a key challenge. This is particularly true for end-to-end RL policies, where gait generation, motion execution, and energy optimization are tightly coupled, leading to high sensitivity to reward design. In this work, we propose a hierarchical reinforcement learning (HRL) framework that separates a high-frequency policy for stable and robust joint-level motion execution from low-frequency gait adaptation that explicitly minimizes the cost of transport (CoT). The three-stage Isaac-based training procedure enables zero-shot sim-to-real transfer with improved tracking accuracy, robustness, and energy efficiency. The learned hierarchy exhibits automatic speed-dependent gait adaptation, transitioning from pacing at low speeds to trotting at higher speeds. We validate the proposed approach in simulation against representative single-policy and hierarchical locomotion baselines, demonstrating reduced CoT over a broad range of commanded velocities, while maintaining robust locomotion across flat, uneven rough, and inclined terrains. We further demonstrate its practical feasibility through zero-shot deployment on a physical Unitree AlienGo quadruped.

## TL;DR

While energy efficiency is a critical objective for legged-robot locomotion control, achieving low energy consumption while maintaining robust performance across different velocity ranges and terrain conditions remains a key challenge. This is particularly true for end-to-end RL policies, where gait generation, motion execution, and energy optimization are tightly coupled, leading to high sensitivity to reward design.

## Related
<!-- [[other-paper-citekey]] -->
