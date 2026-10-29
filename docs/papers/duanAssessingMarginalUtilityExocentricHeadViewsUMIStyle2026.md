---
citekey: "duanAssessingMarginalUtilityExocentricHeadViewsUMIStyle2026"
title: "Assessing the Marginal Utility of Exocentric Head Views in UMI-Style Large-FoV Wrist-Camera Manipulation"
authors: ["Yuhui Duan", "Shi Jin", "Yuntian Wang", "Jin Wang", "Siao Liu", "Wenchang Gao", "Zhaxizhuoma", "Yan Ding"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14075"
doi: "10.48550/arXiv.2610.14075"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Assessing the Marginal Utility of Exocentric Head Views in UMI-Style Large-FoV Wrist-Camera Manipulation

> Yuhui Duan, Shi Jin, Yuntian Wang, Jin Wang, Siao Liu, Wenchang Gao, Zhaxizhuoma, Yan Ding · 2026
> [arXiv](https://arxiv.org/abs/2610.14075) · [PDF](https://arxiv.org/pdf/2610.14075)

## Abstract

Multi-view perception is often treated as a safe design choice for robot manipulation: if one camera is useful, more cameras should be better. We revisit that assumption in tabletop bimanual manipulation by comparing policies trained with two large-field-of-view (FoV) wrist cameras against policies that additionally receive a head view, using controlled-variable experiments on a real bimanual platform. Across three tabletop tasks, adding a head view does not consistently improve task completion or execution quality: when the wrist cameras already observe the objects, grippers, and goal regions, wrist-only policies form a strong baseline. Restricting the wrist-camera FoV increases the potential value of a head view, but performance improves most reliably when the added view supplies concentrated, task-relevant information: region-of-interest (ROI) cropping yields more consistent head-view gains than the uncropped image, which is dominated by background and task-irrelevant regions. The data-scaling results further suggest an interaction between FoV and demonstration count: wide observations improve coverage but may require more data to stabilize, and they may reach a higher performance ceiling once enough demonstrations are available. These results suggest that camera design should be framed as a task-relevance and information-density problem rather than as a simple count of input views.

## TL;DR

Multi-view perception is often treated as a safe design choice for robot manipulation: if one camera is useful, more cameras should be better. We revisit that assumption in tabletop bimanual manipulation by comparing policies trained with two large-field-of-view (FoV) wrist cameras against policies that additionally receive a head view, using controlled-variable experiments on a real bimanual platform.

## Related
<!-- [[other-paper-citekey]] -->
