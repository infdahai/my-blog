---
citekey: "linUniInterveneAdaptiveInterventionAgentEfficientRealWorldReinforcement2026"
title: "UniIntervene++: An Adaptive Intervention Agent for Efficient Real-World Reinforcement Learning"
authors: ["Yudong Lin", "Haoyuan Deng", "Zhuoxuan Yuan", "Zaijia Yang", "Yuanjiang Xue", "Ziwei Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.03620"
doi: "10.48550/arXiv.2610.03620"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-06
---

# UniIntervene++: An Adaptive Intervention Agent for Efficient Real-World Reinforcement Learning

> Yudong Lin, Haoyuan Deng, Zhuoxuan Yuan, Zaijia Yang, Yuanjiang Xue, Ziwei Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.03620) · [PDF](https://arxiv.org/pdf/2610.03620)

## Abstract

Online reinforcement learning (RL) enables robot policies to improve through physical interaction, but the assistance they require changes as their competence evolves. Existing intervention strategies based on offline estimates or fixed decision rules can therefore become mismatched to the current policy. To address this, we propose UniIntervene++, an adaptive intervention agent that learns to allocate control between autonomous execution and heterogeneous assisted behaviors during online RL. Specifically, UniIntervene++ first formulates the evolving RL policy, trajectory correction, and a task-structured CodePolicy as Options in a unified semi-Markov decision process and learns their relative values online. Building on this, competence-adaptive intervention periodically probes the RL policy through unassisted execution, keeping control allocation responsive to its evolving capability. Finally, coupled experience learning allows assisted behaviors to improve the RL policy, whose evolving outcomes in turn reshape future intervention decisions. In this way, UniIntervene++ jointly determines when to intervene, how to intervene, and when to return control as the RL policy improves. Across five real-world manipulation tasks, UniIntervene++ achieves an average success rate of 89.67%, outperforming all baselines by at least 6 percentage points, while reducing human intervention to 0.77%, a relative reduction of at least 94.6% from the best baseline. Code is available in our \href{https://github.com/dannyyudong/An-Adaptive-Intervention-Agent-for-Efficient-Real-World-Reinforcement-Learning}{GitHub repository}.

## TL;DR

Online reinforcement learning (RL) enables robot policies to improve through physical interaction, but the assistance they require changes as their competence evolves. Existing intervention strategies based on offline estimates or fixed decision rules can therefore become mismatched to the current policy.

## Related
<!-- [[other-paper-citekey]] -->
