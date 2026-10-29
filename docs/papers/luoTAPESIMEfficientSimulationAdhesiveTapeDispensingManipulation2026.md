---
citekey: "luoTAPESIMEfficientSimulationAdhesiveTapeDispensingManipulation2026"
title: "TAPESIM: Efficient Simulation of Adhesive Tape Dispensing for Robotic Manipulation"
authors: ["Zhaofeng Luo", "Xinyu Lu", "jaehoon Choi", "Zhehuan Chen", "Trinity Chung", "Xiaowen Qiu", "Hugh Nicholas Perkins", "Gianna Calderon", "Alexis Duburcq", "Sanghyun Son", "Tsun-Hsuan Wang", "Yi-Ling Qiao", "Minchen Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28766"
doi: "10.48550/arXiv.2609.28766"
tags: [paper, embodied-ai, "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# TAPESIM: Efficient Simulation of Adhesive Tape Dispensing for Robotic Manipulation

> Zhaofeng Luo, Xinyu Lu, jaehoon Choi, Zhehuan Chen, Trinity Chung, Xiaowen Qiu, Hugh Nicholas Perkins, Gianna Calderon, Alexis Duburcq, Sanghyun Son, Tsun-Hsuan Wang, Yi-Ling Qiao, Minchen Li · 2026
> [arXiv](https://arxiv.org/abs/2609.28766) · [PDF](https://arxiv.org/pdf/2609.28766)

## Abstract

Applying adhesive tape to secure wire harnesses or seal packages requires robots to coordinate a flexible strip, a moving roll, and surfaces that attach and detach. Simulation could make these interactions repeatable for robot development and evaluation, but resolving every adhesive layer is expensive and can suppress roll motion at practical solver tolerances, while a permanently rigid roll cannot release material. We present TapeSim, a tape simulator that concentrates deformation near the unwinding region and along the released strip. We will release the source code. A rigid cluster represents most wound material, while an advancing deformable collar enables payout and leaves released tape flexible and reattachable. Optional releasable bonds simplify adhesive interfaces and reduce mean step times for smaller rolls. Controlled swing tests show improved roll rotation. At 32 turns, clustering gives 3.2-3.4x mean physics-step speedups at a fixed Newton tolerance and 4.5-8.4x for comparable roll motion. Across five real-motion Stick replays, the clustered variants reduce mean image-plane core-landmark error by 23-29% relative to the full-shell cohesive baseline. On 100 paired Peel cases, they improve balanced accuracy from 50% to 72.9-76.3%, with interface rankings varying across tasks. A teleoperated box-sealing sequence demonstrates attachment, dispensing, cutting, and sealing in a continuous workflow.

## TL;DR

Applying adhesive tape to secure wire harnesses or seal packages requires robots to coordinate a flexible strip, a moving roll, and surfaces that attach and detach. Simulation could make these interactions repeatable for robot development and evaluation, but resolving every adhesive layer is expensive and can suppress roll motion at practical solver tolerances, while a permanently rigid roll cannot release material.

## Related
<!-- [[other-paper-citekey]] -->
