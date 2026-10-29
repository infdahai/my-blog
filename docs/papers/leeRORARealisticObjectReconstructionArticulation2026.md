---
citekey: "leeRORARealisticObjectReconstructionArticulation2026"
title: "RORA: Realistic Object Reconstruction with Articulation"
authors: ["Hyesung Lee", "Youngseon Lee", "Kyutae Lee", "Dongjun Lee", "Yongseok Lee"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.04842"
doi: "10.48550/arXiv.2608.04842"
tags: [paper, embodied-ai, "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# RORA: Realistic Object Reconstruction with Articulation

> Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee · 2026
> [arXiv](https://arxiv.org/abs/2608.04842) · [PDF](https://arxiv.org/pdf/2608.04842)

## Abstract

Replicating real-world environments into simulation by realistic visual representation like NeRF and 3D Gaussian Splatting (3DGS) has emerged as an effective strategy to reduce the sim-to-real gap in robot learning. However, implementing object articulation during the real-to-sim process is still a challenging task. Existing motion tracking or learning based articulation methods shows low success rates on complex kinematic structures having multiple joints. Furthermore, those methods require scan of dynamic motion of objects, which makes reconstruction process much complicated. In this work, we propose the first end-to-end pipeline that reconstructs simulation-ready assets with accurate articulation from a single static object video input through suggestion based human-in-the-loop process. Our approach exports a hybrid representation combining 3DGS for photorealistic rendering and mesh-based geometry for physical interaction. In the reconstruction process, our pipeline performs convex decomposition followed by user grouping for intuitive part segmentation, subsequently binding 3D Gaussians to the corresponding mesh parts. An Automatic Joint Suggestion Algorithm then calculates candidate joint axes from local boundary geometries and presents them to users for efficient articulated asset reconstruction. We have shown that our method achieves precise articulation results on partnet-mobility-v0 dataset and real objects. Additionally we presented a potential usage of our framework on robot learning, deploying the reconstructed assets in Unreal Engine and NVIDIA Isaac Sim, demonstrating real-time dexterous hand manipulation tasks.

## TL;DR

Replicating real-world environments into simulation by realistic visual representation like NeRF and 3D Gaussian Splatting (3DGS) has emerged as an effective strategy to reduce the sim-to-real gap in robot learning. However, implementing object articulation during the real-to-sim process is still a challenging task.

## Related
<!-- [[other-paper-citekey]] -->
