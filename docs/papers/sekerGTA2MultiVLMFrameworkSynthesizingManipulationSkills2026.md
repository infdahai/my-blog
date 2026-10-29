---
citekey: "sekerGTA2MultiVLMFrameworkSynthesizingManipulationSkills2026"
title: "GTA-2: A Multi-VLM Framework for Synthesizing Robot Manipulation Skills via Grounded Task Axes"
authors: ["M. Yunus Seker", "Shobhit Aggarwal", "Ruwan Wickramarachchi", "Jonathan Francis", "Oliver Kroemer"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.09808"
doi: "10.48550/arXiv.2609.09808"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# GTA-2: A Multi-VLM Framework for Synthesizing Robot Manipulation Skills via Grounded Task Axes

> M. Yunus Seker, Shobhit Aggarwal, Ruwan Wickramarachchi, Jonathan Francis, Oliver Kroemer · 2026
> [arXiv](https://arxiv.org/abs/2609.09808) · [PDF](https://arxiv.org/pdf/2609.09808)

## Abstract

Robotic manipulation tasks are often decomposed into behaviors or skills. However, one often needs to predefine these behaviors for specific tasks or try to cover a wide range of tasks using generic skills. As a result, these behaviors can remain too coarse to expose the geometric, control, and scene-dependent decisions required for execution. We introduce Grounded Task Axes v2 (GTA-2), a modular multi-VLM framework that constructs executable, task-bespoke manipulation skills from reusable object-centric task-axis components. Rather than predicting actions end-to-end or composing fixed task-level primitives, GTA-2 represents each skill as semantic subtasks comprising task-relevant keypoints and axes, controller compositions, and scene-dependent parameters. Four specialized VLM agents separately decompose the task, construct an abstract task-axis skill, assign controller parameters, and ground the required visual features from RGB-D observations. This abstraction-to-grounding factorization enables zero-shot skill generation without task-specific robot demonstrations, policy training, or fine-tuning. It also keeps intermediate decisions explicit, allowing targeted human feedback to refine an incorrect stage while preserving correct components. We evaluate GTA-2 on 14 real-robot manipulation tasks against a VLA policy pi_{0.5} and two Code-as-Policies baselines using task-axis controllers or conventional robot primitives. GTA-2 achieves an average zero-shot success rate of 73.9%, exceeding the strongest baseline by 31.4 percentage points, while targeted refinement raises GTA-2's average success rate to 90.7%. Project page: https://gta2-project.github.io/

## TL;DR

Robotic manipulation tasks are often decomposed into behaviors or skills. However, one often needs to predefine these behaviors for specific tasks or try to cover a wide range of tasks using generic skills.

## Related
<!-- [[other-paper-citekey]] -->
