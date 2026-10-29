---
citekey: "jinDeepJEPAScalingWorldModelsWithin2026"
title: "DeepJEPA: Scaling World Models from Within"
authors: ["Zijian Jin", "Yunbei Zhang", "Yuanzhe Liu", "Ming Liu", "Baian Chen", "Weirui Ye", "Shilong Liu", "Marco Pavone"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00368"
doi: "10.48550/arXiv.2610.00368"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# DeepJEPA: Scaling World Models from Within

> Zijian Jin, Yunbei Zhang, Yuanzhe Liu, Ming Liu, Baian Chen, Weirui Ye, Shilong Liu, Marco Pavone · 2026
> [arXiv](https://arxiv.org/abs/2610.00368) · [PDF](https://arxiv.org/pdf/2610.00368)

## Abstract

World-model planners typically scale outward by rolling farther, sampling more trajectories, or optimizing longer, while assigning the same computation to every imagined transition. We show that making every transition uniformly deeper wastes computation and can degrade planning because useful refinement is concentrated at a small set of decision-critical events. We introduce DeepJEPA, a weight-tied joint-embedding predictive world model that treats transition depth as an inner test-time scaling axis and learns when another recurrent update is worth computing for each candidate and rollout step. Across five visual-control settings, DeepJEPA improves or matches the strongest fixed-depth planner while averaging only 1.00-1.26 updates per transition. Its additional computation concentrates at contact onset and sustained object interaction, where latent corrections can change which candidates enter the planner's elite set and which action is selected. Representation probes further show that improved planning does not require uniformly better object-state decodability. DeepJEPA therefore reframes world-model scaling as a problem of allocating internal computation where it can change the planner's decision: think deeper at decision-critical transitions instead of making every rollout uniformly deeper or longer.

## TL;DR

World-model planners typically scale outward by rolling farther, sampling more trajectories, or optimizing longer, while assigning the same computation to every imagined transition. We show that making every transition uniformly deeper wastes computation and can degrade planning because useful refinement is concentrated at a small set of decision-critical events.

## Related
<!-- [[other-paper-citekey]] -->
