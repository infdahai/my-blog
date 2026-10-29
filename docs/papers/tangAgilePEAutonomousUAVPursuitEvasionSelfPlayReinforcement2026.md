---
citekey: "tangAgilePEAutonomousUAVPursuitEvasionSelfPlayReinforcement2026"
title: "AgilePE: Autonomous UAV Pursuit-Evasion via Self-Play Reinforcement Learning"
authors: ["Wenhao Tang", "Tianyang Chen", "Zhejun Cui", "Boyuan An", "Jiayu Chen", "Ruize Zhang", "Huidong Liu", "Tianyue Wu", "Qingmin Liao", "Fei Gao", "Yu Wang", "Chao Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.14135"
doi: "10.48550/arXiv.2608.14135"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# AgilePE: Autonomous UAV Pursuit-Evasion via Self-Play Reinforcement Learning

> Wenhao Tang, Tianyang Chen, Zhejun Cui, Boyuan An, Jiayu Chen, Ruize Zhang, Huidong Liu, Tianyue Wu, Qingmin Liao, Fei Gao, Yu Wang, Chao Yu · 2026
> [arXiv](https://arxiv.org/abs/2608.14135) · [PDF](https://arxiv.org/pdf/2608.14135)

## Abstract

Autonomous pursuit-evasion is a fundamental challenge for Unmanned Aerial Vehicles (UAVs), requiring rapid decision-making under tightly coupled dynamics and continuously changing opponent behaviors. Traditional rule-based or differential-game approaches often struggle with high-dimensional aerial interactions and agile maneuvering. We present AgilePE, a complete system for autonomous UAV pursuit-evasion via self-play reinforcement learning. AgilePE integrates agile low-level control, competitive policy optimization, and sim-to-real deployment in a unified framework. The policy directly maps onboard state observations to Collective Thrust and Body Rates (CTBR) commands, enabling end-to-end agile maneuvering without intermediate trajectory planners or waypoint controllers. For training, we use competitive self-play with Prioritized Fictitious Self-Play (PFSP) and a diversified opponent pool, enabling agents to improve against historical policies while stabilizing optimization and reducing policy oscillation. This process leads to the emergence of sophisticated pursuit and evasion strategies. For real-world deployment, we develop a hardware-aligned simulation pipeline that models actuator-response dynamics, communication latency, and domain randomization. The learned policies transfer zero-shot to real quadrotors without task-specific tuning. Real-world experiments reproduce pursuit-evasion tactics observed in simulation, including rapid dodging and flanking, and demonstrate interactive two-agent zero-shot deployment.

## TL;DR

Autonomous pursuit-evasion is a fundamental challenge for Unmanned Aerial Vehicles (UAVs), requiring rapid decision-making under tightly coupled dynamics and continuously changing opponent behaviors. Traditional rule-based or differential-game approaches often struggle with high-dimensional aerial interactions and agile maneuvering.

## Related
<!-- [[other-paper-citekey]] -->
