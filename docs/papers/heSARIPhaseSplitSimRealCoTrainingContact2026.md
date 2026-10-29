---
citekey: "heSARIPhaseSplitSimRealCoTrainingContact2026"
title: "SARI: Phase-Split Sim-Real Co-Training for Contact-Rich Manipulation"
authors: ["Xingxin He", "Yuxuan Jiang", "Haonan Zhang", "Chuhan Cui", "Kaile Li", "Zhongxing Zheng", "Caihao Xu", "Ziqi Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.02804"
doi: "10.48550/arXiv.2610.02804"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-05
---

# SARI: Phase-Split Sim-Real Co-Training for Contact-Rich Manipulation

> Xingxin He, Yuxuan Jiang, Haonan Zhang, Chuhan Cui, Kaile Li, Zhongxing Zheng, Caihao Xu, Ziqi Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.02804) · [PDF](https://arxiv.org/pdf/2610.02804)

## Abstract

Vision-language-action (VLA) models often require costly real-world demonstrations to adapt to contact-rich manipulation tasks, particularly when generalization across object placements is needed. We propose SARI (Simulated Approach, Real Interaction), a phase-split sim-and-real co-training framework built on a simple insight: spatial coverage and contact physics should be acquired from the domains best suited to them. Specifically, free-space approaches require spatial diversity but tolerate modest simulation gaps, making them ideal for synthetic generation; conversely, contact interactions demand accurate physics but vary little across object placements, allowing a few real demonstrations to generalize across the workspace. SARI generates diverse simulated approaches in a photorealistic digital twin while collecting real contact interactions at only a few placements. Post-trained on these phase-segmented demonstrations, a single policy seamlessly stitches simulated approaches with real contact interactions using visual appearance alignment and a shared camera-relative action representation--without explicit phase labels or hand-coded switches. Across five real-world contact-rich manipulation tasks, SARI reduces real-data collection time by 34.3% and achieves 27.5% success at unseen placements, where all full-task sim-real baselines fail completely (0%).

## TL;DR

Vision-language-action (VLA) models often require costly real-world demonstrations to adapt to contact-rich manipulation tasks, particularly when generalization across object placements is needed. We propose SARI (Simulated Approach, Real Interaction), a phase-split sim-and-real co-training framework built on a simple insight: spatial coverage and contact physics should be acquired from the domains best suited to them.

## Related
<!-- [[other-paper-citekey]] -->
