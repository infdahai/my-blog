---
citekey: "liuScene2DemoSelfEvolvingEmbodiedDataGenerationObjectAction2026"
title: "Scene2Demo: Self-Evolving Embodied Data Generation via Object-Action Graph"
authors: ["Xiang Liu", "Sen Cui", "Guocai Yao", "Zhong Cao", "Jingheng Ma", "Min Zhang", "Changshui Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2602.12065"
doi: "10.48550/arXiv.2602.12065"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Scene2Demo: Self-Evolving Embodied Data Generation via Object-Action Graph

> Xiang Liu, Sen Cui, Guocai Yao, Zhong Cao, Jingheng Ma, Min Zhang, Changshui Zhang · 2026
> [arXiv](https://arxiv.org/abs/2602.12065) · [PDF](https://arxiv.org/pdf/2602.12065)

## Abstract

We present Scene2Demo, a self-evolving framework for offline embodied data generation. Given a single real-world RGB image and a user query, Scene2Demo constructs an interactive simulated scene and generates executable task configurations, multi-view execution videos, and offline robot-learning datasets. Scene2Demo uses a structured multi-module workflow via an object-action graph, representing task generation through object-centric configurations and action transitions. Failed or incomplete executions are further refined by feedback agents that inspect visual rollouts and revise action flows through sequence modification or parameter adjustment. Across 102 automatically generated primitive scene-task pairs, Scene2Demo achieves a 71.6\% execution success rate; on four representative long-horizon tasks, self-evolution improves both task success and subtask-level execution quality over primitive-only execution, and comparisons with RoboGen and GenSim2 show stronger task planning and execution performance under automated data-generation settings. Finally, behavior cloning policies achieve 96.0\% and 92.0\% success on two representative tasks, validating that the generated data can support downstream policy learning. Our project page is available at https://scene2demo-anon.github.io/ .

## TL;DR

We present Scene2Demo, a self-evolving framework for offline embodied data generation. Given a single real-world RGB image and a user query, Scene2Demo constructs an interactive simulated scene and generates executable task configurations, multi-view execution videos, and offline robot-learning datasets.

## Related
<!-- [[other-paper-citekey]] -->
