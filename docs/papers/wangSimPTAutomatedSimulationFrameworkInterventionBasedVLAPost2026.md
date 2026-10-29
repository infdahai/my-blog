---
citekey: "wangSimPTAutomatedSimulationFrameworkInterventionBasedVLAPost2026"
title: "SimPT: An Automated Simulation Framework for Intervention-Based VLA Post-Training"
authors: ["Caicheng Wang", "Zipeng Ye", "Zhexuan Zhou", "Zilong Huang", "Xi Zhang", "Yuchen Xie"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29161"
doi: "10.48550/arXiv.2610.29161"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# SimPT: An Automated Simulation Framework for Intervention-Based VLA Post-Training

> Caicheng Wang, Zipeng Ye, Zhexuan Zhou, Zilong Huang, Xi Zhang, Yuchen Xie · 2026
> [arXiv](https://arxiv.org/abs/2610.29161) · [PDF](https://arxiv.org/pdf/2610.29161)

## Abstract

Human-in-the-loop (HIL) post-training improves vision-language-action (VLA) policies through expert corrections, but costly human supervision and repeated real-robot evaluation limit algorithm exploration and development. We introduce SimPT (Simulation-based Post-Training), a simulation framework that automates intervention-based VLA post-training by integrating policy rollouts, corrective data collection, policy training, and standalone evaluation. To automatically determine intervention timing and recovery strategies, we develop an Agent-Compiled Progress Graph that tracks task progress using privileged simulator state and retains stable snapshots during policy execution. After a rollout fails, a CuRobo-based expert attempts recovery from these snapshots, starting at more advanced task stages and falling back to earlier ones as needed to generate corrective trajectories. We implement and compare four post-training methods, RECAP, HG-DAgger, DPO+SFT, and FlowPRO, across seven RoboTwin manipulation tasks. Relative to a fixed-interval snapshot baseline, the Progress Graph reduces recovery attempts by 75.0% and increases recovery success from 93.4% to 98.9%. Using SimPT, we develop RECAP-CF-LPF, a refinement of RECAP that combines cross-fitting and low-pass filtering of value predictions. This refinement increases the overall success rate from 76.50% to 79.36% in held-out simulation trials. In real-robot HIL post-training, it increases the success rate from 72% to 96% across 25 scenarios of an Ethernet cable-insertion task. These results demonstrate the utility of SimPT for exploring and developing VLA post-training algorithms.

## TL;DR

Human-in-the-loop (HIL) post-training improves vision-language-action (VLA) policies through expert corrections, but costly human supervision and repeated real-robot evaluation limit algorithm exploration and development. We introduce SimPT (Simulation-based Post-Training), a simulation framework that automates intervention-based VLA post-training by integrating policy rollouts, corrective data collection, policy training, and standalone evaluation.

## Related
<!-- [[other-paper-citekey]] -->
