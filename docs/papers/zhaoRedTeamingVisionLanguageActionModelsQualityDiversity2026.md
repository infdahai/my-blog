---
citekey: "zhaoRedTeamingVisionLanguageActionModelsQualityDiversity2026"
title: "Red-Teaming of Vision-Language-Action Models via Quality Diversity Environment Generation"
authors: ["Shihan Zhao", "Henry Chen", "Ya-Chuan Hsu", "Minjune Hwang", "Siddharth Srikanth", "Freddie Liang", "Akanksha Saran", "Aaquib Tabrez", "Stefanos Nikolaidis", "Daniel Seita"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14415"
doi: "10.48550/arXiv.2610.14415"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Red-Teaming of Vision-Language-Action Models via Quality Diversity Environment Generation

> Shihan Zhao, Henry Chen, Ya-Chuan Hsu, Minjune Hwang, Siddharth Srikanth, Freddie Liang, Akanksha Saran, Aaquib Tabrez, Stefanos Nikolaidis, Daniel Seita · 2026
> [arXiv](https://arxiv.org/abs/2610.14415) · [PDF](https://arxiv.org/pdf/2610.14415)

## Abstract

A long-standing goal in robotics is to develop generalist robots that can perform tasks across a wide range of settings, flexibly specified with images and text. Vision-Language-Action (VLA) models offer a promising path toward this goal by training on large collections of robot demonstrations. However, while VLAs perform well in-distribution, they often fail under minor test-time shifts, such as changes in object positions, lighting, textures, and camera poses. To address this, we propose Quality Diversity for Diverse Environment Generation (Q-DEG), a method for improving VLA robustness by generating adversarial environments and fine-tuning the VLA on its own successful rollouts. Q-DEG uses Quality Diversity (QD) optimization to find a set of high-failure environments, while promoting diversity using policy embeddings extracted from the VLA. These environments expose vulnerabilities that can be mitigated through self-imitation fine-tuning, thereby improving the VLA's robustness. In simulation, we conduct experiments across three representative VLA models, and our results indicate that Q-DEG improves robustness to out-of-distribution (OOD) adversarial environments compared to the base VLA and VLAs fine-tuned using data collected from two red-teaming baselines. Furthermore, we demonstrate that improving VLA robustness through Q-DEG facilitates sim-to-real transfer. Our anonymous project website is at: https://qd-env.github.io/qdeg/.

## TL;DR

A long-standing goal in robotics is to develop generalist robots that can perform tasks across a wide range of settings, flexibly specified with images and text. Vision-Language-Action (VLA) models offer a promising path toward this goal by training on large collections of robot demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
