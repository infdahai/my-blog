---
citekey: "zhangEgoForesightEffectivelyScalingPolicyLearningNoisyEgocentricActions2026"
title: "EgoForesight: Effectively Scaling Policy Learning with Noisy Egocentric Actions"
authors: ["Chubin Zhang", "Changyuan Wang", "Yirui Wang", "Ao Li", "Shilin Ma", "Yue Su", "Cai Zhou", "Xiuwei Xu", "Tianle Zhang", "Yansong Tang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31845"
doi: "10.48550/arXiv.2610.31845"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# EgoForesight: Effectively Scaling Policy Learning with Noisy Egocentric Actions

> Chubin Zhang, Changyuan Wang, Yirui Wang, Ao Li, Shilin Ma, Yue Su, Cai Zhou, Xiuwei Xu, Tianle Zhang, Yansong Tang · 2026
> [arXiv](https://arxiv.org/abs/2610.31845) · [PDF](https://arxiv.org/pdf/2610.31845)

## Abstract

Scaling policy learning requires broad experience and reliable supervision. Robot demonstrations provide high-quality trajectory supervision but are costly to collect. Egocentric videos broaden task and environment coverage, yet motion reconstruction and retargeting introduce noisy action labels. To address this challenge, we introduce EgoForesight, a vision-language-action framework that learns jointly from both sources by reducing the influence of unreliable action labels and exploiting demonstrated outcomes as complementary supervision. A joint vision-action flow couples future visual representation prediction with action generation, unifying reliability-aware action learning with outcome-informed representation transfer. Specifically, reliability-conditioned corruption allocates action supervision across noise levels according to source reliability, while reliability-weighted regression regulates each source's contribution. Complementing this treatment of noisy labels, privileged-future representation distillation draws supervision from demonstrated outcomes. An exponential-moving-average teacher observes the current scene and clean future to encode action-relevant structure from the resulting scene change. Its deeper representations supervise an earlier student layer receiving a corrupted future, providing outcome-informed structure beyond noisy action annotations. Together, these mechanisms support effective scaling with noisy egocentric actions. Over the tested range, EgoForesight exhibits steeper scaling slopes than the baseline, reducing real-world open-loop action MSE by 20.5% and improving RoboCasa few-shot success by 8.1 percentage points at 30,000 hours of pretraining data. After post-training, it also achieves strong absolute performance in both simulated and real-world dexterous manipulation.

## TL;DR

Scaling policy learning requires broad experience and reliable supervision. Robot demonstrations provide high-quality trajectory supervision but are costly to collect.

## Related
<!-- [[other-paper-citekey]] -->
