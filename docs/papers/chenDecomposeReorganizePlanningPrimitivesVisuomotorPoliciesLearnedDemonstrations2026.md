---
citekey: "chenDecomposeReorganizePlanningPrimitivesVisuomotorPoliciesLearnedDemonstrations2026"
title: "Decompose and Reorganize: Planning with Primitives and Visuomotor Policies Learned from Demonstrations"
authors: ["Yizhou Chen", "Hang Xu", "Dongjie Yu", "Yupu Lu", "Tengye Xu", "Zeqing Zhang", "Wei Zhang", "Yi Ren", "Ben M. Chen", "Jia Pan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.25397"
doi: "10.48550/arXiv.2607.25397"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Decompose and Reorganize: Planning with Primitives and Visuomotor Policies Learned from Demonstrations

> Yizhou Chen, Hang Xu, Dongjie Yu, Yupu Lu, Tengye Xu, Zeqing Zhang, Wei Zhang, Yi Ren, Ben M. Chen, Jia Pan · 2026
> [arXiv](https://arxiv.org/abs/2607.25397) · [PDF](https://arxiv.org/pdf/2607.25397)

## Abstract

Successfully automating dexterous, long-horizon robotic manipulation requires frameworks capable of both high-level reasoning and fine-grained execution. Traditional task and motion planning (TAMP), while excellent at symbolic planning, is often brittle in contact-rich operations. Simultaneously, imitation learning (IL), while effective in manipulation tasks with visual feedback, is limited by its low capability in spatial generalization and multi-stage operation. To reconcile their complementary strengths and limitations, we propose DR-LfD (Decomposed and Reorganized Skills Learned from Demonstrations), a framework that seamlessly integrates visuomotor policies into a TAMP-gated decision-making system. Based on contact relationships, DR-LfD decomposes human demonstrations into atomic skills, which are reproduced as visuomotor policies or object-centric primitives. The initiation, termination, and constraints of the visuomotor policies are carefully modeled and implemented in a TAMP-compatible form, enabling reorganization of skills learned from different sources. DR-LfD transforms the learning problem from one requiring exponential demonstration data over possible skill sequences to one whose demonstration burden scales with the number of distinct skill types, with limited data for each skill. Through comprehensive real-world and simulation benchmarking across diverse scenarios, we demonstrate the strong performance of DR-LfD on tasks involving multiple steps, unseen setups, and physical constraints. Project website: https://dr-lfd.github.io/DR-LfD-website.

## TL;DR

Successfully automating dexterous, long-horizon robotic manipulation requires frameworks capable of both high-level reasoning and fine-grained execution. Traditional task and motion planning (TAMP), while excellent at symbolic planning, is often brittle in contact-rich operations.

## Related
<!-- [[other-paper-citekey]] -->
