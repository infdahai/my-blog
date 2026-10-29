---
citekey: "maLearningOptimizeUAVPathPlanningDataSensingWireless2026"
title: "Learning to Optimize UAV Path Planning for Data Sensing in Wireless Sensor Networks"
authors: ["Sijie Ma", "Zeyuan Ma", "Weijia Cao", "Yue-Jiao Gong", "Lingling Ma", "Zhiyang Huang", "Jun Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.16629"
doi: "10.48550/arXiv.2609.16629"
tags: [paper, embodied-ai, "cs.NE", "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Learning to Optimize UAV Path Planning for Data Sensing in Wireless Sensor Networks

> Sijie Ma, Zeyuan Ma, Weijia Cao, Yue-Jiao Gong, Lingling Ma, Zhiyang Huang, Jun Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.16629) · [PDF](https://arxiv.org/pdf/2609.16629)

## Abstract

UAVs have emerged as highly flexible platforms for data sensing in Wireless Sensor Networks (WSNs). Path planning for UAVs in such tasks plays a key role to assure remote sensing effectiveness and friendly energy consumption. However, existing approaches show two key limitations: i) they are primarily hand-crafted with certain design biases that harm adaptation on unseen tasks. ii) they predominantly assume idealized spatial complexities of actual environments through simplified simulation, causing them to underperform during real-world deployment. In this paper, we propose a novel learning-assisted planning framework, termed Landscape-Aware Meta Differential Evolution (LAMDE), to tackle the mentioned limitations. The major contributions come from the following aspects. We first re-formulate such UAV path planning problem to embrace challenging constraints. To efficiently navigate this highly constrained space, we propose a bi-level learning to optimize approach, where the meta-level is a trainable algorithm configuration policy that meta-learns an adaptable planning strategy for low-level planning algorithm. To address the potential training data scarcity and distribution shift in real-world environments, we introduce a landscape-aware automatic augmentation scheme that enriches training data. At the low-level, a Differential Evolution algorithm is deployed for solving the path planning tasks. To enhance the solving flexibility, we further design a variable-length encoding strategy that dynamically prunes redundant hover points and optimizes continuous flight parameters concurrently within a unified search space. Based on all proposed designs, we meta-train LAMDE and compare it with representative baselines. Comprehensive experiments demonstrate that LAMDE achieves state-of-the-art performance on the tested complex UAV path planning tasks in WSN data collection scenarios.

## TL;DR

UAVs have emerged as highly flexible platforms for data sensing in Wireless Sensor Networks (WSNs). Path planning for UAVs in such tasks plays a key role to assure remote sensing effectiveness and friendly energy consumption.

## Related
<!-- [[other-paper-citekey]] -->
