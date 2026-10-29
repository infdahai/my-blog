---
citekey: "tangCoLTDriveCounterfactualLongTailBenchmarkingKnowledgePreserving2026"
title: "CoLT-Drive: Counterfactual Long-Tail Benchmarking and Knowledge-Preserving Adaptation for Driving Affordance Prediction"
authors: ["Zhengxu Tang", "Guofeng Cui", "Ziyu Gong", "Xiaozhou Zhang", "Ruifeng Deng", "Chengzhi Qi", "Ke Chen", "Sachin Patil", "Tianjun Xiao", "Langechuan Liu", "Pichao Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.00242"
doi: "10.48550/arXiv.2609.00242"
tags: [paper, embodied-ai, "cs.AI", "cs.CL", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-04
---

# CoLT-Drive: Counterfactual Long-Tail Benchmarking and Knowledge-Preserving Adaptation for Driving Affordance Prediction

> Zhengxu Tang, Guofeng Cui, Ziyu Gong, Xiaozhou Zhang, Ruifeng Deng, Chengzhi Qi, Ke Chen, Sachin Patil, Tianjun Xiao, Langechuan Liu, Pichao Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.00242) · [PDF](https://arxiv.org/pdf/2609.00242)

## Abstract

Long-tail autonomous driving failures are often framed as rare-object recognition errors. We argue that this view is incomplete: the decision-critical question is not only whether a model recognizes an unusual object, but whether it infers how that object changes the ego vehicle's feasible high-level actions. We formalize this problem as decision-level driving affordance prediction, where a model maps a front-view image, ego-motion history, and navigation command to a structured longitudinal--lateral meta-action. To evaluate this capability, we introduce CoLT-Drive, a 3,536-sample counterfactual long-tail benchmark that inserts rare objects into otherwise fixed driving scenes and measures whether models predict acceptable action pairs. To improve deployable small VLMs, we propose KPA, a knowledge-preserving adaptation framework that combines structured perception-to-decision prompting, SLERP-based expert merging, and RegMoE, a regime-aware LoRA mixture-of-experts module. KPA preserves the pretrained model's open-world knowledge while allocating lightweight adaptation capacity to different driving decision regimes. Experiments on an in-domain driving split and CoLT-Drive show that KPA achieves 60.8\% pair accuracy on CoLT-Drive, outperforming the pretrained Qwen3-VL-2B baseline (50.3\%) and LoRA SFT (32.4\%) while maintaining competitive in-domain accuracy. Our benchmark and code are available at https://huggingface.co/datasets/tangzx2024/CoLT-Drive and https://github.com/tangzhengxu/CoLT-Drive.

## TL;DR

Long-tail autonomous driving failures are often framed as rare-object recognition errors. We argue that this view is incomplete: the decision-critical question is not only whether a model recognizes an unusual object, but whether it infers how that object changes the ego vehicle's feasible high-level actions.

## Related
<!-- [[other-paper-citekey]] -->
