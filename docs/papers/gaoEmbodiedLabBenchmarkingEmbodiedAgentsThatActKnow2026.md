---
citekey: "gaoEmbodiedLabBenchmarkingEmbodiedAgentsThatActKnow2026"
title: "EmbodiedLab: Benchmarking Embodied Agents That Act to Know"
authors: ["Hongcheng Gao", "Zelin Zheng", "Alex Zhou", "Jay Zhu", "Shijia Ge", "Yazhe Wang", "Xiping Li", "Jianshu Zeng", "Di Wu", "Xuan Shangguan", "Yexing Wan", "Lingyu He", "Yongli Wang", "Xiaohan Yu", "Zhiqi Jia", "Yue Liu", "Bryan Hooi", "Yinpeng Dong", "Wentao Zhang", "Sihang Wu", "Xiao He"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.35385"
doi: "10.48550/arXiv.2610.35385"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# EmbodiedLab: Benchmarking Embodied Agents That Act to Know

> Hongcheng Gao, Zelin Zheng, Alex Zhou, Jay Zhu, Shijia Ge, Yazhe Wang, Xiping Li, Jianshu Zeng, Di Wu, Xuan Shangguan, Yexing Wan, Lingyu He, Yongli Wang, Xiaohan Yu, Zhiqi Jia, Yue Liu, Bryan Hooi, Yinpeng Dong, Wentao Zhang, Sihang Wu, Xiao He · 2026
> [arXiv](https://arxiv.org/abs/2610.35385) · [PDF](https://arxiv.org/pdf/2610.35385)

## Abstract

Embodied agents are expected to accomplish real-world goals by deciding for themselves how and when to interact with their surroundings. For many such goals, changing the physical state of the world is the means rather than the end: the agent changes the state of a system through interaction, observes the feedback, and explores until it either achieves the goal itself (e.g., discovering physical laws) or learns what the goal requires; it acts to know. Manipulation benchmarks stop at acting to change, with the target state given; scientific discovery benchmarks evaluate knowing but replace physical experimentation with symbolic actions or numerical queries. We introduce EmbodiedLab, a benchmark in which a robot must act to know. Quantitative science experiments make this setting controllable: the parameters of the system are resampled for every instance, so the result cannot be known in advance, yet it can be scored exactly. Across 30 experiments in five disciplines on 14 apparatus platforms, the agent receives an objective and the apparatus, chooses its own procedure, and operates a physics-based simulated laboratory, reading the instruments through its cameras. Evaluation checks what the agent came to know, grounded in readings recorded during the episode, as well as the physical state the task requires; every experiment is verified to be solvable. We evaluate six frontier models in their developers' coding agents with native observation and control, with added perception and motion planning, and with manipulation skills distilled from the strongest agents. With native control, even the strongest agent succeeds less than half the time; for every agent, most failures arise in interacting with the apparatus, and manipulation skills help weaker agents more than perception and planning. The benchmark and its evaluation code are available at https://github.com/HexaFuture/EmbodiedLab.

## TL;DR

Embodied agents are expected to accomplish real-world goals by deciding for themselves how and when to interact with their surroundings. For many such goals, changing the physical state of the world is the means rather than the end: the agent changes the state of a system through interaction, observes the feedback, and explores until it either achieves the goal itself (e.g., discovering physical laws) or learns what the goal requires; it acts to know.

## Related
<!-- [[other-paper-citekey]] -->
