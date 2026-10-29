---
citekey: "huCALMCurrentAlignedLinkManipulationSingleArmOversized2026"
title: "CALM: Current Aligned Link Manipulation for Single Arm Oversized Object Lifting"
authors: ["Jun Hu", "Sihan Chen", "Kosta Jovanovic", "David Navarro-Alarcon", "Xueqian Wang", "Jia Pan", "Peng Zhou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.29017"
doi: "10.48550/arXiv.2609.29017"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-26
---

# CALM: Current Aligned Link Manipulation for Single Arm Oversized Object Lifting

> Jun Hu, Sihan Chen, Kosta Jovanovic, David Navarro-Alarcon, Xueqian Wang, Jia Pan, Peng Zhou · 2026
> [arXiv](https://arxiv.org/abs/2609.29017) · [PDF](https://arxiv.org/pdf/2609.29017)

## Abstract

Most robots manipulate objects solely with their end effectors, whereas humans flexibly leverage different body parts, such as the forearm and elbow, especially when handling oversized objects. Learning such whole-arm manipulation is chal-lenging due to long-horizon sparse rewards, limited contact sens-ing, and the sim-to-real gap in contact and actuator dynamics. To address these challenges, we propose Current-Aligned Link Manipulation, a framework for learning long-horizon contact-rich manipulation using motor current as joint load related feedback. Three stage-specific policies first learn repositioning, grasping, and lifting using privileged simulation information, and a stage router sequences them to generate complete task demonstrations. For sim-to-real transfer, a causal current mapper predicts physical motor current from simulated joint histories, aligning the actuator current observation between simulation and hardware. A unified student policy then learns from these demonstrations using only deployable sensor observations and is further refined with DAgger. The task policies are trained entirely in simulation, and the final student is deployed on hardware. Experiments demonstrate 76.2% (762/1000 trials) complete-task success in simulation and 73.3% success (22/30 trials) on the physical robot for sequential oversized-object lifting.

## TL;DR

Most robots manipulate objects solely with their end effectors, whereas humans flexibly leverage different body parts, such as the forearm and elbow, especially when handling oversized objects. Learning such whole-arm manipulation is chal-lenging due to long-horizon sparse rewards, limited contact sens-ing, and the sim-to-real gap in contact and actuator dynamics.

## Related
<!-- [[other-paper-citekey]] -->
