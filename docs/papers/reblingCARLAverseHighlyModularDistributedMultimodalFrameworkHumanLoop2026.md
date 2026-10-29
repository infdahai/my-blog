---
citekey: "reblingCARLAverseHighlyModularDistributedMultimodalFrameworkHumanLoop2026"
title: "CARLAverse: A Highly Modular, Distributed, and Multimodal Framework for Human-in-the-Loop Simulation"
authors: ["Patrick Rebling", "Philipp Nenninger", "Reiner Kriesten"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11478"
doi: "10.48550/arXiv.2609.11478"
tags: [paper, embodied-ai, "cs.HC", "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# CARLAverse: A Highly Modular, Distributed, and Multimodal Framework for Human-in-the-Loop Simulation

> Patrick Rebling, Philipp Nenninger, Reiner Kriesten · 2026
> [arXiv](https://arxiv.org/abs/2609.11478) · [PDF](https://arxiv.org/pdf/2609.11478)

## Abstract

The development of autonomous driving demands comprehensive testing in mixed-traffic scenarios involving vulnerable road users (VRUs), where purely artificial agents often fail to capture authentic human social negotiations. While human-in-the-loop (HITL) simulators enable safe investigation of these interactions, existing multi-agent platforms struggle with the network latency and synchronization constraints required for high-fidelity haptic feedback. To resolve this, we present CARLAverse, an open-source, multimodal simulation ecosystem. Extending modular hardware abstraction, CARLAverse integrates driving (DrivoCARLA), cycling (CycloCARLA), and pedestrian (WalkoCARLA) simulators into a shared virtual environment. Its core methodological contribution is a distributed physics architecture: latency-critical ego dynamics and high-frequency force feedback are computed locally on client nodes, while a central CARLA server orchestrates non-player character (NPC) physics and global traffic. By decoupling haptic control loops from network bottlenecks, CARLAverse enables scalable, cross-institutional HITL experiments without compromising physical immersion. Code and documentation: https://git.ieem-ka.de/simulator-environments/carlaverse

## TL;DR

The development of autonomous driving demands comprehensive testing in mixed-traffic scenarios involving vulnerable road users (VRUs), where purely artificial agents often fail to capture authentic human social negotiations. While human-in-the-loop (HITL) simulators enable safe investigation of these interactions, existing multi-agent platforms struggle with the network latency and synchronization constraints required for high-fidelity haptic feedback.

## Related
<!-- [[other-paper-citekey]] -->
