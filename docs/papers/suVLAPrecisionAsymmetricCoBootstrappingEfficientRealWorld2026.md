---
citekey: "suVLAPrecisionAsymmetricCoBootstrappingEfficientRealWorld2026"
title: "VLA-Precision: Asymmetric Co-Bootstrapping for Efficient Real-World Online RL of Vision-Language-Action Models"
authors: ["Chenyu Su", "Zhaolong Shen", "Yuan Qian", "Chen Qian", "Rui Zhang", "Feng Yan", "Weixing Chen", "Fei Zhang", "Jiamin Wang", "Shuang Cong", "Weiwei Shang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04355"
doi: "10.48550/arXiv.2609.04355"
tags: [paper, embodied-ai, "cs.AI", "cs.HC", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# VLA-Precision: Asymmetric Co-Bootstrapping for Efficient Real-World Online RL of Vision-Language-Action Models

> Chenyu Su, Zhaolong Shen, Yuan Qian, Chen Qian, Rui Zhang, Feng Yan, Weixing Chen, Fei Zhang, Jiamin Wang, Shuang Cong, Weiwei Shang · 2026
> [arXiv](https://arxiv.org/abs/2609.04355) · [PDF](https://arxiv.org/pdf/2609.04355)

## Abstract

Pretrained vision-language-action (VLA) models enable broad manipulation but remain unreliable in tasks demanding precision and repeatability. Applying real-world online reinforcement learning (RL) to VLA post-training enables autonomous trial-and-error improvement beyond demonstrations alone, but exposes two bottlenecks: 1) unreliable value signals can induce policy drift; 2) large-VLA overhead constrains throughput and sample efficiency. To address these challenges, we present VLA-Precision, an efficient real-world online RL framework featuring the Asymmetric Co-Bootstrapping (ACoB) algorithm and the ACoB-Stream architecture. Specifically, ACoB establishes asymmetric co-bootstrapping across timescales: early intervention-guided behavioral learning rapidly improves policy performance while enhancing online experience quality. As autonomous experience accumulates, global return propagation and local preference ranking progressively calibrate value estimates, yielding relative action advantages for reference-regularized policy improvement while suppressing drift. To enable ACoB on large VLAs, we develop ACoB-Stream, a closed-loop experience--policy architecture that establishes invariant-state decoupling and on-demand streaming as design principles, delivering up to 10.9$\times$ improvements in throughput and computational efficiency. Extensive evaluations on nine high-precision chemistry tasks across four categories and four robot embodiments show that VLA-Precision achieves 98.3\% mean success rate in 45.8 min/task, with 27.6 s episodes running at 1.2$\times$ and 1.8$\times$ the speeds of VLA and RL baselines. Resources are available at https://vla-precision.github.io.

## TL;DR

Pretrained vision-language-action (VLA) models enable broad manipulation but remain unreliable in tasks demanding precision and repeatability. Applying real-world online reinforcement learning (RL) to VLA post-training enables autonomous trial-and-error improvement beyond demonstrations alone, but exposes two bottlenecks: 1) unreliable value signals can induce policy drift; 2) large-VLA overhead constrains throughput and sample efficiency.

## Related
<!-- [[other-paper-citekey]] -->
