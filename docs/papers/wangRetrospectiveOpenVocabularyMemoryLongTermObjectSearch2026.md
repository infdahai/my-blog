---
citekey: "wangRetrospectiveOpenVocabularyMemoryLongTermObjectSearch2026"
title: "Retrospective Open-Vocabulary Memory for Long-Term Object Search"
authors: ["Jiaming Wang", "Zhiwei Xue", "Chen Jizhuo", "Peng Shiqi", "Harold Soh"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00330"
doi: "10.48550/arXiv.2610.00330"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Retrospective Open-Vocabulary Memory for Long-Term Object Search

> Jiaming Wang, Zhiwei Xue, Chen Jizhuo, Peng Shiqi, Harold Soh · 2026
> [arXiv](https://arxiv.org/abs/2610.00330) · [PDF](https://arxiv.org/pdf/2610.00330)

## Abstract

Long-term object search requires learning where objects usually appear from repeated but uneven observations of a changing environment. We formulate retrospective open-vocabulary memory as probabilistic inference from censored observations, where the key idea is to reason with evidence per opportunity: a detection or non-detection should influence belief only in proportion to the robot's opportunity to observe the corresponding location. We introduce ECROM, which uses this principle to estimate long-term prevalence for concepts specified only at query time and converts the resulting belief directly into an active-search prior. To evaluate this problem, we introduce a controlled long-term benchmark in ten HM3D homes that independently varies object placement and observation opportunity across repeated traversals. ECROM improves support-level AP on held-out queries by 4.5 points and search SPL by 4.2 points over the strongest competing memory in each metric. The benchmark, dataset, and code will be open-sourced.

## TL;DR

Long-term object search requires learning where objects usually appear from repeated but uneven observations of a changing environment. We formulate retrospective open-vocabulary memory as probabilistic inference from censored observations, where the key idea is to reason with evidence per opportunity: a detection or non-detection should influence belief only in proportion to the robot's opportunity to observe the corresponding location.

## Related
<!-- [[other-paper-citekey]] -->
