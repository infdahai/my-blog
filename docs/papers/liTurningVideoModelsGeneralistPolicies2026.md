---
citekey: "liTurningVideoModelsGeneralistPolicies2026"
title: "Turning Video Models into Generalist Robot Policies"
authors: ["Sizhe Lester Li", "Evan Kim", "Xingjian Bai", "Tong Zhao", "Tao Pang", "Max Simchowitz", "Vincent Sitzmann"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2605.27817"
doi: "10.48550/arXiv.2605.27817"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Turning Video Models into Generalist Robot Policies

> Sizhe Lester Li, Evan Kim, Xingjian Bai, Tong Zhao, Tao Pang, Max Simchowitz, Vincent Sitzmann · 2026
> [arXiv](https://arxiv.org/abs/2605.27817) · [PDF](https://arxiv.org/pdf/2605.27817)

## Abstract

Video generative models have emerged as a promising robotics backbone, capable of generating videos that depict the completion of complex tasks across embodiments and environments. Recent work proposes robot foundation models that jointly predict future observations and actions by finetuning video models with action-labeled data. In this paper, we test the limits of an alternative approach: leave the video planner as-is while training an embodiment-specific inverse dynamics model (IDM). This decoupling offers several natural benefits: the video planner remains embodiment-agnostic, different video models can be interchanged easily without re-training the IDM, and the IDM can be independently trained with readily available self-play data. We present a closed-loop, video-to-action policy that combines an action-free video world model with a carefully-designed IDM based on the robot embodiment Jacobian. We demonstrate that our IDM design is both data-efficient and scalable to high-dimensional action spaces. Our policy, which we coin the Video-to-Embodied Robot Action Model (VERA), achieves strong performance across simulated and real-world benchmarks, including zero-shot Panda arm manipulation and 16-DoF Allegro-hand dexterous cube re-orientation. The same video planner can be used across multiple embodiments by pairing it with different embodiment-specific IDMs. Our results show that decoupled video planning plus faithful video-to-action translation is a viable alternative route towards zero-shot, cross-embodiment, and generalizable robot control. More results are available on our project website: https://vera.csail.mit.edu.

## TL;DR

Video generative models have emerged as a promising robotics backbone, capable of generating videos that depict the completion of complex tasks across embodiments and environments. Recent work proposes robot foundation models that jointly predict future observations and actions by finetuning video models with action-labeled data.

## Related
<!-- [[other-paper-citekey]] -->
