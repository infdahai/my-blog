---
citekey: "wanCometVLACoTrainingEmbodiedDataPyramidPhysicalUnderstanding2026"
title: "CometVLA: Co-Training on an Embodied Data Pyramid towards Physical Understanding"
authors: ["Hanwen Wan", "Dafeng Chi", "Linbo Zhai", "Tianao Shen", "Yuzheng Zhuang", "Tianle Zhang", "Peidong Liu", "Liang Lin", "Xiaoqiang Ji"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30289"
doi: "10.48550/arXiv.2608.30289"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# CometVLA: Co-Training on an Embodied Data Pyramid towards Physical Understanding

> Hanwen Wan, Dafeng Chi, Linbo Zhai, Tianao Shen, Yuzheng Zhuang, Tianle Zhang, Peidong Liu, Liang Lin, Xiaoqiang Ji · 2026
> [arXiv](https://arxiv.org/abs/2608.30289) · [PDF](https://arxiv.org/pdf/2608.30289)

## Abstract

Vision-language-action (VLA) models remain brittle in manipulation tasks that require physical commonsense. Current physical VQA data is typically disembodied and misaligned with robot action domains. Egocentric videos are used only as auxiliary pre-training. It remains unclear whether improved VLM physical understanding actually benefits downstream action generation. Therefore, we present CometVLA to close this gap. We construct CometData and CometBench, an embodied physical VQA corpus and benchmark strictly aligned with the robot's action data and embodiment. We introduce Global Action Prior (GAP) tokens, a compact learnable bottleneck that isolates task-agnostic motion regularities and lets the action head consume physical commonsense without corrupting the pre-trained VLM backbone. We co-train CometVLA across the embodied data pyramid, spanning teleoperation, simulation, egocentric trajectories, and VQA layers. On real-world manipulation tasks and RoboTwin simulation, CometVLA consistently outperforms strong VLA baselines. Correlation analysis shows that stronger VLM performance on CometBench indicates higher VLA success rates. Results demonstrate that physical understanding pre-training genuinely benefits downstream manipulation.

## TL;DR

Vision-language-action (VLA) models remain brittle in manipulation tasks that require physical commonsense. Current physical VQA data is typically disembodied and misaligned with robot action domains.

## Related
<!-- [[other-paper-citekey]] -->
