---
citekey: "zhouCoRELearningCollaborationRoleExpertsDecentralizedCollaborativeManipulation2026"
title: "CoRE: Learning Collaboration-Role Experts for Decentralized Collaborative Manipulation with One Policy"
authors: ["Yanan Zhou", "Zhaoyan Qian", "Zihao Li", "Mingyuan Ba", "Ranpeng Qiu", "Weiming Zhi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07752"
doi: "10.48550/arXiv.2610.07752"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# CoRE: Learning Collaboration-Role Experts for Decentralized Collaborative Manipulation with One Policy

> Yanan Zhou, Zhaoyan Qian, Zihao Li, Mingyuan Ba, Ranpeng Qiu, Weiming Zhi · 2026
> [arXiv](https://arxiv.org/abs/2610.07752) · [PDF](https://arxiv.org/pdf/2610.07752)

## Abstract

Collaborative manipulation requires robots to perform complementary actions as interactions unfold. We study single-policy decentralized collaboration: every robot runs the same policy from its visual observations and proprioception, without task prompts, identity labels, or inter-robot messages. The challenge is to learn complementary team behaviors within shared parameters and select appropriate actions from each robot's local observations. We introduce CoRE, which learns Collaboration-Role Experts from pooled multi-task, multi-robot demonstrations. Fused appearance and geometry provide local interaction evidence. Query-conditioned cross-attention experts provide adaptable prediction paths, which a local router combines at each action-chunk position. During training, an action-expert alignment loss supervises expert selection using relative forced-route prediction errors against demonstrations under fixed inputs, without role labels. Across simulation benchmarks, CoRE achieves the highest average performance among evaluated decentralized methods. Physical experiments demonstrate effective collaboration across diverse manipulation tasks and robustness to partner delays and slowdowns. Project page: https://aus.bot/research/core/.

## TL;DR

Collaborative manipulation requires robots to perform complementary actions as interactions unfold. We study single-policy decentralized collaboration: every robot runs the same policy from its visual observations and proprioception, without task prompts, identity labels, or inter-robot messages.

## Related
<!-- [[other-paper-citekey]] -->
