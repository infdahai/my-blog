---
citekey: "wuDEXTERASingleImageDeployableDexterousManipulationRealSim2026"
title: "DEXTERA: From a Single Image to Deployable Dexterous Manipulation via Real-to-Sim-to-Real"
authors: ["Jin Wu", "Lianjie Yuan", "Zeyan Sun", "Yuanyuan Lei", "Disi A", "Bicheng Han", "Fangzhou Xia"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21045"
doi: "10.48550/arXiv.2609.21045"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# DEXTERA: From a Single Image to Deployable Dexterous Manipulation via Real-to-Sim-to-Real

> Jin Wu, Lianjie Yuan, Zeyan Sun, Yuanyuan Lei, Disi A, Bicheng Han, Fangzhou Xia · 2026
> [arXiv](https://arxiv.org/abs/2609.21045) · [PDF](https://arxiv.org/pdf/2609.21045)

## Abstract

Collecting real-world robot data for dexterous manipulation is costly and time-consuming. While high-fidelity physics simulators enable scalable data synthesis and policy learning, constructing deployment-ready digital twins manually remains labor-intensive, and residual visual, geometric, and dynamics gaps hinder reliable sim-to-real transfer. We present DEXTERA, an automated real-to-sim-to-real framework that transforms a single RGB image into deployable policies for dexterous manipulation across four unified stages: (1) single-image scene factorization into a static Gaussian background and interactive rigid or articulated assets with VLM-inferred physical parameters; (2) metric scene global alignment, object canonicalization, and morphology-balanced robot calibration; (3) scalable simulator task primitive construction, VR teleoperation, and object-centric trajectory synthesis; and (4) a shared multimodal policy interface supporting both imitation learning and reinforcement learning. We evaluate DEXTERA across 13 task-embodiment pairs, 2 dexterous robot platforms, and 6 policy architectures. Experimental results demonstrate that DEXTERA achieves superior visual fidelity and 3D geometric reconstruction compared to generative baselines, while cross-domain trajectory replays validate strong physical interaction consistency. Furthermore, simulation-only trained policies enable viable zero-shot real-robot deployment, while simulation-real co-training substantially improves mean physical policy success from 29.2% to 61.9% across diverse policy architectures.

## TL;DR

Collecting real-world robot data for dexterous manipulation is costly and time-consuming. While high-fidelity physics simulators enable scalable data synthesis and policy learning, constructing deployment-ready digital twins manually remains labor-intensive, and residual visual, geometric, and dynamics gaps hinder reliable sim-to-real transfer.

## Related
<!-- [[other-paper-citekey]] -->
