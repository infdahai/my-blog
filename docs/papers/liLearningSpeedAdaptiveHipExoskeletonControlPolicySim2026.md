---
citekey: "liLearningSpeedAdaptiveHipExoskeletonControlPolicySim2026"
title: "Learning a Speed-adaptive Hip Exoskeleton Control Policy Via Sim-to-real Reinforcement Learning"
authors: ["Bin Li", "Zhimin Hou", "Jiacheng Hou", "Zenian Liang", "Tong Wu", "Teng Ma", "Chenglong Fu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28027"
doi: "10.48550/arXiv.2609.28027"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# Learning a Speed-adaptive Hip Exoskeleton Control Policy Via Sim-to-real Reinforcement Learning

> Bin Li, Zhimin Hou, Jiacheng Hou, Zenian Liang, Tong Wu, Teng Ma, Chenglong Fu · 2026
> [arXiv](https://arxiv.org/abs/2609.28027) · [PDF](https://arxiv.org/pdf/2609.28027)

## Abstract

Providing personalized exoskeleton assistance across varying walking speeds remains challenging. Existing online optimization methods are sample-inefficient, requiring extensive human-in-the-loop (HIL) evaluations to optimize the entire assistive torque profile. Sim-to-real reinforcement learning (RL) offers a promising alternative but cannot directly account for individual user preferences. We propose a framework integrating sim-to-real RL with online preference learning for personalized exoskeleton assistance. Specifically, assistance timing is learned in simulation by training RL policies with human musculoskeletal models across varying walking speeds. The learned policies are then distilled and deployed on a physical hip exoskeleton using onboard sensory observations. Gaussian-process-based preference learning further personalizes the assistance magnitude through pairwise user comparisons. By decoupling assistance timing learning in simulation from magnitude optimization in real-world experiments, our framework substantially reduces the online optimization space. Human-subject experiments demonstrate efficient identification of personalized assistive torque profiles across varying walking speeds with fewer real-world evaluations.

## TL;DR

Providing personalized exoskeleton assistance across varying walking speeds remains challenging. Existing online optimization methods are sample-inefficient, requiring extensive human-in-the-loop (HIL) evaluations to optimize the entire assistive torque profile.

## Related
<!-- [[other-paper-citekey]] -->
