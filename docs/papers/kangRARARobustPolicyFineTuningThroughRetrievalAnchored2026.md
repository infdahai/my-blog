---
citekey: "kangRARARobustPolicyFineTuningThroughRetrievalAnchored2026"
title: "RARA: Robust Policy Fine-Tuning through Retrieval-Anchored Representation Alignment for Robotic Manipulation"
authors: ["Xuhui Kang", "Sung-Wook Lee", "Yan Zhuang", "Tianle Zhong", "Yen-Ling Kuo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13578"
doi: "10.48550/arXiv.2610.13578"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# RARA: Robust Policy Fine-Tuning through Retrieval-Anchored Representation Alignment for Robotic Manipulation

> Xuhui Kang, Sung-Wook Lee, Yan Zhuang, Tianle Zhong, Yen-Ling Kuo · 2026
> [arXiv](https://arxiv.org/abs/2610.13578) · [PDF](https://arxiv.org/pdf/2610.13578)

## Abstract

Pre-trained robot policies, such as Vision-Language-Action (VLA) models, provide a strong foundation for generalist robotic manipulation, but adapting them to new tasks with only a few demonstrations remains challenging. Directly fine-tuning a pre-trained policy often achieves strong in-distribution performance, yet it can distort the representations learned during pre-training and weaken the model's generalization ability under out-of-distribution shifts. We propose Retrieval-Anchored Representation Alignment (RARA), a two-stage adaptation method, to address this issue. First, RARA retrieves representation features from pretraining with similar task intent and motion, and aligns the policy's representations of the target demonstrations with the pre-trained representations of the retrieved demonstrations. Second, RARA fine-tunes the policy on the target demonstrations while limiting how much its representations of the retrieved demonstrations change during fine-tuning. By reducing the representation mismatch before action learning and preserving pre-trained knowledge during adaptation, RARA limits unnecessary representation drift during fine-tuning. Experiments with Diffusion Policy and GR00T on 13 tasks in RoboTwin, RoboCasa, and on a real robot show that RARA improves the average success of fine-tuning by 9.5 points in-distribution and 13.6 points out-of-distribution, and outperforms all compared baselines. Project page: https://shua-kang.github.io/RARA_robot/

## TL;DR

Pre-trained robot policies, such as Vision-Language-Action (VLA) models, provide a strong foundation for generalist robotic manipulation, but adapting them to new tasks with only a few demonstrations remains challenging. Directly fine-tuning a pre-trained policy often achieves strong in-distribution performance, yet it can distort the representations learned during pre-training and weaken the model's generalization ability under out-of-distribution shifts.

## Related
<!-- [[other-paper-citekey]] -->
