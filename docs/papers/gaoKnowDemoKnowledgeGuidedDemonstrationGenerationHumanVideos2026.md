---
citekey: "gaoKnowDemoKnowledgeGuidedDemonstrationGenerationHumanVideos2026"
title: "KnowDemo: Knowledge-Guided Robot Demonstration Generation from Human Videos"
authors: ["Zhiyuan Gao", "Yanxiang Zhan", "Mohammad Khoshnazar", "Jeroen Schäfer", "Michael Beetz"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21229"
doi: "10.48550/arXiv.2609.21229"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# KnowDemo: Knowledge-Guided Robot Demonstration Generation from Human Videos

> Zhiyuan Gao, Yanxiang Zhan, Mohammad Khoshnazar, Jeroen Schäfer, Michael Beetz · 2026
> [arXiv](https://arxiv.org/abs/2609.21229) · [PDF](https://arxiv.org/pdf/2609.21229)

## Abstract

Learning robot manipulation policies typically requires substantial demonstration data, which are costly to collect on real robots. Recent methods generate robot demonstrations from human videos by adapting recovered motion and validating the resulting trajectories in simulation. However, methods centered on motion-reference adaptation can limit behavioral diversity by retaining the demonstrated contact strategies and subtask orders, while insufficient understanding of task requirements and scene relations can reduce demonstration generation efficiency by generating invalid candidates. To address these limitations, we propose KnowDemo, a framework that uses structured manipulation knowledge from human videos to generate diverse robot demonstrations for a target workspace. To distinguish task requirements from demonstration-specific choices, we develop a knowledge extraction and reasoning module based on a vision-language model (VLM) that associates object and action descriptions with inferred task conditions, demonstration references, and permissible execution variations. To translate this knowledge into executable demonstrations, we resolve the descriptions against target-scene entities and geometry to guide candidate generation and screening before motion planning and simulation. The resulting demonstrations exhibit multimodal behavior through alternative contact strategies and valid subtask orders, with structured execution labels. Experiments demonstrate additional verified execution modes beyond a reference-only configuration and improved candidate planning success through task-guided grasp sampling. To validate the generated data for policy learning, we fine-tune the pretrained $π_{0.5}$ model on simulation data, achieving sim-to-real transfer across three tasks. Project page: https://zhiyuan-gao.github.io/knowdemo/

## TL;DR

Learning robot manipulation policies typically requires substantial demonstration data, which are costly to collect on real robots. Recent methods generate robot demonstrations from human videos by adapting recovered motion and validating the resulting trajectories in simulation.

## Related
<!-- [[other-paper-citekey]] -->
