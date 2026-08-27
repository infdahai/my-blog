---
citekey: "fangUniDexTokUnifiedDexterousHandTokenizerRealData2026"
title: "UniDexTok: A Unified Dexterous Hand Tokenizer from Real Data"
authors: ["Dong Fang", "Youjun Wu", "Yuanxin Zhong", "Rui Zhang", "Yunlong Wang", "Xiaosong Jia", "Yu-Gang Jiang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.10683"
doi: "10.48550/arXiv.2606.10683"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# UniDexTok: A Unified Dexterous Hand Tokenizer from Real Data

> Dong Fang, Youjun Wu, Yuanxin Zhong, Rui Zhang, Yunlong Wang, Xiaosong Jia, Yu-Gang Jiang · 2026
> [arXiv](https://arxiv.org/abs/2606.10683) · [PDF](https://arxiv.org/pdf/2606.10683)

## Abstract

Dexterous hands are essential for fine-grained manipulation, but their hardware designs vary substantially across embodiments. Differences in kinematics, joint definitions, and degrees of freedom make it difficult to define a shared state representation compared with parallel grippers. As a result, dexterous-hand data remains fragmented and difficult to use for joint training. In this work, we propose the Unified Dexterous Hand Model (UDHM), which maps human and robot hand states into a shared 22-DoF semantic interface. Based on UDHM, we introduce UniDexTok, a retargeting-free state tokenizer that learns embodiment-conditioned discrete tokens from standardized real joint states. UniDexTok provides a unified representation for heterogeneous dexterous hands without relying on retargeting or simulation data. Compared with the recent baseline UniHM, UniDexTok reduces MPJAE from 15.63 degrees to 0.16 degrees and MPJPE from 18.51 mm to 0.18 mm, corresponding to error reductions of 98.98% and 99.03%, respectively. These results improve reconstruction from centimeter-scale to sub-millimeter accuracy. Experiments further show that data from other embodiments improves target-embodiment reconstruction accuracy, demonstrating the benefit of cross-embodiment tokenization. UniDexTok also shows strong zero-shot and few-shot reconstruction ability when new dexterous hands are introduced.

## TL;DR

Dexterous hands are essential for fine-grained manipulation, but their hardware designs vary substantially across embodiments. Differences in kinematics, joint definitions, and degrees of freedom make it difficult to define a shared state representation compared with parallel grippers.

## Related
<!-- [[other-paper-citekey]] -->
