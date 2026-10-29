---
citekey: "zhouLargeMultimodalModelsDirectControlGPT6Beginning2026"
title: "Large Multimodal Models for Direct Robot Control: GPT-6 as a Beginning"
authors: ["Youwei Zhou", "Bohan Hou", "Yankai Fu", "Yaoxu Lyu", "Yifan Ye", "Shilin Shan", "Chen Guo", "Jiaming Liu", "Ran He", "Caifeng Shan", "Shanghang Zhang", "Jianfei Yang", "Zhihe Lu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28259"
doi: "10.48550/arXiv.2610.28259"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Large Multimodal Models for Direct Robot Control: GPT-6 as a Beginning

> Youwei Zhou, Bohan Hou, Yankai Fu, Yaoxu Lyu, Yifan Ye, Shilin Shan, Chen Guo, Jiaming Liu, Ran He, Caifeng Shan, Shanghang Zhang, Jianfei Yang, Zhihe Lu · 2026
> [arXiv](https://arxiv.org/abs/2610.28259) · [PDF](https://arxiv.org/pdf/2610.28259)

## Abstract

Recent advances in visuospatial understanding and agentic reasoning enable direct robotic manipulation with general-purpose multimodal models, but their embodied capabilities remain poorly understood. This paper systematically evaluate GPT-6 Astra for closed-loop robotic manipulation using a lightweight agent execution framework. We first probe three fundamental embodied capabilities-depth perception, embodied in-context learning, and tactile understanding-and demonstrate that the model can exploit depth information, acquire simple manipulation strategies from contextual demonstrations, and use tactile feedback to correct its actions. We then evaluate GPT-6 Astra across five established manipulation benchmarks along six capability dimensions. Despite competitive performance on several benchmarks-26.92\% success on RoboDojo and 76.0\% on RoboTwin 2.0-our analysis reveals a pronounced gap between semantic reasoning and physical execution, particularly in consequence-aware action planning, precision, and complex motion coordination. To further examine these limitations, we introduce LIBERO-GeoMotion, a new benchmark of geometry-constrained tasks that require precise pose alignment, coordinated translation and rotation, and anticipation of physical action consequences. GPT-6 Astra achieves only 11.1\% zero-shot success, exposing the difficulty of translating spatial understanding into physically feasible motion. Real-world experiments corroborate these findings: zero-shot execution is feasible for simple tasks, yet persistent deficits remain in motion feasibility, precise control, and physical safety, while substantial inference latency further hinders practical deployment. Overall, our results characterize the emerging embodied capabilities of general-purpose multimodal models and delineate the key challenges toward safe, efficient, and reliable robotic manipulation.

## TL;DR

Recent advances in visuospatial understanding and agentic reasoning enable direct robotic manipulation with general-purpose multimodal models, but their embodied capabilities remain poorly understood. This paper systematically evaluate GPT-6 Astra for closed-loop robotic manipulation using a lightweight agent execution framework.

## Related
<!-- [[other-paper-citekey]] -->
