---
citekey: "gimenezFlowPoliciesActionsSkillLevelWorldModelsLearned2026"
title: "Flow Policies as Actions of Skill-Level World Models: Learned and Symbolic Abstractions for Long-Horizon Planning"
authors: ["Andreu Matoses Gimenez", "Andrei-Carlo Papuc", "Chris Pek", "Javier Alonso-Mora"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04767"
doi: "10.48550/arXiv.2610.04767"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Flow Policies as Actions of Skill-Level World Models: Learned and Symbolic Abstractions for Long-Horizon Planning

> Andreu Matoses Gimenez, Andrei-Carlo Papuc, Chris Pek, Javier Alonso-Mora · 2026
> [arXiv](https://arxiv.org/abs/2610.04767) · [PDF](https://arxiv.org/pdf/2610.04767)

## Abstract

Latent world models enable robots to plan by predicting the consequences of actions. Planning long tasks with control-rate actions requires many prediction steps, which enlarges the search space and accumulates error. Skill-level actions shorten these sequences, but a symbolic skill vocabulary requires domain knowledge and labeled demonstrations. We construct skill-level actions from the inputs of a flow-matching policy trained on demonstrations segmented into complete skills. The policy maps a noise seed and an observation, optionally with a code or label, to a complete skill execution, so one execution is one world-model transition. On this mechanism we propose four action abstractions with increasing task knowledge: a compressed seed, two discrete codes learned from the demonstrations, and a symbolic label. We evaluate them with a common world-model training procedure and planning framework on simulated block rearrangement tasks that require up to 14 sequential skills. The symbolic label succeeds in over 90% of the tasks that require up to six skills and degrades beyond. Without any label, an object-centric learned code matches it on single-skill tasks and retains half to three quarters of its success on tasks of two to five skills. Ablations attribute much of the label's advantage to its planner knowing which actions are applicable, rather than to the label itself. Beyond six skills the search, not the world model, limits success. Project page: https://andreumatoses.github.io/research/flow-skill-wm

## TL;DR

Latent world models enable robots to plan by predicting the consequences of actions. Planning long tasks with control-rate actions requires many prediction steps, which enlarges the search space and accumulates error.

## Related
<!-- [[other-paper-citekey]] -->
