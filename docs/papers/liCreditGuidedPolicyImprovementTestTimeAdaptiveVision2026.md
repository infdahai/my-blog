---
citekey: "liCreditGuidedPolicyImprovementTestTimeAdaptiveVision2026"
title: "Credit-Guided Policy Improvement for Test-time Adaptive Vision-Language Navigation"
authors: ["Yang Li", "Sijia Zhang", "Yihan Li", "Aming WU", "Zihao Zhang", "Ziju Han", "Yahong Han"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.37591"
doi: "10.48550/arXiv.2609.37591"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Credit-Guided Policy Improvement for Test-time Adaptive Vision-Language Navigation

> Yang Li, Sijia Zhang, Yihan Li, Aming WU, Zihao Zhang, Ziju Han, Yahong Han · 2026
> [arXiv](https://arxiv.org/abs/2609.37591) · [PDF](https://arxiv.org/pdf/2609.37591)

## Abstract

Test-time adaptation for vision-language navigation (TTA-VLN) enables pretrained policies to adapt online to unseen environments using only test-time observations and interaction history. However, distribution shifts can distort local action preferences and lead to off-course decisions. Existing methods rely on predictive uncertainty, trajectory-level feedback, or accumulated adaptation experience to correct such deviations. These signals, however, do not directly reveal whether an executed action supports instruction-guided progress toward the goal. Moreover, a plausible corrective signal does not guarantee a reliable policy update. The key challenge is thus twofold: identifying interactions that support goal-directed improvement and determining whether the resulting updates are worth retaining. We observe that each executed action induces an immediate observation transition, providing evidence of its local consequences. Based on this insight, we propose Credit-Guided Policy Improvement (CGPI), which recovers signed, reference-relative decision credit from action-induced observation transitions without external outcome feedback. With the pretrained navigation policy frozen, CGPI uses this credit to propose lightweight adaptation updates and verifies them against prior credit-supported interactions. Updates are retained only when supported and rolled back otherwise. CGPI achieves consistent gains across the evaluated VLN benchmarks and navigation backbones, while qualitative robot trials further illustrate the feasibility of zero-shot sim-to-real transfer.

## TL;DR

Test-time adaptation for vision-language navigation (TTA-VLN) enables pretrained policies to adapt online to unseen environments using only test-time observations and interaction history. However, distribution shifts can distort local action preferences and lead to off-course decisions.

## Related
<!-- [[other-paper-citekey]] -->
