---
citekey: "wangCeDRNavCrossEmbodimentMaplessNavigationOfflineDemonstration2026"
title: "CeDR-Nav: Cross-Embodiment Mapless Navigation via Offline Demonstration Recasting"
authors: ["Xianghui Wang", "Xinming Zhang", "Yiwei Qian", "Siwei Cheng", "Shanze Wang", "Dan Zhang", "Wei Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13007"
doi: "10.48550/arXiv.2610.13007"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# CeDR-Nav: Cross-Embodiment Mapless Navigation via Offline Demonstration Recasting

> Xianghui Wang, Xinming Zhang, Yiwei Qian, Siwei Cheng, Shanze Wang, Dan Zhang, Wei Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.13007) · [PDF](https://arxiv.org/pdf/2610.13007)

## Abstract

Learning-based methods have demonstrated strong performance in mapless robot navigation. However, a learned policy remains restricted to the embodiment on which it was trained. Many cross-embodiment navigation methods require time-consuming online training and can still underperform target-specific policies. In fact, demonstrations collected on a source embodiment already contain navigation experience that is potentially reusable for deriving a policy for each target embodiment, but the embodiment mismatch prevents these demonstrations from directly serving as valid supervision for the target. In this article, we present CeDR-Nav, a cross-embodiment demonstration recasting framework that trains a dedicated navigation policy for each target embodiment from existing source demonstrations without online data collection. Geometry-consistent scaling with per-demonstration validity assessment converts the source demonstrations into target training data, and a target-specific Gaussian mixture policy generates feasible avoidance maneuvers for each target embodiment. Extensive quantitative simulations and real-world deployments across multiple robot platforms demonstrate the effectiveness of CeDR-Nav, with an average success-rate gain of 13.8 percentage points over DRL-DCLP in cross-embodiment simulations and target-specific policy training completed within seconds.

## TL;DR

Learning-based methods have demonstrated strong performance in mapless robot navigation. However, a learned policy remains restricted to the embodiment on which it was trained.

## Related
<!-- [[other-paper-citekey]] -->
