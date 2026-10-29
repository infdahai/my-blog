---
citekey: "dingCQDCWarpGPUAcceleratedDifferentiableQuasiDynamicSimulation2026"
title: "CQDC-Warp: GPU-Accelerated Differentiable Quasi-Dynamic Simulation for Contact-Rich Manipulation"
authors: ["Yanchen Ding", "Jiayi Chen", "Jianfeng Xu", "Wei Zhao", "Li Yi", "He Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.21349"
doi: "10.48550/arXiv.2610.21349"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# CQDC-Warp: GPU-Accelerated Differentiable Quasi-Dynamic Simulation for Contact-Rich Manipulation

> Yanchen Ding, Jiayi Chen, Jianfeng Xu, Wei Zhao, Li Yi, He Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.21349) · [PDF](https://arxiv.org/pdf/2610.21349)

## Abstract

Efficient synthesis of contact-rich manipulation trajectories is essential for downstream robot learning. Gradient-based planning offers a promising approach, but jointly optimizing motion and contact decisions remains challenging. Meanwhile, many existing planners run on CPUs with limited throughput. We present CQDC-Warp, a GPU-accelerated differentiable quasi-dynamic simulator for batched model predictive control (MPC). We use it to study contact-guided trajectory optimization, in which intended robot--object contacts are specified before planning and encouraged through soft costs, while the simulated dynamics determine contact geometry and frictional response without a prescribed contact-mode schedule. Across $17{,}408$ trials on the $17$-object Allegro in-hand rotation benchmark, our framework achieves $79.8\%$ success, compared with $73.7\%$ for CFree and $65.2\%$ for IMPACT, and reduces mean trajectory-generation time by factors of $27.0$ and $50.2$, respectively. On a single NVIDIA RTX 4090 with $2{,}048$ parallel worlds, forward and backward throughput reach $2.06\times10^5$ and $2.25\times10^5$ world-steps per second, respectively. Further experiments cover manipulation with LEAP and Shadow hands, environmental contact exploitation, bimanual manipulation, whole-body control, and real-world trajectory replay on a Sharpa hand.

## TL;DR

Efficient synthesis of contact-rich manipulation trajectories is essential for downstream robot learning. Gradient-based planning offers a promising approach, but jointly optimizing motion and contact decisions remains challenging.

## Related
<!-- [[other-paper-citekey]] -->
