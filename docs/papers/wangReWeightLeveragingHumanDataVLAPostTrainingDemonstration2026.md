---
citekey: "wangReWeightLeveragingHumanDataVLAPostTrainingDemonstration2026"
title: "ReWeight: Leveraging Human Data for VLA Post-Training via Demonstration Retrieval and Sample Weighting"
authors: ["Chenwei Wang", "Dianye Huang", "Match W. L. Ko", "Chenjia Bai", "Zhongliang Jiang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.13851"
doi: "10.48550/arXiv.2609.13851"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# ReWeight: Leveraging Human Data for VLA Post-Training via Demonstration Retrieval and Sample Weighting

> Chenwei Wang, Dianye Huang, Match W. L. Ko, Chenjia Bai, Zhongliang Jiang · 2026
> [arXiv](https://arxiv.org/abs/2609.13851) · [PDF](https://arxiv.org/pdf/2609.13851)

## Abstract

Post-training vision-language-action (VLA) models for specific robots and tasks requires in-domain demonstrations, yet collecting diverse robot data is costly. Egocentric human demonstrations provide a scalable alternative, but directly mixing human and robot data can introduce cross-embodiment discrepancies and degrade policy performance. To address this challenge, we introduce ReWeight, a framework that incorporates human data into VLA post-training through demonstration-level retrieval and sample-level weighting. ReWeight learns a cross-embodiment visuomotor representation that combines visual observations with future actions to measure behavioral similarity between human and robot demonstrations. Based on optimal transport, it retrieves human demonstrations relevant to the target robot data and assigns larger weights to samples with smaller cross-embodiment discrepancies. We evaluate ReWeight using $π_{0.5}$ across eight simulation tasks and four real-world tasks under both clean and randomized settings. In simulation, ReWeight improves the average success rate of post-trained $π_{0.5}$ from 39% with only robot data and 44% with randomly mixed human-robot data to 57%. In the physical experimental setting, it achieves an average success rate of 68.8%, outperforming the baselines by 28.8% and 13.8%, respectively. Overall, ReWeight provides an effective paradigm for transforming abundant egocentric human experience into transferable supervision for robot learning. (Project webpage: https://reweight-vla.github.io/)

## TL;DR

Post-training vision-language-action (VLA) models for specific robots and tasks requires in-domain demonstrations, yet collecting diverse robot data is costly. Egocentric human demonstrations provide a scalable alternative, but directly mixing human and robot data can introduce cross-embodiment discrepancies and degrade policy performance.

## Related
<!-- [[other-paper-citekey]] -->
