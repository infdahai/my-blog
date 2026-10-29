---
citekey: "liuFleetsNeedContextPlaneRethinkingCooperativePerceptionAutonomous2026"
title: "Fleets Need a Context Plane: Rethinking Cooperative Perception for Autonomous Drones"
authors: ["Liangkai Liu", "Xiaoxiao Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.00659"
doi: "10.48550/arXiv.2609.00659"
tags: [paper, embodied-ai, "cs.DC", "cs.ET", "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Fleets Need a Context Plane: Rethinking Cooperative Perception for Autonomous Drones

> Liangkai Liu, Xiaoxiao Wu · 2026
> [arXiv](https://arxiv.org/abs/2609.00659) · [PDF](https://arxiv.org/pdf/2609.00659)

## Abstract

Cooperative perception allows a drone fleet to combine observations from multiple viewpoints. However, existing systems typically fix their feature-sharing policies at design time or adapt to only one context signal. This is a poor fit for aerial fleets, whose missions, bandwidth, formation geometry, and scene coverage can change during flight. We quantify the cost of context-blind sharing on UAV3D by controlling feature exchange at evaluation time using a released DiscoNet checkpoint, without retraining. Mission-aware sharing matches full-sharing accuracy while using only 5-10% of the bytes. The best tested peer selection policy changes with the byte budget, and choosing the wrong policy loses up to 7.7 AP. Moreover, under a constrained budget, two policies with the same full-scene accuracy differ by 5.9 AP within the mission region, showing that multiple context axes must be considered jointly. We therefore propose the context plane, a bounded, structured interface for runtime context. Each drone publishes a descriptor of at most 1 KB at 10 Hz, and lightweight, replaceable policies use the fleet context to decide what each drone computes, shares, and fuses. Existing sharing schemes become fixed policies within this interface. In our ROS 2 prototype on a Jetson AGX Orin, the context plane uses approximately 0.01% of the data-plane bandwidth, and each policy decision takes 0.10 ms. These results show that an explicit context interface can support low-overhead runtime adaptation without modifying or retraining the perception model.

## TL;DR

Cooperative perception allows a drone fleet to combine observations from multiple viewpoints. However, existing systems typically fix their feature-sharing policies at design time or adapt to only one context signal.

## Related
<!-- [[other-paper-citekey]] -->
