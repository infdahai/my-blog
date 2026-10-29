---
citekey: "yinWMCraftnetWorldSynesthesiaModelGeneralizableRobustDexterous2026"
title: "WM-Craftnet: World Synesthesia Model for Generalizable and Robust Dexterous In-Hand Manipulation"
authors: ["Jie Yin", "Zeyuan Zhao", "Xiaojing Tan", "Yang Liu", "Chiyu Wang", "Xinyang Gu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.07002"
doi: "10.48550/arXiv.2609.07002"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# WM-Craftnet: World Synesthesia Model for Generalizable and Robust Dexterous In-Hand Manipulation

> Jie Yin, Zeyuan Zhao, Xiaojing Tan, Yang Liu, Chiyu Wang, Xinyang Gu · 2026
> [arXiv](https://arxiv.org/abs/2609.07002) · [PDF](https://arxiv.org/pdf/2609.07002)

## Abstract

Generalizable and robust dexterous in-hand manipulation requires a policy to infer object pose, geometry, contact, and potential slip from partial and noisy observations. Although recent tactile and visuotactile RL methods achieve strong in-hand rotation in controlled settings, their robustness often degrades under pose shifts, force disturbances, and object variation. We propose WM-Craftnet, a world-model-conditioned framework that learns compact action-conditioned latent dynamics from proprioception, depth, tactile sensing, and actions, supervised by multimodal reconstruction and reward prediction. Rather than using the world model for latent imagination or policy optimization, WM-Craftnet uses the learned World Synesthesia Model (WSM) as recurrent task context for an asymmetric actor--critic policy. Importantly, WSM is trained to reconstruct clean depth targets from noisy depth inputs, providing a denoised geometric state for real-robot deployment. Ablations over recurrent baselines, auxiliary heads, tactile masking, and WSM modality heads show that predictive world modeling, clean-depth supervision, and tactile contact cues all shape the learned state. A WSM pretrained on nine \(z\)-axis objects serves as a reusable prior for \(49\)-object downstream policy learning. This context improves multi-object rotation, with quantitative and qualitative evidence for unseen-object, perturbation-recovery, and sim-to-real transfer.

## TL;DR

Generalizable and robust dexterous in-hand manipulation requires a policy to infer object pose, geometry, contact, and potential slip from partial and noisy observations. Although recent tactile and visuotactile RL methods achieve strong in-hand rotation in controlled settings, their robustness often degrades under pose shifts, force disturbances, and object variation.

## Related
<!-- [[other-paper-citekey]] -->
