---
citekey: "kapelyukhTestTimeSpatialReasoningManipulationGenerativeRealSim2026"
title: "Test-Time Spatial Reasoning for Robot Manipulation Using Generative Real-to-Sim"
authors: ["Ivan Kapelyukh", "Yafei Hu", "Ran Gong", "Brandon May", "Tushar Kusnur", "Laura Herlant", "Karl Schmeckpeper", "Edward Johns", "Xiaohan Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33982"
doi: "10.48550/arXiv.2609.33982"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Test-Time Spatial Reasoning for Robot Manipulation Using Generative Real-to-Sim

> Ivan Kapelyukh, Yafei Hu, Ran Gong, Brandon May, Tushar Kusnur, Laura Herlant, Karl Schmeckpeper, Edward Johns, Xiaohan Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.33982) · [PDF](https://arxiv.org/pdf/2609.33982)

## Abstract

Spatial reasoning is fundamental to general robot intelligence, as it enables robots to complete long-horizon tasks involving multi-object interaction. We introduce Simify, a training-free, test-time framework that performs explicit spatial reasoning via massively parallel physics simulation. From a single RGB-D image of a scene, Simify reconstructs simulation-ready assets leveraging 3D generative models and vision-language models. Then given a task specified by a reward function (e.g., build the tallest tower), Simify launches thousands of parallel rollouts in simulation and performs an evolutionary search to optimize object arrangements, typically converging within seconds. We conduct quantitative experiments on real-robot hardware to demonstrate the ability of our framework to execute complex object rearrangement tasks end-to-end with previously unseen objects. Results show that our framework outperforms prior work on foundation models for spatial reasoning by effectively exploiting large-scale parallel simulation during inference, and also highlight the importance of complete and accurate geometry for successful sim-to-real transfer.

## TL;DR

Spatial reasoning is fundamental to general robot intelligence, as it enables robots to complete long-horizon tasks involving multi-object interaction. We introduce Simify, a training-free, test-time framework that performs explicit spatial reasoning via massively parallel physics simulation.

## Related
<!-- [[other-paper-citekey]] -->
