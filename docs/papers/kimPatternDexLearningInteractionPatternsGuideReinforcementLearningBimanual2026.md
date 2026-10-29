---
citekey: "kimPatternDexLearningInteractionPatternsGuideReinforcementLearningBimanual2026"
title: "PatternDex: Learning Interaction Patterns to Guide Reinforcement Learning of Bimanual Dexterous Manipulation of Articulated Objects"
authors: ["David Minkwan Kim", "Runfa Blark Li", "Beckham Po-Ju Lee", "Nikolay Atanasov", "Truong Nguyen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04765"
doi: "10.48550/arXiv.2610.04765"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# PatternDex: Learning Interaction Patterns to Guide Reinforcement Learning of Bimanual Dexterous Manipulation of Articulated Objects

> David Minkwan Kim, Runfa Blark Li, Beckham Po-Ju Lee, Nikolay Atanasov, Truong Nguyen · 2026
> [arXiv](https://arxiv.org/abs/2610.04765) · [PDF](https://arxiv.org/pdf/2610.04765)

## Abstract

In this paper, we develop a method that enables bimanual dexterous hands to manipulate articulated objects with a high success rate without suffering from an embodiment gap. We observe that the correlation between hand motions and object motions is dictated by the object rather than the hands and can be learned from human-object demonstrations. Based on this observation, we propose PatternDex, a method that learns this correlation and represents it as a token sequence, which we call an interaction pattern. From this pattern, PatternDex estimates the wrist motions and contact points that fit the target robot, and then trains a reinforcement learning policy that exploits these estimates as guidance. Since the guidance fits the target embodiment, the policy explores only the actions that the target robot can execute and thus achieves high success rates. PatternDex also requires only simple fine-tuning to train a new robot, since it can reuse the learned interaction pattern. We evaluate PatternDex with bimanual dexterous hands on human demonstrations from the ARCTIC dataset. PatternDex achieves, on average, a 92.8% success rate with Allegro hands, while the state-of-the-art baseline achieves 52.2%. Also, it achieves success rates above 70% with three other robot hands after fine-tuning alone. Furthermore, we verify that the learned policy transfers well to a real-world task of opening a microwave. Videos and additional results are available at https://patterndex.github.io/PatternDex/

## TL;DR

In this paper, we develop a method that enables bimanual dexterous hands to manipulate articulated objects with a high success rate without suffering from an embodiment gap. We observe that the correlation between hand motions and object motions is dictated by the object rather than the hands and can be learned from human-object demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
