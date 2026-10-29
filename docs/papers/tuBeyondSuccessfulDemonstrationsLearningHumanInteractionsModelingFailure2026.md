---
citekey: "tuBeyondSuccessfulDemonstrationsLearningHumanInteractionsModelingFailure2026"
title: "Beyond Successful Robot Demonstrations: Learning from Human Interactions and Modeling Failure Dynamics"
authors: ["Peiyan Tu", "Cong Wang", "Hanxin Zhu", "Xin Jin", "Zhibo Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13522"
doi: "10.48550/arXiv.2610.13522"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Beyond Successful Robot Demonstrations: Learning from Human Interactions and Modeling Failure Dynamics

> Peiyan Tu, Cong Wang, Hanxin Zhu, Xin Jin, Zhibo Chen · 2026
> [arXiv](https://arxiv.org/abs/2610.13522) · [PDF](https://arxiv.org/pdf/2610.13522)

## Abstract

Action-conditioned world models offer a promising foundation for generalist robotic intelligence by predicting the consequences of actions. However, existing robotic datasets provide limited coverage of the diverse interaction dynamics required for generalizable world modeling. Large-scale egocentric human videos offer complementary interaction experience, yet the embodiment gap between human hands and robotic manipulators hinders effective cross-embodiment learning. Meanwhile, the predominance of successful demonstrations leaves failure dynamics substantially underrepresented, limiting the ability of world models to anticipate unsuccessful executions. To address these limitations, we introduce HF-WM, an action-conditioned world model that combines Human interaction learning with Failure-aware post-training. To bridge the embodiment gap, we develop a dual-branch framework that couples video generation with auxiliary pointflow prediction, using stabilized pointflow as a unified motion representation across human and robot interactions while suppressing egocentric camera motion. To improve failure modeling, we further perform Group Relative Policy Optimization (GRPO) post-training on perturbed actions derived from successful demonstrations, guided by action alignment and physical plausibility rewards, enabling the model to learn plausible failure dynamics without paired ground-truth videos. Extensive experiments demonstrate that HF-WM achieves state-of-the-art performance in action-conditioned video generation and exhibits strong utility for policy evaluation in downstream robotic tasks.

## TL;DR

Action-conditioned world models offer a promising foundation for generalist robotic intelligence by predicting the consequences of actions. However, existing robotic datasets provide limited coverage of the diverse interaction dynamics required for generalizable world modeling.

## Related
<!-- [[other-paper-citekey]] -->
