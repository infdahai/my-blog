---
citekey: "yangTrajectoryLevelContinuousActionRepresentationManipulation2026"
title: "Trajectory-Level Continuous Action Representation for Robotic Manipulation"
authors: ["Tong Yang", "Jingkai Jia", "Yuecheng Xu", "Xueyao Chen", "Chi Zhang", "Wenqiang Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.24111"
doi: "10.48550/arXiv.2608.24111"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-26
---

# Trajectory-Level Continuous Action Representation for Robotic Manipulation

> Tong Yang, Jingkai Jia, Yuecheng Xu, Xueyao Chen, Chi Zhang, Wenqiang Zhang · 2026
> [arXiv](https://arxiv.org/abs/2608.24111) · [PDF](https://arxiv.org/pdf/2608.24111)

## Abstract

We propose CAT, a trajectory-level continuous action representation framework for robotic manipulation. Existing visuomotor systems often entangle action representation with control frequency or rely on fixed temporal parameterizations. This leads to representational redundancy at high sampling rates and limits the modeling of critical motion. CAT instead encodes action trajectories within a fixed real-time interval into a set of continuous latent tokens. To ensure temporal consistency across varying control frequencies, we further incorporate a frequency-aware positional encoding that establishs a shared temporal coordinate system. Trajectory-level regularization further stabilizes the latent representation. This approach prevents representation growth with timestep density and avoids reliance on predefined temporal parameterizations. Extensive system-level evaluations on LIBERO, MimicGen, and real-world long-horizon manipulation tasks demonstrate that CAT-based policies consistently outperform both competitive VQ-based and continuous visuomotor baselines under matched training settings. Across various model backbones and control frequencies, CAT consistently improves success rates. These results highlight the advantages of trajectory-level continuous action modeling for scalable robotic manipulation across varying control rates.

## TL;DR

We propose CAT, a trajectory-level continuous action representation framework for robotic manipulation. Existing visuomotor systems often entangle action representation with control frequency or rely on fixed temporal parameterizations.

## Related
<!-- [[other-paper-citekey]] -->
