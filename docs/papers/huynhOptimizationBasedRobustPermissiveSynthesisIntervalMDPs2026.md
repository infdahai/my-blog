---
citekey: "huynhOptimizationBasedRobustPermissiveSynthesisIntervalMDPs2026"
title: "Optimization-Based Robust Permissive Synthesis for Interval MDPs"
authors: ["Khang Vo Huynh", "David Parker", "Lu Feng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2510.03481"
doi: "10.48550/arXiv.2510.03481"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-09-15
---

# Optimization-Based Robust Permissive Synthesis for Interval MDPs

> Khang Vo Huynh, David Parker, Lu Feng · 2026
> [arXiv](https://arxiv.org/abs/2510.03481) · [PDF](https://arxiv.org/pdf/2510.03481)

## Abstract

We present an optimization-based framework for robust permissive synthesis for Interval Markov Decision Processes (IMDPs). While robust IMDP controller synthesis typically yields a single policy and most permissive-synthesis methods assume exact transition models, we synthesize multi-strategies that retain multiple actions while guaranteeing satisfaction of probabilistic reachability or expected-reward specifications under all admissible transition probabilities. We formulate the problem as a mixed-integer linear program (MILP) that maximizes the number of enabled state--action pairs subject to robust Bellman constraints. We develop two encodings: a direct vertex-enumeration formulation and a dualization-based formulation that avoids explicit enumeration of uncertainty-polytope vertices and has size linear in the number of successor transitions. Experiments on four benchmark domains show that both encodings achieve the same optimal permissiveness and scale to IMDPs with hundreds of thousands of states. Compared with standard robust single-policy synthesis, the resulting multi-strategies retain substantially more action choices.

## TL;DR

We present an optimization-based framework for robust permissive synthesis for Interval Markov Decision Processes (IMDPs). While robust IMDP controller synthesis typically yields a single policy and most permissive-synthesis methods assume exact transition models, we synthesize multi-strategies that retain multiple actions while guaranteeing satisfaction of probabilistic reachability or expected-reward specifications under all admissible transition probabilities.

## Related
<!-- [[other-paper-citekey]] -->
