---
citekey: "johnsonALFREDRequirementDrivenDevelopmentOpenSourceMobileManipulator2026"
title: "ALFRED: Requirement-driven development of an open-source mobile manipulator for long-term plant monitoring"
authors: ["Ciar\\'an Miceal Johnson", "Christopher Quail", "Garry Ellard", "Alistair McConnell", "Steve Tonneau", "Fernando Auat Cheein"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01477"
doi: "10.48550/arXiv.2610.01477"
tags: [paper, embodied-ai, "cs.AR", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# ALFRED: Requirement-driven development of an open-source mobile manipulator for long-term plant monitoring

> Ciar\'an Miceal Johnson, Christopher Quail, Garry Ellard, Alistair McConnell, Steve Tonneau, Fernando Auat Cheein · 2026
> [arXiv](https://arxiv.org/abs/2610.01477) · [PDF](https://arxiv.org/pdf/2610.01477)

## Abstract

Tracking seasonal change in crops and forests requires observing the same plants repeatedly. Ground robots can do this at close range, and a manipulator gives their sensors more viewpoints. Yet the robots behind long-term field datasets are rarely released with their design files, and how a robot's own structure limits arm reach and occludes its sensors is seldom compared between builds. We present ALFRED, an open-source mobile manipulator built from commercially available components. It carries a six-degree-of-freedom arm, LiDAR, RGB-D cameras, RTK GNSS and an IMU on an Ackermann-steered base, all mounted on a reconfigurable aluminium strut frame, and runs containerised ROS software. It was developed through four builds against six requirements for repeated outdoor deployment: durability, modularity, repairability, sensing reach, endurance and reproducibility. Model-based analysis of the last three builds shows the usable share of the arm's reachable poses rising from 34.0% to 60.0% and then 66.1%, and ray casting shows that only the final build keeps the frame-mounted LiDAR's horizontal view clear both forwards and backwards. ALFRED completed a year of monthly forest surveys (528 traversals) without missing a scheduled collection. This was despite battery degradation, reconfiguration for another researcher's study, and the parallel development of ALFRED 2.0 for autonomous crop-row operation, with each switch between builds taking about six hours. The deployment also showed that mechanical modularity is only as dependable as the robot description that tracks it.

## TL;DR

Tracking seasonal change in crops and forests requires observing the same plants repeatedly. Ground robots can do this at close range, and a manipulator gives their sensors more viewpoints.

## Related
<!-- [[other-paper-citekey]] -->
