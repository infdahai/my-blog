---
citekey: "zhuFastPlanningMultiObjectMultiTargetThrowing2026"
title: "Fast Planning for Multi-object Multi-target Throwing"
authors: ["Zhengming Zhu", "Yang Liu", "Xiao Gao", "Aude Billard"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09224"
doi: "10.48550/arXiv.2610.09224"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-09
---

# Fast Planning for Multi-object Multi-target Throwing

> Zhengming Zhu, Yang Liu, Xiao Gao, Aude Billard · 2026
> [arXiv](https://arxiv.org/abs/2610.09224) · [PDF](https://arxiv.org/pdf/2610.09224)

## Abstract

Robot throwing has emerged as a promising technique for improving efficiency in logistics and warehouse automation, by enlarging the workspace and speeding up the process. To significantly increase the throwing system's throughput, we develop strategies for throwing multiple objects in one swipe. Such multi-object multi-target throwing (MOMT) leverages the large degrees of freedom of anthropomorphic hands. The key is to quickly generate fast and feasible throwing motions, which involves a complex trade-off between short trajectory duration and short planning time. We solve this problem in two stages. Offline, we build a model of the feasible set by combining object's inverted flying dynamics and the robot's kinematics and dynamics. Online, we generate feasible throws through fast solution matching and filtering of object's valid detach state and robot's feasible state that can compose sequences of throws in less than 5 ms. We validate the framework on a 7-DoF manipulator equipped with a multi-fingered hand. In simulation, coordinated two-object throwing reduces execution time by up to 46% compared to independent single-object planning, and this improvement is maintained when scaling to three objects. Real-world experiments with two objects confirm a 29% reduction; the remaining gap to the theoretical 50% is attributed to inter-throw transition overhead. When target positions are randomly changed mid-execution, the system re-plans and successfully reaches the new targets within 100 ms latency without stopping the robot. These results establish the first unified planning framework for MOMT throwing -- demonstrating scalability to multiple objects in simulation and real-world feasibility on two-object tasks -- advancing the frontier of high-throughput robotic manipulation. A video summarizing the method and the hardware experiments is available at https://liuyangdh.github.io/momt-video

## TL;DR

Robot throwing has emerged as a promising technique for improving efficiency in logistics and warehouse automation, by enlarging the workspace and speeding up the process. To significantly increase the throwing system's throughput, we develop strategies for throwing multiple objects in one swipe.

## Related
<!-- [[other-paper-citekey]] -->
