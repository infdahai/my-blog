---
citekey: "garcesModelBasedReinforcementLearningHeterogeneousMultiTaskAssignment2026"
title: "Model-Based Reinforcement Learning for Heterogeneous Multi-Robot Task Assignment Under Distribution Shifts"
authors: ["Daniel Garces", "Sara Castro", "Adrian Haimovich", "Byron Crowe", "Stephanie Gil"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.21554"
doi: "10.48550/arXiv.2608.21554"
tags: [paper, embodied-ai, "cs.LG", "cs.MA", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Model-Based Reinforcement Learning for Heterogeneous Multi-Robot Task Assignment Under Distribution Shifts

> Daniel Garces, Sara Castro, Adrian Haimovich, Byron Crowe, Stephanie Gil · 2026
> [arXiv](https://arxiv.org/abs/2608.21554) · [PDF](https://arxiv.org/pdf/2608.21554)

## Abstract

Heterogeneous multi-robot service systems must assign requests to compatible robots, construct feasible schedules, and adapt as new tasks arrive online. Historical data can help anticipate future demand, but relying too heavily on inaccurate predictions can degrade performance under distribution shifts. We develop a prediction-aware adaptive rollout framework for heterogeneous multi-robot task assignment with scheduled and real-time requests. The problem is formulated as a finite-horizon stochastic dynamic program incorporating robot-task compatibility, ordered service requirements, routing constraints, service windows, and end-of-horizon return requirements. The proposed policy evaluates current assignments using sampled future request scenarios while restricting immediate commitments to requests already observed. To enable online use, the framework combines pruned candidate controls, wait actions, and an interaction-aware base policy for efficient future-cost estimation. Robustness to forecast error is provided by adaptively reweighting predicted requests based on recent prediction mismatch and selectively re-optimizing assigned but unstarted requests. We also introduce a historical-data-driven procedure for selecting the heterogeneous fleet composition before deployment. In a case study using real nursing-task requests from hospital inpatient floors, the proposed approach achieves near-complete service and reduces serviced-request wait times relative to reactive, token-passing, prediction-positioning, and myopic greedy baselines, with the largest improvements in tail-delay metrics.

## TL;DR

Heterogeneous multi-robot service systems must assign requests to compatible robots, construct feasible schedules, and adapt as new tasks arrive online. Historical data can help anticipate future demand, but relying too heavily on inaccurate predictions can degrade performance under distribution shifts.

## Related
<!-- [[other-paper-citekey]] -->
