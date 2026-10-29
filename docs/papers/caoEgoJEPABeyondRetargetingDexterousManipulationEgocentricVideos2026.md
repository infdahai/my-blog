---
citekey: "caoEgoJEPABeyondRetargetingDexterousManipulationEgocentricVideos2026"
title: "EgoJEPA: Beyond Retargeting for Dexterous Manipulation from Egocentric Videos"
authors: ["Meng Cao", "Can Zhao", "Jinjie Wei", "Haonan Zhao", "Yulong Zhang", "Duo Han", "Xiaofan Li", "Ziwu Song", "Rongtao Xu", "Ruyi Gan", "Hao Wang", "Qian Wang", "Daolin Ma", "Ian Reid", "Xiaodan Liang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20904"
doi: "10.48550/arXiv.2610.20904"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# EgoJEPA: Beyond Retargeting for Dexterous Manipulation from Egocentric Videos

> Meng Cao, Can Zhao, Jinjie Wei, Haonan Zhao, Yulong Zhang, Duo Han, Xiaofan Li, Ziwu Song, Rongtao Xu, Ruyi Gan, Hao Wang, Qian Wang, Daolin Ma, Ian Reid, Xiaodan Liang · 2026
> [arXiv](https://arxiv.org/abs/2610.20904) · [PDF](https://arxiv.org/pdf/2610.20904)

## Abstract

Egocentric human videos offer a scalable alternative to costly robot demonstra- tions, yet transferring their manipulation priors to robot control remains chal- lenging. The commonly adopted retargeting-based approaches convert human wrist and finger poses into embodiment-specific action commands through hand- crafted geometric mappings. However, such mappings require meticulous recal- ibration across different embodiments and risk propagating hand-tracking errors into downstream robot control pipelines. To this end, we propose EgoJEPA, a three-stage framework that learns embodiment-agnostic representations from ego- centric human videos without rule-based human-to-robot retargeting: 1) Human- action pre-training learns effect-aware latent actions through JEPA-style visual prediction conditioned on hand-motion differences; 2) Latent-action-based world modeling jointly predicts future visual dynamics and latent actions, which decou- ples human prior pre-training from robot-specific control parameterizations; 3) Embodiment-specific tuning adapts the pretrained model to diverse robots through lightweight action adapters. Experiments on five real-world manipulation tasks across three robot embodiments demonstrate the effectiveness and efficiency of EgoJEPA. It achieves a 74% average success rate under the out-of-domain evalu- ation, compared with 65% for the retargeting baseline, while reducing cumulative cross-embodiment wall-clock cost by 47.2%, from 743.2 to 392.7 hours.

## TL;DR

Egocentric human videos offer a scalable alternative to costly robot demonstra- tions, yet transferring their manipulation priors to robot control remains chal- lenging. The commonly adopted retargeting-based approaches convert human wrist and finger poses into embodiment-specific action commands through hand- crafted geometric mappings.

## Related
<!-- [[other-paper-citekey]] -->
