---
citekey: "mengLTLDiffFiniteLinearTemporalLogicGuidedDataGeneration2026"
title: "LTLDiff: Finite Linear Temporal Logic-Guided Data Generation and Diffusion Policies for Multi-agent Robotic Manipulation"
authors: ["Chuhan Meng", "Haiyan Yin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11043"
doi: "10.48550/arXiv.2609.11043"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# LTLDiff: Finite Linear Temporal Logic-Guided Data Generation and Diffusion Policies for Multi-agent Robotic Manipulation

> Chuhan Meng, Haiyan Yin · 2026
> [arXiv](https://arxiv.org/abs/2609.11043) · [PDF](https://arxiv.org/pdf/2609.11043)

## Abstract

Multi-agent robotic manipulation tasks require coordination among agents to satisfy task-level temporal, logical, and safety constraints. Recently, diffusion policies have been used to perform the task. However, they still suffer from desynchronization, incorrect action ordering, and coordination failures in tasks that require simultaneous or sequential multi-agent interaction. Therefore, LTLDiff is proposed as a framework that combines Finite Linear Temporal Logic (LTLf) specification learning for both the generation of demonstrations and learning via diffusion policies. Each task has a specific LTLf formula that is learned from a set of natural language instructions using a large-scale language model. To enable a fixed-dimensional vector embedding of the learned specification from the language model, LTLf uses an abstract syntax tree representation scheme. This embedding of logic serves as a condition for (i) logic-guided data collection and (ii) diffusion-based policy training, encouraging trajectories that are consistent with the desired ordering and coordination requirements. Experiments on multi-agent LTLDiff manipulation tasks demonstrate improved task success rates compared to the baseline. Together, these contributions demonstrate the effectiveness of LTLDiff for coordinated multi-agent manipulation.

## TL;DR

Multi-agent robotic manipulation tasks require coordination among agents to satisfy task-level temporal, logical, and safety constraints. Recently, diffusion policies have been used to perform the task.

## Related
<!-- [[other-paper-citekey]] -->
