---
citekey: "wangEWAMEmergentDepthWiseSpecializationUnifiedEmbodiedModel2026"
title: "EWAM: Emergent Depth-Wise Specialization in a Unified Embodied Model -- From Semantic Understanding through Visual Foresight to Action"
authors: ["Hao Wang", "Jiajun Wen", "Jingzhi Liu", "Shuoshuo Xue", "Zhiliang Chen", "Min Lin", "Yicheng Chang", "Xiaoyu Guo", "Yukang Zhuo", "Zheng Chong", "Yunshuang Nie", "Jian Zhang", "Weijia Liufu", "Qingman Wu", "Heming Xu", "Bingchang Song", "Dantong Wu", "Zhiyuan Wang", "Hang Xu", "Jianhua Han", "Bokui Chen", "Shen Zhao", "Rui Li", "Xiaodan Liang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.39973"
doi: "10.48550/arXiv.2609.39973"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# EWAM: Emergent Depth-Wise Specialization in a Unified Embodied Model -- From Semantic Understanding through Visual Foresight to Action

> Hao Wang, Jiajun Wen, Jingzhi Liu, Shuoshuo Xue, Zhiliang Chen, Min Lin, Yicheng Chang, Xiaoyu Guo, Yukang Zhuo, Zheng Chong, Yunshuang Nie, Jian Zhang, Weijia Liufu, Qingman Wu, Heming Xu, Bingchang Song, Dantong Wu, Zhiyuan Wang, Hang Xu, Jianhua Han, Bokui Chen, Shen Zhao, Rui Li, Xiaodan Liang · 2026
> [arXiv](https://arxiv.org/abs/2609.39973) · [PDF](https://arxiv.org/pdf/2609.39973)

## Abstract

Vision-language-action (VLA) policies emphasize semantic understanding, whereas world-action models (WAMs) learn predictive representations of environment dynamics. Systems that expose a policy to both sources often still concentrate action computation on a single expert. We present EWAM, an action-centric unified embodied model whose asymmetric joint attention lets action tokens read semantic, current-visual, predicted-future, and action information at every layer while the perceptual experts retain their distinct roles. Without layer-wise supervision, EWAM develops an emergent depth-wise specialization: action queries attend mainly to vision-language features in shallow layers, to predicted future frames in intermediate layers, and to action tokens themselves in deep layers. This handoff replicates across tasks and is stable across denoising steps. Checkpoint tracking and causal interventions show that it is learned and that action generation depends on it. EWAM is pretrained in two separate regimes, one on cross-embodiment robot trajectories and one on human egocentric video. In simulation and real-robot experiments, it surpasses existing VLA, WAM, and hybrid baselines. Human egocentric data improve both cross-embodiment transfer and real-robot robustness, and subtask-phase supervision improves long-horizon completion. Together, these results suggest that unified embodied learning can induce an ordered internal progression from semantic understanding, through visual foresight, to action formation.

## TL;DR

Vision-language-action (VLA) policies emphasize semantic understanding, whereas world-action models (WAMs) learn predictive representations of environment dynamics. Systems that expose a policy to both sources often still concentrate action computation on a single expert.

## Related
<!-- [[other-paper-citekey]] -->
