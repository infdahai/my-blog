---
citekey: "tengCableVLASimulationPrivilegedGlobalLocalRepresentationLearningCable2026"
title: "CableVLA: Simulation-Privileged Global-Local Representation Learning for Cable Routing"
authors: ["Zhifei Teng", "Bo Feng", "Xiang Zou", "Jinpeng Xiao", "Min Li", "Zhouping Yin", "Yiqun Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25606"
doi: "10.48550/arXiv.2609.25606"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# CableVLA: Simulation-Privileged Global-Local Representation Learning for Cable Routing

> Zhifei Teng, Bo Feng, Xiang Zou, Jinpeng Xiao, Min Li, Zhouping Yin, Yiqun Li · 2026
> [arXiv](https://arxiv.org/abs/2609.25606) · [PDF](https://arxiv.org/pdf/2609.25606)

## Abstract

Cable routing requires coordinated control of global cable topology and changing local contacts. We present CableVLA, an end-to-end multimodal vision-language-action framework that converts simulation-privileged supervision into deployable cable-topology and tactile representations. TopoHead distills node-level physics and current and future cable-topology information into causal visual context for the action expert. TacSense uses complementary frame and taxel branches to learn contact dynamics from resistive arrays, with simulator-derived kinematics and contact events providing supervision beyond the measured force map. A contact gate activates force-tactile residuals that refine the next 8 arm-and-gripper actions of a frozen topology-conditioned policy. Across 345 MuJoCo evaluations, CableVLA improves success from 62.6% for the $π_{0.5}$-V visual baseline to 84.9%. TacSense achieves pronounced gains in slip-transition recognition over a CNN-LSTM baseline with a similar parameter count, and this advantage persists under frozen-encoder probes. Topology prediction and 57-task tactile evaluations assess representation quality, while policy adaptation studies evaluate downstream control performance. Cross-simulator and real-robot comparisons further examine zero-shot policy transfer under changes in dynamics and sensing.

## TL;DR

Cable routing requires coordinated control of global cable topology and changing local contacts. We present CableVLA, an end-to-end multimodal vision-language-action framework that converts simulation-privileged supervision into deployable cable-topology and tactile representations.

## Related
<!-- [[other-paper-citekey]] -->
