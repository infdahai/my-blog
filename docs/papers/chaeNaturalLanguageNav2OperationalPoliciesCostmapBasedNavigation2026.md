---
citekey: "chaeNaturalLanguageNav2OperationalPoliciesCostmapBasedNavigation2026"
title: "Natural-Language to Nav2: Operational Policies for Costmap-Based Navigation"
authors: ["Jiyeong Chae", "Hyunkyo Seo", "Heonjae Lee", "Kyung-Joon Park"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32633"
doi: "10.48550/arXiv.2610.32633"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# Natural-Language to Nav2: Operational Policies for Costmap-Based Navigation

> Jiyeong Chae, Hyunkyo Seo, Heonjae Lee, Kyung-Joon Park · 2026
> [arXiv](https://arxiv.org/abs/2610.32633) · [PDF](https://arxiv.org/pdf/2610.32633)

## Abstract

Autonomous mobile robots support material transport in warehouses and industrial facilities, where navigation must adapt to changing operating conditions. Sensor observations reveal physical obstacles, but do not by themselves specify temporary access rules, route preferences, or exceptions known to operators. This paper presents a natural-language policy interface that brings this knowledge into ROS 2 Nav2. A local large language model converts instructions into JSON policies specifying destinations, spatial constraints, and temporal or event conditions. Deterministic checks govern mission acceptance, and three costmap adapters project accepted policies into the existing navigation stack without changing its planner or controller. On 150 researcher-authored English commands, four local models produce 107-142 correct accepted policies, compared with 44 for a rule-based parser, with 3-20 incorrect acceptances per model. Fault injection records rejection of eight endpoint/JSON faults and 29 validator-stage faults. Navigation experiments use correct task policies to evaluate keepouts, zone costs, person-dependent regions, and event-conditioned passage in simulation and on a TurtleBot3. For Tasks 1-3, mean travel times are 18.4-24.5% lower in simulation and 23.1-35.0% lower on the physical testbed than with the baseline lacking those policies. A native KeepoutFilter comparison and two-robot demonstrations examine basic keepout behavior and shared policy projection. The interface connects operator instructions to explicit navigation policies while retaining Nav2's planning and control components.

## TL;DR

Autonomous mobile robots support material transport in warehouses and industrial facilities, where navigation must adapt to changing operating conditions. Sensor observations reveal physical obstacles, but do not by themselves specify temporary access rules, route preferences, or exceptions known to operators.

## Related
<!-- [[other-paper-citekey]] -->
