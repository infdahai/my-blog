---
citekey: "jooScalingLatentMotorAdaptationCoordinatedBimanualManipulation2026"
title: "Scaling Latent Motor Adaptation to Coordinated Bimanual Manipulation"
authors: ["Seung-Bin Joo", "Alessandro Albini", "Luca Wiehe", "Perla Maiolino", "Daniel Olmeda Reino", "Jo\\~ao F. Henriques"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14833"
doi: "10.48550/arXiv.2610.14833"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Scaling Latent Motor Adaptation to Coordinated Bimanual Manipulation

> Seung-Bin Joo, Alessandro Albini, Luca Wiehe, Perla Maiolino, Daniel Olmeda Reino, Jo\~ao F. Henriques · 2026
> [arXiv](https://arxiv.org/abs/2610.14833) · [PDF](https://arxiv.org/pdf/2610.14833)

## Abstract

Robust manipulation under uncertain object dynamics and geometry remains a core challenge in real-world robotics. Policies trained under fixed assumptions often degrade when object mass, friction, scale, or shape vary. Embedding-based adaptation methods such as Rapid Motor Adaptation (RMA) address this by conditioning actions on latent representations of environment dynamics inferred from interaction history. We investigate whether this paradigm scales from single arm settings to coordinated bimanual manipulation, where higher dimensional control, coupled contacts, and shared object forces introduce additional complexity. We evaluate bimanual RMA on three contact-rich ManiSkill tasks with randomized YCB object properties. Bimanual RMA, using observation-action history and dual wrist depth images, retains privileged policy performance on bimanual picking and lifting, while an otherwise matched stationary PPO policy without latent conditioning achieves low success; all methods remain limited on long-horizon stacking. We further demonstrate direct sim-to-real transfer on a dual Franka lifting task without real-world finetuning. Together, these results suggest that latent conditioning provides useful structure for scaling robust control to coordinated bimanual systems, while longer horizon tasks require additional temporal structure.

## TL;DR

Robust manipulation under uncertain object dynamics and geometry remains a core challenge in real-world robotics. Policies trained under fixed assumptions often degrade when object mass, friction, scale, or shape vary.

## Related
<!-- [[other-paper-citekey]] -->
