---
citekey: "zouFunctionBeyondFormFunctionalCorrespondenceCrossEmbodimentDexterous2026"
title: "Function beyond Form: Functional Correspondence for Cross-Embodiment Dexterous Grasp Generation"
authors: ["Bolin Zou", "Wenlong Dong", "Mu Ai", "Chao Tang", "Aoxiang Gu", "Lipeng Chen", "Hong Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.39006"
doi: "10.48550/arXiv.2609.39006"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Function beyond Form: Functional Correspondence for Cross-Embodiment Dexterous Grasp Generation

> Bolin Zou, Wenlong Dong, Mu Ai, Chao Tang, Aoxiang Gu, Lipeng Chen, Hong Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.39006) · [PDF](https://arxiv.org/pdf/2609.39006)

## Abstract

Cross-embodiment dexterous grasp generation remains challenging because robotic hands differ substantially in geometry, topology, and kinematics. Existing approaches often lack explicit correspondences between structurally different hand regions that play similar functional roles in a grasp, a concept we refer to as functional correspondence. Consequently, their models tend to learn hand-specific interaction patterns rather than transferable grasp knowledge, limiting generalization to unseen hands. To address this limitation, we introduce FunCo-Grasp, which establishes functional correspondences across heterogeneous hand embodiments. Specifically, Functional Part Alignment aligns each hand to a canonical functional schema by mapping physical links to shared functional parts according to their grasping roles, while Canonical Frame Alignment expresses these parts in canonical local frames. These two alignments provide a consistent representation for inter-part and hand-object interactions, allowing the model to learn transferable grasp knowledge across hands. Conditioned on the aligned hand representation and object geometry, a diffusion model generates the target spatial arrangement of the functional parts, which are then converted into an executable joint configuration. Adapting FunCo-Grasp to an unseen hand requires only its geometric and kinematic models and a one-time lightweight functional annotation, without target-hand grasp data, fine-tuning, or learned retargeting. In simulation on held-out objects from the filtered CMapDataset, we achieves average success rates of 92.40% on three seen hands and 74.02% on four unseen hands. In real-world experiments, the same model achieves an overall success rate of 76.00% on two unseen hands without additional training or fine-tuning. These results demonstrate the effectiveness of FunCo-Grasp in transferring grasp knowledge to unseen hands.

## TL;DR

Cross-embodiment dexterous grasp generation remains challenging because robotic hands differ substantially in geometry, topology, and kinematics. Existing approaches often lack explicit correspondences between structurally different hand regions that play similar functional roles in a grasp, a concept we refer to as functional correspondence.

## Related
<!-- [[other-paper-citekey]] -->
