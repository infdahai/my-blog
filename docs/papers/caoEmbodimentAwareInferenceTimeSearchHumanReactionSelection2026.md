---
citekey: "caoEmbodimentAwareInferenceTimeSearchHumanReactionSelection2026"
title: "Embodiment-Aware Inference-Time Search for Human Reaction Selection in Humanoid Retargeting"
authors: ["Yongpeng Cao", "Masahiro Hirano", "Yuji Yamakawa"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.15274"
doi: "10.48550/arXiv.2610.15274"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Embodiment-Aware Inference-Time Search for Human Reaction Selection in Humanoid Retargeting

> Yongpeng Cao, Masahiro Hirano, Yuji Yamakawa · 2026
> [arXiv](https://arxiv.org/abs/2610.15274) · [PDF](https://arxiv.org/pdf/2610.15274)

## Abstract

Training humanoid robots to learn human behaviors requires expensive data collection, and human-robot interaction data can be even more difficult and costly to collect. Training a specialized reaction model for each humanoid embodiment can also be time-consuming and resource-intensive. Human-to-humanoid motion retargeting provides a more scalable alternative, allowing human-human reaction data to serve as a common motion representation for different humanoid embodiments. However, due to morphological and kinematic differences between humans and humanoid robots, a reaction preferred in human motion space may not be the most suitable one for execution on a particular robot embodiment. In this work, we propose an inference-time reaction search framework that leverages stochastic sampling from a generative reaction model and jointly considers reaction quality and humanoid embodiment feasibility. Given the observed interaction, our framework generates multiple plausible reaction candidates. Each candidate is retargeted to the target humanoid and evaluated using complementary interaction and embodiment-specific feasibility criteria, allowing candidate selection under the physical constraints of the target embodiment. Since the reaction generator remains frozen, the framework can adapt to different humanoid embodiments at inference time without retraining. Experimental results demonstrate that the proposed framework maintains overall human reaction quality while improving the feasibility of retargeted humanoid reactions across different embodiments. The proposed pipeline improves humanoid retargeting feasibility by 1.61%. Moreover, human-space and G1 best-candidate selections disagree in 78.98% of samples, demonstrating substantial embodiment dependence. Code will be released.

## TL;DR

Training humanoid robots to learn human behaviors requires expensive data collection, and human-robot interaction data can be even more difficult and costly to collect. Training a specialized reaction model for each humanoid embodiment can also be time-consuming and resource-intensive.

## Related
<!-- [[other-paper-citekey]] -->
