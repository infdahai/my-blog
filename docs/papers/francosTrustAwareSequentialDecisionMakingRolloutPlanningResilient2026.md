---
citekey: "francosTrustAwareSequentialDecisionMakingRolloutPlanningResilient2026"
title: "Trust-Aware Sequential Decision Making and Rollout Planning for Resilient Multi-Robot Systems"
authors: ["Roee M. Francos", "Daniel Garces", "Orhan Eren Akg\\\"un", "Nathaniel D. Bastian", "Stephanie Gil"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25690"
doi: "10.48550/arXiv.2608.25690"
tags: [paper, embodied-ai, "cs.MA", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Trust-Aware Sequential Decision Making and Rollout Planning for Resilient Multi-Robot Systems

> Roee M. Francos, Daniel Garces, Orhan Eren Akg\"un, Nathaniel D. Bastian, Stephanie Gil · 2026
> [arXiv](https://arxiv.org/abs/2608.25690) · [PDF](https://arxiv.org/pdf/2608.25690)

## Abstract

Sequential decision-making in multi-robot systems typically assumes that planning information is reliable and that agents execute the actions anticipated by the planner. Compromised agents can violate both assumptions, creating a mismatch between the planning model and physical execution. We study this problem in online multi-robot routing under localization spoofing. We introduce a distance-constrained spoofing model for monitor-aware adversaries, together with a tiered bipartite matching strategy that maximizes assignment influence while limiting spoofing magnitude. To mitigate such attacks, we develop a trust-aware monitor that combines probabilistic localization trust, calibrated using real GPS spoofing data, with behavioral evidence from task execution to classify agents and remove detected adversaries from subsequent planning. We further show that undetected adversaries can cause rollout to lose its expected cost-improvement behavior by violating planner-execution consistency. Trust-aware removal restores this consistency after detection, enabling stable routing and recovery of rollout's empirical advantage over the base policy. Experiments using real GPS spoofing datasets and San Francisco taxicab demand demonstrate effective detection and resilient routing across varying spoofing capabilities, adversarial fleet sizes, adaptive attacks, monitoring configurations, and rollout horizons.

## TL;DR

Sequential decision-making in multi-robot systems typically assumes that planning information is reliable and that agents execute the actions anticipated by the planner. Compromised agents can violate both assumptions, creating a mismatch between the planning model and physical execution.

## Related
<!-- [[other-paper-citekey]] -->
