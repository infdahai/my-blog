---
citekey: "kalantherOrchestratingLevelKPoliciesAgainstUnknownOpponentsPartially2026"
title: "Orchestrating Level-$K$ Policies Against Unknown Opponents in Partially-Observable Dynamic Games"
authors: ["Addison Kalanther", "Sanika Bharvirkar", "Daniel Bostwick", "Chinmay Maheshwari", "Shankar Sastry"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04937"
doi: "10.48550/arXiv.2610.04937"
tags: [paper, embodied-ai, "cs.MA", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Orchestrating Level-$K$ Policies Against Unknown Opponents in Partially-Observable Dynamic Games

> Addison Kalanther, Sanika Bharvirkar, Daniel Bostwick, Chinmay Maheshwari, Shankar Sastry · 2026
> [arXiv](https://arxiv.org/abs/2610.04937) · [PDF](https://arxiv.org/pdf/2610.04937)

## Abstract

Level-$K$ reasoning generates a hierarchy of policies specialized to opponents with different reasoning levels. When an opponent's level is unknown, a common deployment rule estimates that level and selects the corresponding response. In a dynamic, partially-observed game, this selection is repeated, with each choice shaping subsequent states and observations. The response associated with the most likely opponent level need not maximize expected return from the current history. We formulate this deployment problem as dynamic orchestration of a fixed, pretrained policy library in a partially observable Markov game. We compare classification-based orchestrators (CBOs) trained using offline data or on-policy data aggregation with a reinforcement-learning-based orchestrator (RLBO) trained to maximize expected discounted return. In pursuit-evasion experiments, on-policy training improves classification and return, yet RLBO achieves higher return than the on-policy and offline CBOs. Given a pretrained library, RLBO also reaches performance comparable to a policy trained directly over the pursuers' action space with fewer training timesteps. These findings support treating a hierarchy of level-$K$ policies as a resource for orchestration, not a prescription for deployment.

## TL;DR

Level-$K$ reasoning generates a hierarchy of policies specialized to opponents with different reasoning levels. When an opponent's level is unknown, a common deployment rule estimates that level and selects the corresponding response.

## Related
<!-- [[other-paper-citekey]] -->
