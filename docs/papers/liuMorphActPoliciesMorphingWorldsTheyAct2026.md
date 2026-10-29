---
citekey: "liuMorphActPoliciesMorphingWorldsTheyAct2026"
title: "MorphAct: Robot Policies Morphing with the Worlds They Act In"
authors: ["Ziyan Liu", "Jiting Liu", "Weihong Zhong", "Wenda Yu", "Yeqiu Chen", "Jason Li", "Xiaojiang Peng", "Shuyuan Hu", "Kai Wang", "Bo Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20019"
doi: "10.48550/arXiv.2610.20019"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# MorphAct: Robot Policies Morphing with the Worlds They Act In

> Ziyan Liu, Jiting Liu, Weihong Zhong, Wenda Yu, Yeqiu Chen, Jason Li, Xiaojiang Peng, Shuyuan Hu, Kai Wang, Bo Zhao · 2026
> [arXiv](https://arxiv.org/abs/2610.20019) · [PDF](https://arxiv.org/pdf/2610.20019)

## Abstract

Progress toward general intelligence in the physical world requires scaling robot learning across diverse environments and interactions. However, existing robot policies use shared parameters that remain fixed across interaction contexts. When different operations favor competing parameter adjustments, fitting their mixture can leave individual operations insufficiently adapted. Our atomic-task diagnostics reveal competing update directions in both vision-language and action parameters, with source-improving updates increasing loss on other tasks. This motivates MorphAct, a contextual parameterization framework that dynamically adjusts robot policy parameters as interaction contexts change. Two coupled generators produce context-dependent low-rank updates for the vision-language and action modules. Their coupling follows the policy's computational dependency: vision-language updates shape the representations that condition action-side parameter generation. Both generators are trained jointly through the native action objective, without operation labels or expert-adapter targets. MorphAct improves performance across three VLA backbones on LIBERO and Meta-World, with gains of up to 16.30%. In real-world evaluation, it achieves gains of up to 14% over $π_{0.5}$. Ablations support the benefits of contextual parameter generation and representation coupling.

## TL;DR

Progress toward general intelligence in the physical world requires scaling robot learning across diverse environments and interactions. However, existing robot policies use shared parameters that remain fixed across interaction contexts.

## Related
<!-- [[other-paper-citekey]] -->
