---
citekey: "badithelaAnyRankReliableAnytimePolicyRankingSequentialTesting2026"
title: "AnyRank: Reliable Anytime Policy Ranking via Sequential Testing"
authors: ["Apurva Badithela", "David Snyder", "Tenny Yin", "Jade Sceats", "George Pappas", "Nikolai Matni", "Masha Itkina", "Haruki Nishimura", "Anirudha Majumdar"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14603"
doi: "10.48550/arXiv.2610.14603"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-15
---

# AnyRank: Reliable Anytime Policy Ranking via Sequential Testing

> Apurva Badithela, David Snyder, Tenny Yin, Jade Sceats, George Pappas, Nikolai Matni, Masha Itkina, Haruki Nishimura, Anirudha Majumdar · 2026
> [arXiv](https://arxiv.org/abs/2610.14603) · [PDF](https://arxiv.org/pdf/2610.14603)

## Abstract

Due to the high cost of hardware experiments, robot policies are predominantly evaluated by comparing their empirical performance on a limited number of hardware trials. However, finite-sample statistical uncertainty can lead to erroneous conclusions, especially when ranking multiple policies using a fixed batch of evaluation data. We propose AnyRank: a sequential method for multi-policy ranking that (i) adaptively allocates trials to hard-to-separate policies, (ii) provides (partial) rankings at any stopping time while bounding the probability of an incorrect ranking, and (iii) optionally exploits prior information to prioritize hardware evaluations more efficiently. This prior information could be informed from expert intuition, a small set of held-out hardware evaluations, or from policy rollouts in a simulator or an action-conditioned video world model. Notably, the prior can be imperfect; while a strong prior can provide efficiency gains on hardware, any inaccuracies in prior policy rankings do not invalidate the statistical assurances of AnyRank. We achieve the aforementioned properties through novel theoretical contributions that combine sequential testing with multiple-hypothesis graphical testing approaches. Experiments in simulation and real-world policy evaluation benchmarks show that AnyRank requires up to 50% fewer hardware evaluations compared to existing statistically rigorous approaches, while guarding against the incorrect rankings produced by heuristic methods used by state-of-the-art benchmarks.

## TL;DR

Due to the high cost of hardware experiments, robot policies are predominantly evaluated by comparing their empirical performance on a limited number of hardware trials. However, finite-sample statistical uncertainty can lead to erroneous conclusions, especially when ranking multiple policies using a fixed batch of evaluation data.

## Related
<!-- [[other-paper-citekey]] -->
