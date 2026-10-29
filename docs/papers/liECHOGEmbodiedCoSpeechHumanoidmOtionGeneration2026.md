---
citekey: "liECHOGEmbodiedCoSpeechHumanoidmOtionGeneration2026"
title: "ECHO-G: Embodied Co-speech Humanoid mOtion Generation"
authors: ["Yizhao Li", "Pusen Gao", "Ming Wang", "Shaojie Shen", "Shuo Yang", "Hao Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.39575"
doi: "10.48550/arXiv.2609.39575"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# ECHO-G: Embodied Co-speech Humanoid mOtion Generation

> Yizhao Li, Pusen Gao, Ming Wang, Shaojie Shen, Shuo Yang, Hao Xu · 2026
> [arXiv](https://arxiv.org/abs/2609.39575) · [PDF](https://arxiv.org/pdf/2609.39575)

## Abstract

Generating full-body co-speech motion for humanoid robots requires coordinating speech prosody, linguistic content, and embodiment-specific motion. To this end, we present ECHO-G, a framework jointly conditioned on speech audio and timed transcripts. Its Speech-Grounded Diffusion Transformer (SGDiT) combines frame-aligned acoustic features with token-level linguistic context, preserving their distinct granularities. Trained with rectified flow matching, it models one-to-many utterance-motion relationships directly in robot space. To support training and evaluation, we introduce a BEAT2-derived audio-text-robot dataset and a benchmark covering co-speech characteristics, robot-motion quality, and runtime efficiency. Comparative evaluation supports direct robot-space generation over the evaluated human-motion generation and retargeting pipelines, while modality ablations highlight the benefits of joint audio-text conditioning. We further demonstrate deployment on a physical humanoid robot. A complementary video-rating study also favors joint conditioning over the alternatives. The dataset and training, inference, and evaluation code are available through our project page.

## TL;DR

Generating full-body co-speech motion for humanoid robots requires coordinating speech prosody, linguistic content, and embodiment-specific motion. To this end, we present ECHO-G, a framework jointly conditioned on speech audio and timed transcripts.

## Related
<!-- [[other-paper-citekey]] -->
