---
citekey: "sautenkovUAVSwarmAgentScalableMultiUAVReconnaissanceTaskAllocation2026"
title: "UAV-SwarmAgent: Scalable Multi-UAV Reconnaissance and Task Allocation via Code Generation and Vision-Language Reasoning"
authors: ["Oleg Sautenkov", "Yasheerah Yaqoot", "Muhammad Ahsan Mustafa", "Grigorii Kalinin", "Chih-Yung Wen", "Dzmitry Tsetserukou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32559"
doi: "10.48550/arXiv.2610.32559"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# UAV-SwarmAgent: Scalable Multi-UAV Reconnaissance and Task Allocation via Code Generation and Vision-Language Reasoning

> Oleg Sautenkov, Yasheerah Yaqoot, Muhammad Ahsan Mustafa, Grigorii Kalinin, Chih-Yung Wen, Dzmitry Tsetserukou · 2026
> [arXiv](https://arxiv.org/abs/2610.32559) · [PDF](https://arxiv.org/pdf/2610.32559)

## Abstract

Supervising a multi-UAV reconnaissance mission usually means plotting waypoints and watching every drone. We present UAV SwarmAgent, a hierarchical multi-agent system in which an operator states the mission in one natural-language sentence and a ground-station agent writes and executes code that turns it into per-UAV routes. The agent grounds inspection targets in an aerial map with a vision-language model, splits them among N UAVs by balancing route length, and dispatches worker agents that verify incidents with a compact onboard decision model. In simulation over 4 incident types and 3 foundation models, the swarm located the incident in 244 of 255 missions (95.7%). A paired scaling study with one to 5 UAVs shows that flight time follows an Amdahl-type law. The second UAV delivers half of the attainable saving and the speedup is bounded at 1.52x. We discuss what this predictability, and the false alarms we observed, imply for an operator who supervises the swarm, and outline the user study needed to test it.

## TL;DR

Supervising a multi-UAV reconnaissance mission usually means plotting waypoints and watching every drone. We present UAV SwarmAgent, a hierarchical multi-agent system in which an operator states the mission in one natural-language sentence and a ground-station agent writes and executes code that turns it into per-UAV routes.

## Related
<!-- [[other-paper-citekey]] -->
