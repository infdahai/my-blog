---
citekey: "huangLifelongSmallObjectNavigationChangingObjectLayoutsBenchmark2026"
title: "Lifelong small-object navigation in changing object layouts: a benchmark and method"
authors: ["Jiagan Huang", "Zikun Zhou", "Zijian Ni", "Hongpeng Wang", "Guangming Lu", "Jun Yu", "Wenjie Pei"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.10125"
doi: "10.48550/arXiv.2610.10125"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# Lifelong small-object navigation in changing object layouts: a benchmark and method

> Jiagan Huang, Zikun Zhou, Zijian Ni, Hongpeng Wang, Guangming Lu, Jun Yu, Wenjie Pei · 2026
> [arXiv](https://arxiv.org/abs/2610.10125) · [PDF](https://arxiv.org/pdf/2610.10125)

## Abstract

Household robots need to continually navigate to different objects in the same environment, many of which are small and portable, such as tools and toys. Their small visual footprint and frequent occlusion make reliable observation difficult, and they may be moved by people without the robot observing the changes. We formulate this challenging task as Lifelong Small-object Navigation in Changing Object Layouts (LiSoNav-COL). Agents must seek suitable viewpoints for reliable observation, accumulate and reuse scene knowledge to efficiently locate subsequent targets, and update outdated memory after object relocation. To eliminate the need for prior scene scanning, we also require agents to start navigation with empty scene memory. Although practical, this task still lacks benchmarks designed around its defining assumptions. To bridge this gap, we introduce LiSoNav-Eval, a dedicated benchmark spanning 28 indoor scenes with 45 small-object categories. Its lifelong navigation sequences include both unchanged and relocated targets to evaluate memory reuse and adaptation to object relocation. To address this challenging task, we propose a navigation method based on multi-view Inspection with Viewpoint-Anchored Memory, dubbed IVAM-Nav. IVAM-Nav actively observes supporting surfaces from complementary viewpoints for reliable small-object perception and anchors the resulting memory to their observation viewpoints, supporting relational memory reuse and revalidation under similar viewing conditions. Extensive experiments on LiSoNav-Eval demonstrate favorable performance of IVAM-Nav against representative methods. Benchmark analyses also show that smaller objects, larger environments, and longer relocation distances pose greater challenges. The dataset and code are available here.

## TL;DR

Household robots need to continually navigate to different objects in the same environment, many of which are small and portable, such as tools and toys. Their small visual footprint and frequent occlusion make reliable observation difficult, and they may be moved by people without the robot observing the changes.

## Related
<!-- [[other-paper-citekey]] -->
