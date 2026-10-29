---
citekey: "luuProgressGuidedPreferenceGenerationAligningGenerativeControlPolicies2026"
title: "Progress-Guided Preference Generation for Aligning Generative Control Policies"
authors: ["Tung M. Luu", "Tri Ton", "Duc M. Nguyen", "Xuan Thanh Nguyen", "Nguyen Gia Binh", "Quang Tan Nguyen", "Vu Duong", "Daniel Sonntag", "Duy M. H. Nguyen", "Vien Anh Ngo", "Chang D. Yoo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.25692"
doi: "10.48550/arXiv.2610.25692"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Progress-Guided Preference Generation for Aligning Generative Control Policies

> Tung M. Luu, Tri Ton, Duc M. Nguyen, Xuan Thanh Nguyen, Nguyen Gia Binh, Quang Tan Nguyen, Vu Duong, Daniel Sonntag, Duy M. H. Nguyen, Vien Anh Ngo, Chang D. Yoo · 2026
> [arXiv](https://arxiv.org/abs/2610.25692) · [PDF](https://arxiv.org/pdf/2610.25692)

## Abstract

Generative policies have achieved strong performance in imitation learning tasks, but their success is often constrained by the limited availability of expert demonstrations. Although preference-based fine-tuning can leverage suboptimal rollouts to improve performance, existing approaches heavily rely on expensive human annotations. In this work, we introduce Progress-Guided Preference Generation (PGPG), an unsupervised preference alignment framework that eliminates the need for human-in-the-loop supervision. Our method leverages ordered coverage alignment to measure sequential progress relative to a small set of expert demonstrations, enabling the automatic extraction of pseudo-preference labels from autonomously collected rollouts. Furthermore, we introduce key enhancements to improve the reliability of these progress-guided preferences, enabling effective fine-tuning of pretrained generative policies without requiring manually designed reward functions. Extensive experiments across a suite of challenging long-horizon manipulation tasks demonstrate that PGPG outperforms standard supervised fine-tuning baselines. Moreover, our conceptually simple framework is broadly applicable across multiple classes of generative policies, demonstrating strong versatility when integrated with both diffusion and flow-matching policies.

## TL;DR

Generative policies have achieved strong performance in imitation learning tasks, but their success is often constrained by the limited availability of expert demonstrations. Although preference-based fine-tuning can leverage suboptimal rollouts to improve performance, existing approaches heavily rely on expensive human annotations.

## Related
<!-- [[other-paper-citekey]] -->
