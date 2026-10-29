---
citekey: "louDexNinjaLearningRobustDexterousCuttingPolicyRealSim2026"
title: "DexNinja: Learning Robust Dexterous Cutting Policy with a Real-to-Sim-to-Real Data Engine"
authors: ["Haozhe Lou", "Runyi Yang", "Wanqi Zhong", "Caiyun Liu", "Yicheng Liu", "Wenhao Liu", "Wenlong Ma", "Jiawei Xia", "Kanzhi Wu", "Danda Pani Paudel", "Luc Van Gool", "Hang Zhao", "Yiming Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.17208"
doi: "10.48550/arXiv.2610.17208"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# DexNinja: Learning Robust Dexterous Cutting Policy with a Real-to-Sim-to-Real Data Engine

> Haozhe Lou, Runyi Yang, Wanqi Zhong, Caiyun Liu, Yicheng Liu, Wenhao Liu, Wenlong Ma, Jiawei Xia, Kanzhi Wu, Danda Pani Paudel, Luc Van Gool, Hang Zhao, Yiming Li · 2026
> [arXiv](https://arxiv.org/abs/2610.17208) · [PDF](https://arxiv.org/pdf/2610.17208)

## Abstract

Cutting a piece of food looks effortless in human hands. For a robot, however, every cut is a high-contact interaction with a deformable, elasto-plastic object whose behavior changes with pose, contact mode, and cutting stage. Collecting real-world data is expensive and wasteful: each trial typically contaminates or damages the food, so obtaining scalable real world data for dexterous cutting is expensive and difficult. Simulation is an appealing alternative, but a large sim-to-real gap exists in both physics and perception. This gap is especially severe for topology-changing interactions like cutting, where small errors in contact, friction, or material and elasticity responses quickly compound. We propose \textsc{DexNinja}, a real2sim2real framework that turns a handful of real demonstrations into a dense and realistic training distribution. \textsc{DexNinja} (i) reconstructs object instances from real captures, (ii) randomizes physically meaningful parameters under category-level constraints, and (iii) produces augmented dexterous manipulation episodes using a custom differentiable simulator that couples robot dynamics, tactile contact, and deformable cutting. We evaluate \textsc{DexNinja} on a dexterous food-slicing task and show that (1) with tens of real demonstrations and hundreds of augmented simulator data, the success rate could reach more than 60\%. (2) the augmented data consistently improves success rates when only using real data with more than 20\% via sim-to-real, and (3) the resulting policies generalize to out-of-distribution objects with varying shapes and sizes.

## TL;DR

Cutting a piece of food looks effortless in human hands. For a robot, however, every cut is a high-contact interaction with a deformable, elasto-plastic object whose behavior changes with pose, contact mode, and cutting stage.

## Related
<!-- [[other-paper-citekey]] -->
