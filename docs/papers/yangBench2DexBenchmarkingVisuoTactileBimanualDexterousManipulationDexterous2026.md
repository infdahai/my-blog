---
citekey: "yangBench2DexBenchmarkingVisuoTactileBimanualDexterousManipulationDexterous2026"
title: "Bench2Dex: Benchmarking Visuo-Tactile Bimanual Dexterous Manipulation Across Dexterous Hands"
authors: ["Zhenjie Yang", "Yideng Zhang", "Dongjie Zhang", "Chenyu Jiang", "Xianshuai Liu", "Yufeng Li", "Zuhao Ge", "Xingyu Jiao", "Zheng Zhang", "Kaiyu He", "He Wang", "Yuwen Zhong", "Yi Deng", "Muyun Jiang", "Xianliang Huang", "Haisheng Su", "Donghang Zhang", "Jian Zhang", "Xue Yang", "Hongyang Li", "Zuxuan Wu", "Yu-Gang Jiang", "Xiaosong Jia", "Junchi Yan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.15726"
doi: "10.48550/arXiv.2609.15726"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Bench2Dex: Benchmarking Visuo-Tactile Bimanual Dexterous Manipulation Across Dexterous Hands

> Zhenjie Yang, Yideng Zhang, Dongjie Zhang, Chenyu Jiang, Xianshuai Liu, Yufeng Li, Zuhao Ge, Xingyu Jiao, Zheng Zhang, Kaiyu He, He Wang, Yuwen Zhong, Yi Deng, Muyun Jiang, Xianliang Huang, Haisheng Su, Donghang Zhang, Jian Zhang, Xue Yang, Hongyang Li, Zuxuan Wu, Yu-Gang Jiang, Xiaosong Jia, Junchi Yan · 2026
> [arXiv](https://arxiv.org/abs/2609.15726) · [PDF](https://arxiv.org/pdf/2609.15726)

## Abstract

Tactile sensing provides contact information that can be difficult to infer from vision alone, but tactile hardware for dexterous hands has not converged to a common design. Dexterous hands differ in finger structure, contact surfaces, and sensor layouts, while simulated tactile signals still differ from measurements produced by physical sensors. These factors make it difficult to study visuo-tactile manipulation across diverse dexterous hands within a consistent experimental setting. We present Bench2Dex, a simulation benchmark for visuo-tactile bimanual manipulation across 12 dexterous hands. We adapt existing robot models with a shared simulated tactile interface that converts local contact geometry into image-like tactile observations. The interface provides a consistent observation format across different hand morphologies without attempting to reproduce the output of a specific physical tactile sensor. Bench2Dex includes 26 bimanual manipulation tasks that involve tool use, articulated-object interaction, and multi-stage manipulation, together with about 1.3K human-teleoperated demonstrations. The benchmark provides synchronized visual, tactile, proprioceptive, action, and object-state observations, together with executable task metrics. For robustness, we group seven perturbation types into invariance axis, where the correct action does not change, and equivariance axis, where the correct action changes together with the perturbation. We evaluate ACT, Diffusion Policy, pi0.5, and GR00T N1.5 on Bench2Dex and report their performance and failure modes. Bench2Dex is meant as a platform for studying visuo-tactile learning across dexterous hands. It does not assume that simulated tactile observations can replace real tactile sensing; it offers a shared setting for algorithm development while tactile hardware and simulation models are still evolving.

## TL;DR

Tactile sensing provides contact information that can be difficult to infer from vision alone, but tactile hardware for dexterous hands has not converged to a common design. Dexterous hands differ in finger structure, contact surfaces, and sensor layouts, while simulated tactile signals still differ from measurements produced by physical sensors.

## Related
<!-- [[other-paper-citekey]] -->
