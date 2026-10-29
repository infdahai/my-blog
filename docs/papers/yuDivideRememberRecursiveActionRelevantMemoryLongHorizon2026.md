---
citekey: "yuDivideRememberRecursiveActionRelevantMemoryLongHorizon2026"
title: "Divide-and-Remember: Recursive Action-Relevant Memory for Long-Horizon VLA Policies"
authors: ["Xuehui Yu", "Eason Yu", "Meiyi Wang", "Haozhe Du", "Stefano V. Albrecht", "Harold Soh"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00982"
doi: "10.48550/arXiv.2610.00982"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Divide-and-Remember: Recursive Action-Relevant Memory for Long-Horizon VLA Policies

> Xuehui Yu, Eason Yu, Meiyi Wang, Haozhe Du, Stefano V. Albrecht, Harold Soh · 2026
> [arXiv](https://arxiv.org/abs/2610.00982) · [PDF](https://arxiv.org/pdf/2610.00982)

## Abstract

Vision-language-action (VLA) models struggle on history-dependent manipulation tasks, where the current observation alone does not determine the action, and the policy needs a memory of the history. Existing memory methods decide what to remember by design, for example, keeping frames with large pixel changes, and show inconsistent gains across tasks. We view what to remember as an optimisation problem. From the POMDP formulation of imitation learning, we show that the optimal memory maximises the conditional mutual information $I(a_t; m_t \mid o_t)$ between the action and the memory given the current observation. Intuitively, this means preserving the action-relevant information in the history that is not already contained in the current observation. Based on our analysis, we propose Divide-and-Remember (D&R), a recursive memory method that learns a memory function $m_t = M(h_t)$ and scales to long contexts while staying compute-light. It involves two strategies: (1) the selection over the full history is divided recursively into subproblems of top-$K$ selection over $2K$ tokens, so that fixed-size, lightweight selectors learned end-to-end support an unbounded history; (2) all recursion blocks share one selector, which captures the selection rule common to every block and keeps the method efficient. On RoboMME, a benchmark of 16 long-horizon manipulation tasks that require remembering when, where, what, and how to act, D&R achieves a state-of-the-art average success rate with consistent gains across all four suites under a budget of only 64 tokens; real-robot experiments show the same gain. Code, checkpoints and more results are at https://dnr-memory.github.io/

## TL;DR

Vision-language-action (VLA) models struggle on history-dependent manipulation tasks, where the current observation alone does not determine the action, and the policy needs a memory of the history. Existing memory methods decide what to remember by design, for example, keeping frames with large pixel changes, and show inconsistent gains across tasks.

## Related
<!-- [[other-paper-citekey]] -->
