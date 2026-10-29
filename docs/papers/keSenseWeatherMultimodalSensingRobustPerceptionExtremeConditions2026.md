---
citekey: "keSenseWeatherMultimodalSensingRobustPerceptionExtremeConditions2026"
title: "SenseWeather: Multimodal Sensing for Robust Robotic Perception under Extreme Conditions"
authors: ["Fucai Ke", "Sukai Huang", "Junyi Hao", "Kal Backman", "Naim Rastgoo", "Gholamreza Haffari", "Hamid Rezatofighi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14082"
doi: "10.48550/arXiv.2610.14082"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# SenseWeather: Multimodal Sensing for Robust Robotic Perception under Extreme Conditions

> Fucai Ke, Sukai Huang, Junyi Hao, Kal Backman, Naim Rastgoo, Gholamreza Haffari, Hamid Rezatofighi · 2026
> [arXiv](https://arxiv.org/abs/2610.14082) · [PDF](https://arxiv.org/pdf/2610.14082)

## Abstract

Robotic perception must remain reliable when extreme environmental conditions severely degrade the primary RGB observation. Although robotic platforms commonly carry complementary sensors such as depth and infrared, much of the modern perception stack remains RGB-centric, creating a mismatch between multimodal onboard sensing and pretrained downstream models. We study whether complementary sensing can be used upstream to recover a task-compatible RGB observation that preserves existing perception capabilities without modifying or retraining the downstream stack. To this end, we introduce SenseWeather, a controlled multimodal benchmark for robotic perception under severe rain, snow, dust, fog, and darkness, with registered RGB, depth, and infrared observations, clean references, and grounded high-level perception tasks. We further develop Fusion-to-RGB, with two parameter-efficient sensor-fusion realizations based on token-space fusion for a diffusion transformer and residual latent conditioning for an inpainting UNet. Across frozen open-vocabulary grounding and vision-language models, RGB+D+IR fusion improves all paired downstream comparisons over the corresponding RGB-only restorers, including AP50 gains across all ten detector comparisons. Importantly, these perception gains do not consistently follow conventional image-fidelity metrics, and increasing weather severity does not induce monotonic downstream degradation. These results show that complementary sensing can preserve reusable robotic perception under extreme conditions, while highlighting task-level perception robustness as an objective distinct from visual restoration quality.

## TL;DR

Robotic perception must remain reliable when extreme environmental conditions severely degrade the primary RGB observation. Although robotic platforms commonly carry complementary sensors such as depth and infrared, much of the modern perception stack remains RGB-centric, creating a mismatch between multimodal onboard sensing and pretrained downstream models.

## Related
<!-- [[other-paper-citekey]] -->
