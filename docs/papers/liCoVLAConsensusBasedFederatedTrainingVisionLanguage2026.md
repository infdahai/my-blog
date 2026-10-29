---
citekey: "liCoVLAConsensusBasedFederatedTrainingVisionLanguage2026"
title: "Co-VLA: Consensus-based Federated Training for Vision-Language-Action Models"
authors: ["Haolong Li", "Guner Dilsad Er", "Michael Muehlebach", "Joerg Stueckler"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.19923"
doi: "10.48550/arXiv.2609.19923"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# Co-VLA: Consensus-based Federated Training for Vision-Language-Action Models

> Haolong Li, Guner Dilsad Er, Michael Muehlebach, Joerg Stueckler · 2026
> [arXiv](https://arxiv.org/abs/2609.19923) · [PDF](https://arxiv.org/pdf/2609.19923)

## Abstract

Vision-language-action models (VLAs) have emerged as a promising paradigm for general-purpose robot learning, with performance improving as models and datasets scale. Scaling robot data collection, however, remains challenging because data are naturally distributed across robots, tasks, and locations, making centralization costly or impractical. Federated learning offers a way to train on decentralized robot data, but applying it to VLAs requires accounting for heterogeneous robot client data distributions. We present Co-VLA, which applies consensus optimization using the Alternating Direction Method of Multipliers~(ADMM) to federated VLA training. We show that the same algorithm supports both full-model training and parameter-efficient fine-tuning with both fixed-rank and rank-adaptive adapters. The name Co-VLA reflects both consensus and collaboration: clients with different local robot datasets collaboratively train a shared model without sharing their data. Our experiments demonstrate that Co-VLA achieves performance comparable to centralized training in both full-model training and parameter-efficient fine-tuning settings.

## TL;DR

Vision-language-action models (VLAs) have emerged as a promising paradigm for general-purpose robot learning, with performance improving as models and datasets scale. Scaling robot data collection, however, remains challenging because data are naturally distributed across robots, tasks, and locations, making centralization costly or impractical.

## Related
<!-- [[other-paper-citekey]] -->
