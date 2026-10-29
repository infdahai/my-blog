---
citekey: "garciaLearningTaskMotionPlansRealDemonstrationsHybridFlow2026"
title: "Learning Task and Motion Plans from Real Demonstrations with Hybrid Flow Matching"
authors: ["Zuleika Redondo Garcia", "Andreu Matoses Gimenez", "Javier Alonso-Mora"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04771"
doi: "10.48550/arXiv.2610.04771"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Learning Task and Motion Plans from Real Demonstrations with Hybrid Flow Matching

> Zuleika Redondo Garcia, Andreu Matoses Gimenez, Javier Alonso-Mora · 2026
> [arXiv](https://arxiv.org/abs/2610.04771) · [PDF](https://arxiv.org/pdf/2610.04771)

## Abstract

Long-horizon mobile manipulation requires a task plan and the motion that executes it. Generative planners trained on demonstration produce both in one pass, requiring neither a symbolic domain nor search. To date, however, they have relied on thousands of scripted demonstrations of fixed-base arms and executed open loop. This paper presents a hybrid flow matching planner: a single network generates the symbolic plan with masked discrete flow matching and the motion trajectory with continuous flow matching. Unlike prior generative planners, we aim to learn from a much smaller set of demonstrations and to execute the plan in closed loop. Two properties of the data compensate for the small dataset. A demonstration resumed from any of its intermediate actions is itself a demonstration, which multiplies the training samples and enables replanning after every action. Objects of the same kind are interchangeable, which turns demonstrations of one goal into demonstrations of every permuted goal. Our base implementation produces valid plans on 68% of held-out scenes; a training and generation scheme for the discrete plan raises this to 76%, and replanning after every action raises the task completion rate from 40% to 53% in a kinematic simulation. The planner matches the task completion rate of motion-only flow matching policies while additionally providing the symbolic plan, and it outperforms previous hybrid diffusion formulations on both task completion and plan validity. We validate the planner on a real mobile manipulator. Videos and project page: https://andreumatoses.github.io/research/hybrid-flow-planning

## TL;DR

Long-horizon mobile manipulation requires a task plan and the motion that executes it. Generative planners trained on demonstration produce both in one pass, requiring neither a symbolic domain nor search.

## Related
<!-- [[other-paper-citekey]] -->
