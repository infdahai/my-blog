---
citekey: "xuPredictiveLongHorizonProgressModelingActionAwareQuantification2026"
title: "Predictive Long-Horizon Progress Modeling with Action-Aware Quantification"
authors: ["Tianchi Xu", "Yalin Zheng", "Yangxin Zhu", "Ruonan Ren", "Zheng Fu", "Yunlong Wang", "Yuanxin Zhong"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32776"
doi: "10.48550/arXiv.2610.32776"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# Predictive Long-Horizon Progress Modeling with Action-Aware Quantification

> Tianchi Xu, Yalin Zheng, Yangxin Zhu, Ruonan Ren, Zheng Fu, Yunlong Wang, Yuanxin Zhong · 2026
> [arXiv](https://arxiv.org/abs/2610.32776) · [PDF](https://arxiv.org/pdf/2610.32776)

## Abstract

Quantitative and dense task progress feedback is essential for robotic manipulation across data curation, policy evaluation, and reinforcement learning. Existing progress annotations often rely on sparse keyframe markings derived from subjective manual judgments, limiting their scalability and cross-task consistency, particularly in long-horizon manipulation. To overcome these challenges, we propose action-aware quantification, a unified progress specification that decomposes long-horizon trajectories into object-level subtasks via a vision-language model (VLM) and assigns weighted action credits to capture fine-grained execution dynamics. Using VLM auto-labeling and human calibration, we construct an 800+ hour training video dataset and LOOM, a long-horizon progress benchmark containing 19,618 human-calibrated evaluation frames. To model these dense progress dynamics, we introduce NimCritic, a predictive progress critic trained via Joint Video-Progress Learning. We further incorporate Historical Progress Perturbation to mitigate sequential drift, and design a contrastive Video-Progress Alignment objective that bridges asymmetric expert streams by mutually grounding intermediate visual dynamics and denoised progress trajectories. NimCritic matches or outperforms state-of-the-art process reward models (PRMs) on the established Video Progress Benchmark (VPB) and LOOM, surpassing GVL (GPT-6-Sol) on VPB by about 65% in terminal success accuracy (TSA). On the large-scale RoboArena policy evaluation benchmark, it also retrieves human-selected successful rollouts with about 97% overall recall. These results establish action-aware quantification as a scalable foundation for dense progress feedback in robotic manipulation.

## TL;DR

Quantitative and dense task progress feedback is essential for robotic manipulation across data curation, policy evaluation, and reinforcement learning. Existing progress annotations often rely on sparse keyframe markings derived from subjective manual judgments, limiting their scalability and cross-task consistency, particularly in long-horizon manipulation.

## Related
<!-- [[other-paper-citekey]] -->
