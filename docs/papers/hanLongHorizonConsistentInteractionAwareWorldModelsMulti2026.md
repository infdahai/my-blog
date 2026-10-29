---
citekey: "hanLongHorizonConsistentInteractionAwareWorldModelsMulti2026"
title: "Long-Horizon Consistent and Interaction-Aware World Models for Multi-Style End-to-End Driving"
authors: ["Yuxuan Han", "Kunyuan Wu", "Liyunong Yang", "Zilu Wang", "Cansen Jiang", "Yi Xiao", "Liang Hu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.03225"
doi: "10.48550/arXiv.2609.03225"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Long-Horizon Consistent and Interaction-Aware World Models for Multi-Style End-to-End Driving

> Yuxuan Han, Kunyuan Wu, Liyunong Yang, Zilu Wang, Cansen Jiang, Yi Xiao, Liang Hu · 2026
> [arXiv](https://arxiv.org/abs/2609.03225) · [PDF](https://arxiv.org/pdf/2609.03225)

## Abstract

End-to-end autonomous driving has increasingly adopted world model-based reinforcement learning frameworks to improve learning efficiency through \textit{imagined rollouts}. However, existing world models suffer from three key limitations: temporal inconsistency in long-horizon imagined rollouts, inadequate modeling of ego-environment interactions, and limited adaptability to diverse driving styles. To address these challenges, we propose \textit{StyleDrive}, a world-model-based learning framework that jointly enforces long-horizon consistency, explicitly disentangles interactive traffic states, and supports multi-style policy optimization within a unified learning paradigm. First, we introduce a temporal consistency regularization that integrates historical latent states through gated cross-attention, stabilizing long-horizon imagined rollouts and mitigating error accumulation. Second, we design an explicit state disentanglement module that separates ego-relevant from ego-irrelevant interactive states, enabling more interpretable and efficient decision-making in complex traffic scenarios. Third, we enable multi-style driving behaviors through Group Relative Policy Optimization, which replaces per-step reward optimization with trajectory-wise relative advantages, reducing reward variance and supporting diverse driving styles without retraining. We evaluate StyleDrive on the Bench2Drive closed-loop driving benchmark, achieving a driving score of 88.44 (+17.08 over the previous best world model-based method) and a success rate of 66.82 (+16.58). Furthermore, we deploy StyleDrive on a real automated guided vehicle platform and demonstrate promising sim-to-real transfer capability in dynamic driving scenarios.

## TL;DR

End-to-end autonomous driving has increasingly adopted world model-based reinforcement learning frameworks to improve learning efficiency through \textit{imagined rollouts}. However, existing world models suffer from three key limitations: temporal inconsistency in long-horizon imagined rollouts, inadequate modeling of ego-environment interactions, and limited adaptability to diverse driving styles.

## Related
<!-- [[other-paper-citekey]] -->
