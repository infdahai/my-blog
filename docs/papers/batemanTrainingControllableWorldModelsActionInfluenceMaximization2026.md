---
citekey: "batemanTrainingControllableWorldModelsActionInfluenceMaximization2026"
title: "Training Controllable World Models via Action Influence Maximization"
authors: ["Samuel M. Bateman", "Tenny Yin", "Chongyi Zheng", "Lei Huang", "Brian Wang", "Benjamin Eysenbach", "Jaime Fern\\'andez Fisac", "Dhruv Shah"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27387"
doi: "10.48550/arXiv.2610.27387"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Training Controllable World Models via Action Influence Maximization

> Samuel M. Bateman, Tenny Yin, Chongyi Zheng, Lei Huang, Brian Wang, Benjamin Eysenbach, Jaime Fern\'andez Fisac, Dhruv Shah · 2026
> [arXiv](https://arxiv.org/abs/2610.27387) · [PDF](https://arxiv.org/pdf/2610.27387)

## Abstract

Action-conditioned video generative models trained on successful, goal-directed demonstrations tend to ignore the commanded action, rendering a plausible expert-like future regardless of what is asked of them. We trace this failure to training data that lack sufficient action influence. We analyze this metric and prove that it upper bounds the action influence that any model trained on that data can express. Expert demonstrations, whose narrow action distributions let next states be predicted without attending to the action, set a low ceiling that no amount of model capacity alone can raise. Raising it requires collecting different data. We introduce Action Influence Maximization (AIM), an algorithm for actively collecting training data for improving dataset action influence. We compare the performance and data-efficiency of AIM against exploration heuristics and intrinsic-motivation methods on simulated navigation and manipulation tasks. In pixel-based manipulation, AIM is the only method that consistently improves controllability: 500 actively collected episodes added to 3k demonstrations match a world model trained on 300k expert episodes on end-effector controllability, an $85\times$ reduction in data.

## TL;DR

Action-conditioned video generative models trained on successful, goal-directed demonstrations tend to ignore the commanded action, rendering a plausible expert-like future regardless of what is asked of them. We trace this failure to training data that lack sufficient action influence.

## Related
<!-- [[other-paper-citekey]] -->
