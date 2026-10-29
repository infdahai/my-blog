---
citekey: "huangHaveYouSeenItClearlyUncertaintyGuidedBelief2026"
title: "Have You Seen It Clearly? Uncertainty-Guided Belief Refinement for Zero-Shot Object Navigation"
authors: ["Jingzhi Huang", "Junkai Huang", "Yuhang Peng", "Keyu Mu", "Jiaru Zhong", "Yi Wang", "Lujia Wang", "Lap-Pui Chau", "Siyang Gao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.15375"
doi: "10.48550/arXiv.2610.15375"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Have You Seen It Clearly? Uncertainty-Guided Belief Refinement for Zero-Shot Object Navigation

> Jingzhi Huang, Junkai Huang, Yuhang Peng, Keyu Mu, Jiaru Zhong, Yi Wang, Lujia Wang, Lap-Pui Chau, Siyang Gao · 2026
> [arXiv](https://arxiv.org/abs/2610.15375) · [PDF](https://arxiv.org/pdf/2610.15375)

## Abstract

Zero-Shot Object Navigation (ZSON) requires an agent to locate target objects in unfamiliar environments without additional training for the test categories or environments. Recent approaches leverage large language models and vision-language models to construct spatial representations and guide exploration. However, whether the available evidence sufficiently supports a navigation choice, and how new evidence changes the search value of previously visited locations, remain insufficiently addressed. We propose RefBeliefMap, an uncertainty-guided mapping framework that distinguishes target-location belief from spatial and semantic evidence uncertainty. By jointly modeling intra-observation uncertainty and inter-observation disagreement over a sliding memory window, RefBeliefMap assesses the reliability of both evidence channels. When competing frontiers remain insufficiently resolved, these uncertainty estimates guide active observation and semantic reasoning to refine the evidence supporting target-location beliefs before navigation commitment. Building on the refined map, we introduce RefBeliefNav, which jointly evaluates unexplored frontiers and historical waypoints according to their target-finding potential, expected information gain, and navigation cost. This unified objective allows historical locations to be reconsidered as new evidence changes their search value, coordinating exploration and revisitation. Experiments on HM3D and MP3D demonstrate state-of-the-art performance among the evaluated zero-shot baselines, with ablation studies examining the contributions of modules. Real-world experiments on a Unitree Go2 quadruped robot further demonstrate the sim-to-real transferability of our method.

## TL;DR

Zero-Shot Object Navigation (ZSON) requires an agent to locate target objects in unfamiliar environments without additional training for the test categories or environments. Recent approaches leverage large language models and vision-language models to construct spatial representations and guide exploration.

## Related
<!-- [[other-paper-citekey]] -->
