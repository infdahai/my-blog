---
citekey: "boyalakuntlaBeyondPolicyAlignmentClosingPlanningLearningLoopControl2026"
title: "Beyond Policy Alignment: Closing the Planning-Learning Loop for Robot Control with Learned World Models"
authors: ["Kowndinya Boyalakuntla", "Yuhan Liu", "Abdeslam Boularias"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.39751"
doi: "10.48550/arXiv.2609.39751"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Beyond Policy Alignment: Closing the Planning-Learning Loop for Robot Control with Learned World Models

> Kowndinya Boyalakuntla, Yuhan Liu, Abdeslam Boularias · 2026
> [arXiv](https://arxiv.org/abs/2609.39751) · [PDF](https://arxiv.org/pdf/2609.39751)

## Abstract

Planning with learned world models combines online trajectory optimization with learned value and policy functions for high-dimensional control. Because the planner determines the experience used for learning, while the learned critic and actor in turn score and propose future plans, planning and learning form a closed feedback loop. TD-MPC is a prominent instance of this design. Recent policy-constrained variants strengthen one part of the loop by aligning the learned policy with planner behavior. We introduce PL-MPC (Planning-Learning MPC), which additionally modifies critic supervision and planner terminal-value estimation. Hybrid multi-step TD targets expose critic updates to more realized rewards before bootstrapping; disagreement-aware terminal estimates reduce the influence of uncertain critic values during MPPI planning; and return-weighted actor distillation emphasizes planner-executed actions from high-return episodes. The world-model architecture and MPPI optimizer are otherwise unchanged. On HumanoidBench, the largest gains occur on \texttt{balance-hard}, where Total Average Return (TAR) increases from $98\pm18$ to $387\pm255$, and \texttt{hurdle}, from $199\pm13$ to $466\pm200$; performance across the broader benchmark remains task dependent, and PL-MPC remains competitive on DMControl. Controlled ablations show different component interactions across the two tasks. We further demonstrate zero-shot sim-to-real transfer on wrench-nut alignment with a 7-DoF KUKA IIWA14, obtaining higher observed success than TD-M(PC)^2 on the training object size and two unseen sizes. Code and data will be available at: https://pl-mpc-humanoid.github.io.

## TL;DR

Planning with learned world models combines online trajectory optimization with learned value and policy functions for high-dimensional control. Because the planner determines the experience used for learning, while the learned critic and actor in turn score and propose future plans, planning and learning form a closed feedback loop.

## Related
<!-- [[other-paper-citekey]] -->
