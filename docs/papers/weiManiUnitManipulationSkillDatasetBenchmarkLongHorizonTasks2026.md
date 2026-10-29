---
citekey: "weiManiUnitManipulationSkillDatasetBenchmarkLongHorizonTasks2026"
title: "ManiUnit: A Manipulation Skill Dataset and Benchmark for Long-Horizon Tasks"
authors: ["Guoting Wei", "Dawei Yan", "Xia Yuan", "Gengming Zhang", "Yelin He", "Guodong Du", "Jiaquan Ye", "Heng Zhang", "Xinming Wei", "Xianbiao Qi", "Chunxia Zhao", "Haokui Zhang", "Rong Xiao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12089"
doi: "10.48550/arXiv.2610.12089"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# ManiUnit: A Manipulation Skill Dataset and Benchmark for Long-Horizon Tasks

> Guoting Wei, Dawei Yan, Xia Yuan, Gengming Zhang, Yelin He, Guodong Du, Jiaquan Ye, Heng Zhang, Xinming Wei, Xianbiao Qi, Chunxia Zhao, Haokui Zhang, Rong Xiao · 2026
> [arXiv](https://arxiv.org/abs/2610.12089) · [PDF](https://arxiv.org/pdf/2610.12089)

## Abstract

Long-horizon mobile manipulation requires a robot to navigate multi-room environments and execute a sequence of manipulation skills under a single natural language instruction. Learning and evaluating these skills present three challenges: similar observations under a fixed task instruction may make skill selection ambiguous; even when a preceding skill succeeds, the robot state inherited by the next skill may deviate from its demonstrated starting states and affect execution; and task-level metrics hinder skill-specific diagnosis, while early failures leave later skills untested. We therefore introduce ManiUnit, a manipulation skill dataset and benchmark built from 50 BEHAVIOR-1K activities. Its dataset contains 137,899 segments across 21 skill types and 417 subtasks, and its benchmark contains 1,260 test instances. Correspondingly, ManiUnit pairs each segment with an explicit subtask instruction; measures sensitivity to perturbations of the robot's starting base position or joint configuration; and restores intermediate simulator states and defines local success conditions so that each skill can be evaluated without executing preceding stages. Evaluations of representative vision-language-action (VLA) policies show that similar aggregate scores can hide substantial per-skill differences. The tested starting-state perturbations also degrade execution: on the full benchmark, joint perturbations reduce success rates by approximately 56% relative to those from demonstrated starting states. On two long-horizon activities, a skill policy trained on ManiUnit segments achieves 78.7% local manipulation success, compared with 49.3% for a task policy trained on complete demonstrations. The trained skills further support complete-task execution on these activities, as coordinating the task and skill policies through a planner raises full-task success from 4.0% to 18.0%.

## TL;DR

Long-horizon mobile manipulation requires a robot to navigate multi-room environments and execute a sequence of manipulation skills under a single natural language instruction. Learning and evaluating these skills present three challenges: similar observations under a fixed task instruction may make skill selection ambiguous; even when a preceding skill succeeds, the robot state inherited by the next skill may deviate from its demonstrated starting states and affect execution; and task-level metrics hinder skill-specific diagnosis, while early failures leave later skills untested.

## Related
<!-- [[other-paper-citekey]] -->
