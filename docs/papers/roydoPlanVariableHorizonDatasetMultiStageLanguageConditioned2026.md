---
citekey: "roydoPlanVariableHorizonDatasetMultiStageLanguageConditioned2026"
title: "doPlan: A Variable-Horizon Dataset for Multi-Stage Language-Conditioned Planning in Autonomous Driving"
authors: ["Parthib Roy", "Yash Tandon", "Marcus Blennemann", "Giovanni Tapia Lopez", "Angel Martinez-Sanchez", "Mohan M. Trivedi", "Ross Greer"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38028"
doi: "10.48550/arXiv.2609.38028"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# doPlan: A Variable-Horizon Dataset for Multi-Stage Language-Conditioned Planning in Autonomous Driving

> Parthib Roy, Yash Tandon, Marcus Blennemann, Giovanni Tapia Lopez, Angel Martinez-Sanchez, Mohan M. Trivedi, Ross Greer · 2026
> [arXiv](https://arxiv.org/abs/2609.38028) · [PDF](https://arxiv.org/pdf/2609.38028)

## Abstract

Autonomous vehicles interacting with passengers through natural language must reason beyond immediate commands. Passenger intent may span multiple stages of behavior, depend on future events, refer to surrounding agents or landmarks, and remain relevant as driving conditions evolve. Existing language-enabled driving datasets largely focus on short, localized interactions, leaving these longer-horizon forms of passenger intent comparatively underexplored. We introduce doPlan, to our knowledge the first publicly available, human-annotated real-world dataset designed to study passenger language as persistent task context. Built on nuPlan, doPlan contains 5,154 human-written passenger instructions spanning 169.1 hours of cumulative instruction-aligned context over 50.9 hours of unique driving, with annotation windows ranging from 30.0 to 508.8 s. The annotations capture immediate, deferred, event-conditioned, persistent, and multi-stage passenger intent. The dataset, annotation interface, and supporting resources are publicly available at https://github.com/Mi3-Lab/doPlan. We evaluate four language-conditioned driving models and find that sensitivity to passenger language does not reliably translate into behavior consistent with the requested direction. More broadly, among 2,161 examples with a matched future maneuver, the first associated maneuver occurs a median of 24.6 s after the evaluation point, and only 9.8% occur within the models' common 5 s prediction horizon. These findings highlight the need to connect persistent passenger intent with successive planning decisions. doPlan provides a setting for studying how unresolved goals can be retained, grounded in evolving scenes, and tracked across multiple stages, including how a planner determines when a future goal becomes relevant to the current plan.

## TL;DR

Autonomous vehicles interacting with passengers through natural language must reason beyond immediate commands. Passenger intent may span multiple stages of behavior, depend on future events, refer to surrounding agents or landmarks, and remain relevant as driving conditions evolve.

## Related
<!-- [[other-paper-citekey]] -->
