---
citekey: "zhuTUCOCuratingSimulationDemonstrationsSimRealPolicyCo2026"
title: "TUCO: Curating Simulation Demonstrations for Sim-to-Real Robot Policy Co-Training"
authors: ["Ning Zhu", "Mengfei Zhao", "Yikai Tang", "Zhangyujie Sun", "Peihao Li", "Dongyue Ni", "Jindou Jia", "Jianfei Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05407"
doi: "10.48550/arXiv.2610.05407"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# TUCO: Curating Simulation Demonstrations for Sim-to-Real Robot Policy Co-Training

> Ning Zhu, Mengfei Zhao, Yikai Tang, Zhangyujie Sun, Peihao Li, Dongyue Ni, Jindou Jia, Jianfei Yang · 2026
> [arXiv](https://arxiv.org/abs/2610.05407) · [PDF](https://arxiv.org/pdf/2610.05407)

## Abstract

Simulation demonstrations can supplement scarce real-world data for robot policy co-training. However, the value of using data curation to actively select these demonstrations for sim-to-real co-training remains underexplored. Existing curation methods also lack a unified criterion for measuring trajectory-level utility and set-level coverage from closed-loop target behavior. To address these gaps, we present the first systematic study of data curation for sim-to-real robot policy co-training and propose Trajectory-level Utility and set-level Coverage Optimization (TUCO). TUCO uses influence functions to trace how each source demonstration affects target-domain scoring rollouts. Our key insight is that these effects can be decomposed into an overall contribution to target return and variation across rollouts, providing a common closed-loop basis for measuring trajectory utility and set coverage. We further propose a performance-aligned subset optimizer that combines these measures in a unified curation objective to reduce redundancy and select complementary demonstrations. Extensive experiments on RoboMimic and OmniReset establish the value of active simulation data curation for sim-to-real policy co-training and show that TUCO achieves state-of-the-art performance across single-simulator, sim-to-sim, and sim-to-real settings.

## TL;DR

Simulation demonstrations can supplement scarce real-world data for robot policy co-training. However, the value of using data curation to actively select these demonstrations for sim-to-real co-training remains underexplored.

## Related
<!-- [[other-paper-citekey]] -->
