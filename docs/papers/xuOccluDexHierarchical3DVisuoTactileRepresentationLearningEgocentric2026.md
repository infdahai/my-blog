---
citekey: "xuOccluDexHierarchical3DVisuoTactileRepresentationLearningEgocentric2026"
title: "OccluDex: Hierarchical 3D Visuo-Tactile Representation Learning for Egocentric Dexterous Manipulation under Self-Occlusion"
authors: ["Ziheng Xu", "Yueyuan Chen", "Xinyuan He", "Guoxing Liu", "Yuanshuo Tan", "Huiming Pan", "Bin He", "Shuo Jiang", "Peter B. Shull"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.39017"
doi: "10.48550/arXiv.2609.39017"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# OccluDex: Hierarchical 3D Visuo-Tactile Representation Learning for Egocentric Dexterous Manipulation under Self-Occlusion

> Ziheng Xu, Yueyuan Chen, Xinyuan He, Guoxing Liu, Yuanshuo Tan, Huiming Pan, Bin He, Shuo Jiang, Peter B. Shull · 2026
> [arXiv](https://arxiv.org/abs/2609.39017) · [PDF](https://arxiv.org/pdf/2609.39017)

## Abstract

Reliable dexterous manipulation requires continuous estimation of object geometry and hand-object contact throughout interaction. With egocentric sensing, however, the manipulating hand frequently occludes task-relevant object surfaces and contact regions, reducing the visual evidence available for state estimation and thereby making robust closed-loop control and generalization to unseen object geometries particularly challenging. To address this, we present OccluDex, a hierarchical 3D visuo-tactile representation learning framework that integrates global geometric structure with local contact information for robust manipulation under dynamic self-occlusion during hand-object interaction. OccluDex adopts multi-scale masked autoencoding to progressively encode partial 3D geometry and fuses tactile contact tokens with high-level geometric features through cross-modal attention. The encoder is pretrained from synchronized human visuo-tactile demonstrations and transferred as a frozen perceptual backbone for downstream reinforcement learning. We evaluate OccluDex on a faucet rotation task, requiring one full clockwise handle revolution, and a tabletop object reorientation task, requiring a 180-degree tabletop object reorientation without toppling. In simulation experiments, OccluDex demonstrated 12.6% higher accuracy for unseen objects and 8.3% higher accuracy for previously seen objects than the strongest state-of-the-art baseline models. Physical experiments were further performed with a Shadow Hand to demonstrate successful zero-shot sim-to-real generalization on unseen physical objects. This results could enable humanoid egocentric object manipulation for seen and unseen objects even when the manipulating robotic hand occludes vision.

## TL;DR

Reliable dexterous manipulation requires continuous estimation of object geometry and hand-object contact throughout interaction. With egocentric sensing, however, the manipulating hand frequently occludes task-relevant object surfaces and contact regions, reducing the visual evidence available for state estimation and thereby making robust closed-loop control and generalization to unseen object geometries particularly challenging.

## Related
<!-- [[other-paper-citekey]] -->
