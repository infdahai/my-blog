---
citekey: "leeTempoBridgeLanguageGuidedTempoControlVisionLanguageAction2026"
title: "TempoBridge: Language-Guided Tempo Control for Vision-Language-Action Policies"
authors: ["Yeonseo Lee", "Hyosup Shin", "Guebin Hwang", "Sungho Jo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09451"
doi: "10.48550/arXiv.2610.09451"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# TempoBridge: Language-Guided Tempo Control for Vision-Language-Action Policies

> Yeonseo Lee, Hyosup Shin, Guebin Hwang, Sungho Jo · 2026
> [arXiv](https://arxiv.org/abs/2610.09451) · [PDF](https://arxiv.org/pdf/2610.09451)

## Abstract

Vision-Language-Action (VLA) models are effective at understanding what task to perform, but provide limited control over how it should be executed, such as moving quickly or slowly. We introduce TempoBridge, a lightweight framework that uses frozen VLA representations to modulate actions according to tempo cues in the instruction at each task phase, without additional tempo-conditioned robot demonstrations or tempo-specific base-policy fine-tuning. TempoBridge extracts tempo cues from contextual VLM representations, aligns them with task progress through a causal phase router, and modulates nominal motion commands during execution. Across LIBERO tasks, TempoBridge improves Tempo Success Rate from 52.6% to 89.7% under canonical tempo instructions while retaining high task success. It also preserves near-baseline performance when no tempo cue is present and generalizes to unseen tempo expressions without additional training. Experiments on a physical robot further demonstrate language-conditioned tempo modulation in real-world manipulation.

## TL;DR

Vision-Language-Action (VLA) models are effective at understanding what task to perform, but provide limited control over how it should be executed, such as moving quickly or slowly. We introduce TempoBridge, a lightweight framework that uses frozen VLA representations to modulate actions according to tempo cues in the instruction at each task phase, without additional tempo-conditioned robot demonstrations or tempo-specific base-policy fine-tuning.

## Related
<!-- [[other-paper-citekey]] -->
