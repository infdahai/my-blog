---
citekey: "yangSameSceneDifferentTaskSkillAlignmentCompositionalGeneralization2026"
title: "Same Scene, Different Task: Skill Alignment for Compositional Generalization in VLAs"
authors: ["Taegeun Yang", "Youngju Na", "Yoonki Cho", "Sung-Eui Yoon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00524"
doi: "10.48550/arXiv.2610.00524"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Same Scene, Different Task: Skill Alignment for Compositional Generalization in VLAs

> Taegeun Yang, Youngju Na, Yoonki Cho, Sung-Eui Yoon · 2026
> [arXiv](https://arxiv.org/abs/2610.00524) · [PDF](https://arxiv.org/pdf/2610.00524)

## Abstract

Vision-language-action (VLA) models often struggle to generalize to skill combinations absent from their fine-tuning demonstrations, even when every constituent skill has been demonstrated. We focus on a vision shortcut as one failure mode: during fine-tuning, visual observations can serve as a proxy for the instruction, so a policy may execute a demonstrated combination associated with similar observations rather than the instructed combination. This motivates training with counterfactual pairs formed by holding a demonstration observation fixed while changing the instruction to specify an undemonstrated combination. These pairs, however, lack corresponding demonstrated action targets. Crucially, the currently required skill has already been demonstrated, but actions from those executions cannot serve as direct targets because the same skill can require different actions across observations. We propose CRAFT, which transfers supervision from demonstrated executions of the required skill to counterfactual pairs using skill representations that can be reused across executions of the same skill. Across three VLA models and two simulation benchmarks, CRAFT improves success on undemonstrated combinations while maintaining high success on demonstrated ones; it also improves compositional generalization on a real robot. Project website: https://taegeunyang.github.io/craft/

## TL;DR

Vision-language-action (VLA) models often struggle to generalize to skill combinations absent from their fine-tuning demonstrations, even when every constituent skill has been demonstrated. We focus on a vision shortcut as one failure mode: during fine-tuning, visual observations can serve as a proxy for the instruction, so a policy may execute a demonstrated combination associated with similar observations rather than the instructed combination.

## Related
<!-- [[other-paper-citekey]] -->
