---
citekey: "yamadaOnlineMaterialEstimationConditionedDiffusionPolicyShapingDeformable2026"
title: "Online Material Estimation for Conditioned Diffusion Policy in Shaping Deformable Linear Objects"
authors: ["Ryunosuke Yamada", "Tomohiro Motoda", "Yukiyasu Domae", "Tokuo Tsuji"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12634"
doi: "10.48550/arXiv.2609.12634"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# Online Material Estimation for Conditioned Diffusion Policy in Shaping Deformable Linear Objects

> Ryunosuke Yamada, Tomohiro Motoda, Yukiyasu Domae, Tokuo Tsuji · 2026
> [arXiv](https://arxiv.org/abs/2609.12634) · [PDF](https://arxiv.org/pdf/2609.12634)

## Abstract

Shape control of deformable linear objects (DLOs) is challenging for imitation learning because deformation behavior varies with material properties such as stiffness and elasticity, so a single policy must generate different action sequences for different objects even when the goal shape is identical. We propose a diffusion policy conditioned on material labels that are estimated online during manipulation. A recurrent estimation network predicts the material label of the grasped object from the time series of multi-view images and robot joint states, and the predicted label conditions the diffusion policy at every inference step. We collected 480 real-robot demonstrations covering four DLO materials and three groove-placement tasks, and compared per-material specialist policies, a task-conditioned policy without material labels, a policy conditioned on ground-truth material labels, and the proposed policy. Conditioning on ground-truth material labels improved the average success rate from 45.8% to 60.0% over the task-only policy, and the proposed policy reached 60.8% without any prior material information, matching the policy given ground-truth labels. A post-hoc analysis shows that the estimator extracts material-related information from the manipulation observations and that the diffusion policy responds to the resulting conditioning signal, while the one pronounced failure case is associated with persistent confusion between two similar materials.

## TL;DR

Shape control of deformable linear objects (DLOs) is challenging for imitation learning because deformation behavior varies with material properties such as stiffness and elasticity, so a single policy must generate different action sequences for different objects even when the goal shape is identical. We propose a diffusion policy conditioned on material labels that are estimated online during manipulation.

## Related
<!-- [[other-paper-citekey]] -->
