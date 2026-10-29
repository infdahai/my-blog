---
citekey: "yuanWorldModelsWorldActionModelsRethinkingNextState2026"
title: "From World Models to World Action Models: Rethinking Next-State Prediction"
authors: ["Tingyu Yuan", "Ziming Ji", "Biaoliang Guan", "Wen Ye", "Wenrui Tian", "Zhaopeng Gu", "Feihong Zhang", "Xu Yang", "Yan Huang", "Zhaowen Li", "Chaoyang Zhao", "Jinqiao Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34414"
doi: "10.48550/arXiv.2609.34414"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# From World Models to World Action Models: Rethinking Next-State Prediction

> Tingyu Yuan, Ziming Ji, Biaoliang Guan, Wen Ye, Wenrui Tian, Zhaopeng Gu, Feihong Zhang, Xu Yang, Yan Huang, Zhaowen Li, Chaoyang Zhao, Jinqiao Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.34414) · [PDF](https://arxiv.org/pdf/2609.34414)

## Abstract

Predicting the next state is a core paradigm of World Models for modeling physical dynamics, emphasizing prediction fidelity. As World Models evolve into World-Action Models (WAMs), existing methods still fix the next state before training as RGB, a single latent feature, or a static combination of predefined targets, thereby constraining action learning to the inductive biases preserved by a particular representation. To address this limitation, we propose CF-WAM, a dynamic next-state prediction framework that samples visual, semantic, geometric, and interaction projections of the same future, standardizes them into a common video form, and supervises a unified WAM across these projections. The action-relevant constraints exposed by these projections accumulate across training steps, forcing WAM to capture the underlying state-transition structure that supports multiple projections of the same action-conditioned future. This dynamic mechanism also provides a natural cross-embodiment dynamics reference frame for Human and Robot learning. By jointly learning across different next-state parameterizations, heterogeneous Human and Robot experience can bypass appearance differences and directly contribute to shared state-transition learning, improving cross-embodiment generalization. Experiments show that CF-WAM improves both training efficiency and final control performance, while translating Human experience effectively into policy gains. CF-WAM achieves state-of-the-art performance on RoboCasa-GR1 with an average success rate of 82.50%, while reaching 82.65% on LIBERO-Plus and up to 84.00% in real-world evaluations.

## TL;DR

Predicting the next state is a core paradigm of World Models for modeling physical dynamics, emphasizing prediction fidelity. As World Models evolve into World-Action Models (WAMs), existing methods still fix the next state before training as RGB, a single latent feature, or a static combination of predefined targets, thereby constraining action learning to the inductive biases preserved by a particular representation.

## Related
<!-- [[other-paper-citekey]] -->
