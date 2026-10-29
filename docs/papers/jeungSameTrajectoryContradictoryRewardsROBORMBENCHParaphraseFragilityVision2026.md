---
citekey: "jeungSameTrajectoryContradictoryRewardsROBORMBENCHParaphraseFragilityVision2026"
title: "Same Trajectory, Contradictory Rewards (ROBORMBENCH): Paraphrase Fragility in Vision Language Reward Models"
authors: ["Wonje Jeung", "Sangyeon Yoon", "Hyesoo Hong", "Yoonjun Cho", "Dongjae Jeon", "Bumjun Kim", "Jean Oh", "Youngjae Yu", "Albert No"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.05401"
doi: "10.48550/arXiv.2609.05401"
tags: [paper, embodied-ai, "cs.CL", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# Same Trajectory, Contradictory Rewards (ROBORMBENCH): Paraphrase Fragility in Vision Language Reward Models

> Wonje Jeung, Sangyeon Yoon, Hyesoo Hong, Yoonjun Cho, Dongjae Jeon, Bumjun Kim, Jean Oh, Youngjae Yu, Albert No · 2026
> [arXiv](https://arxiv.org/abs/2609.05401) · [PDF](https://arxiv.org/pdf/2609.05401)

## Abstract

Vision-language models are increasingly used as reward functions for robotic learning, but this role requires paraphrase invariance: the same trajectory should receive the same reward under semantically equivalent goal descriptions. We show that current VLM reward models often violate this property. Paraphrasing the instruction alone can substantially change predicted progress scores, and can even flip identical robot behavior between failure and success. To measure this failure mode, we introduce ROBORMBENCH, a benchmark with 2,390 real-robot trajectories, ground-truth progress labels, and 21,673 verified paraphrases spanning lexical, syntactic, and action-goal rewrites. Across proprietary and open-source VLMs, paraphrase-induced instability is widespread and severe, grows under more divergent rewrites, and is not reliably reduced by scale or explicit reasoning. Dedicated reward models trained with trajectory-grounded supervision are substantially more stable. These results show that paraphrase robustness is a core requirement for reliable VLM-based reward modeling in robotics.

## TL;DR

Vision-language models are increasingly used as reward functions for robotic learning, but this role requires paraphrase invariance: the same trajectory should receive the same reward under semantically equivalent goal descriptions. We show that current VLM reward models often violate this property.

## Related
<!-- [[other-paper-citekey]] -->
