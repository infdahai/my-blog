---
citekey: "xuSLoSaSmallLowPowerSafeFoundationModelsTask2026"
title: "SLoSa: Small, Low-Power, and Safe Foundation Models for Robotic Task Planning"
authors: ["Weizhe Xu", "Jialiang Fan", "Essien Taylor", "Zijun Wang", "Russell Joseph", "Fanxin Kong"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28955"
doi: "10.48550/arXiv.2610.28955"
tags: [paper, embodied-ai, "cs.AI", "cs.LO", "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# SLoSa: Small, Low-Power, and Safe Foundation Models for Robotic Task Planning

> Weizhe Xu, Jialiang Fan, Essien Taylor, Zijun Wang, Russell Joseph, Fanxin Kong · 2026
> [arXiv](https://arxiv.org/abs/2610.28955) · [PDF](https://arxiv.org/pdf/2610.28955)

## Abstract

Safe robotic task planning requires planners that can reliably achieve task goals while satisfying safety constraints. Classical planners search over explicit symbolic task representations and can provide formal guarantees with respect to encoded safety constraints, but require rigid input formats. Their computational cost also increases rapidly with the search space. In contrast, large language models (LLMs) offer flexible task interfaces and strong generalization capabilities, but they are large, power-hungry, and pre-trained with little robot-specific safety data and knowledge. Thus, they can be difficult to deploy locally on robotic systems with limited resources. To address these limitations, we present SLoSa, a neuro-symbolic compression and fine-tuning framework for training foundation-model-based robotic task planners with Small size, Low power demand, and Safety awareness. The framework first constructs a safety-aware dataset using classical planners, an advanced teacher LLM, and formal verifiers, followed by two training stages: supervised fine-tuning and reinforcement learning (RL) fine-tuning guided by a verification-based reward machine to enforce safety alignment. We evaluate SLoSa across four Planning Domain Definition Language (PDDL) domains, two household simulation environments, local edge platforms, and a desktop robotic arm. Across the PDDL tasks, verifier-guided post-training raises the success rate of compact 4B-14B planners to 70.5-76.0%, while INT4 deployment on a Jetson Orin requires 17.85-26.41 W of average power. Results in household simulators and on the physical robot further demonstrate the applicability of SLoSa across diverse robotic task settings.

## TL;DR

Safe robotic task planning requires planners that can reliably achieve task goals while satisfying safety constraints. Classical planners search over explicit symbolic task representations and can provide formal guarantees with respect to encoded safety constraints, but require rigid input formats.

## Related
<!-- [[other-paper-citekey]] -->
