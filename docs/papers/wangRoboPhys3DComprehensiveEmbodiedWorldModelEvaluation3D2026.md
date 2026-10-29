---
citekey: "wangRoboPhys3DComprehensiveEmbodiedWorldModelEvaluation3D2026"
title: "RoboPhys-3D: A Comprehensive Embodied World Model Evaluation via 3D Reconstruction"
authors: ["Tianyi Wang", "Jiazhou Chen", "Yiming Xu", "Xiangyu Li", "Tianyi Zeng", "Chih-Hsien Chou", "Ning Lu", "Liang Peng", "Junfeng Jiao", "Christian Claudel"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28718"
doi: "10.48550/arXiv.2608.28718"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.ET", "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-01
---

# RoboPhys-3D: A Comprehensive Embodied World Model Evaluation via 3D Reconstruction

> Tianyi Wang, Jiazhou Chen, Yiming Xu, Xiangyu Li, Tianyi Zeng, Chih-Hsien Chou, Ning Lu, Liang Peng, Junfeng Jiao, Christian Claudel · 2026
> [arXiv](https://arxiv.org/abs/2608.28718) · [PDF](https://arxiv.org/pdf/2608.28718)

## Abstract

Video world models increasingly serve as data engines, action planners, and simulators for embodied AI, but conventional embodied world model (EWM) benchmarks lack a unified 3D-grounded protocol for establishing whether generated rollouts preserve the underlying 3D scene state or translate into executable actions. We introduce RoboPhys-3D, a 3D-grounded EWM benchmark built on RoboTwin 2.0, covering 50 manipulation tasks across four regimes, with 5,000 episodes and 25,000 multi-view ground-truth videos. A defining feature of RoboPhys-3D is that generated and ground-truth videos are processed through the same 3D reconstruction pipeline, enabling reconstruction-induced error to be distinguished from generation-induced error. The RoboPhys-3D benchmark organizes 50 complementary metrics into 18 sub-dimensions across four levels: pixel-level fidelity, 3D geometry consistency, state-level understanding, and task-level completeness. We further introduce Average Full Score, a hierarchical score averaging all 50 metrics for comprehensive evaluation, and RoboPhyscore, a compact task-aligned score averaging the metrics most strongly correlated with task success. Among the four representative video world models, Cosmos 3 achieves the highest RoboPhyscore (0.6330, 92.7% of ground truth), while state- and execution-grounded metrics reveal substantial failures that perceptual and vision-language model-based judgments fail to capture. RoboPhyscore further exhibits strong agreement with human evaluation (Pearson r = 0.9761 and Spearman \r{ho} = 0.8962), demonstrating the importance of grounded, execution-aware evaluation for EWM capability.

## TL;DR

Video world models increasingly serve as data engines, action planners, and simulators for embodied AI, but conventional embodied world model (EWM) benchmarks lack a unified 3D-grounded protocol for establishing whether generated rollouts preserve the underlying 3D scene state or translate into executable actions. We introduce RoboPhys-3D, a 3D-grounded EWM benchmark built on RoboTwin 2.0, covering 50 manipulation tasks across four regimes, with 5,000 episodes and 25,000 multi-view ground-truth videos.

## Related
<!-- [[other-paper-citekey]] -->
