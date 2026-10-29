---
citekey: "maBehaviorSkillFineGrainedBenchmarkEvaluatingVisionLanguage2026"
title: "Behavior-Skill: A Fine-Grained Benchmark for Evaluating Vision-Language-Action Policies in Long-Horizon Tasks"
authors: ["Chunyun Ma", "Lun Luo", "Xingjian Luo", "Xiexing Feng", "Hang Zhang", "Wei Liu", "Feng Qiao", "Yaonan Wang", "Huimin Lu", "Xieyuanli Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30536"
doi: "10.48550/arXiv.2608.30536"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Behavior-Skill: A Fine-Grained Benchmark for Evaluating Vision-Language-Action Policies in Long-Horizon Tasks

> Chunyun Ma, Lun Luo, Xingjian Luo, Xiexing Feng, Hang Zhang, Wei Liu, Feng Qiao, Yaonan Wang, Huimin Lu, Xieyuanli Chen · 2026
> [arXiv](https://arxiv.org/abs/2608.30536) · [PDF](https://arxiv.org/pdf/2608.30536)

## Abstract

Reliable execution of long-horizon mobile manipulation tasks remains challenging because overall task success depends on the successful completion of multiple constituent skills. Existing benchmarks, however, still rely primarily on full-task rollouts and aggregate task-level metrics, making intermediate failures difficult to observe and analyze. We present Behavior-Skill, a benchmark that reformulates the learning and evaluation of long-horizon tasks around executable constituent skills. It contains 235,492 skill instances from 10,000 demonstrations across 50 household tasks and 34 semantic skill categories. Each instance pairs a skill instruction with an aligned observation-action segment, and is further associated with a restorable intermediate state and a skill success condition to enable independent evaluation under valid preconditions. We further introduce trajectory-level and skill-level metrics to characterize policy capability beyond aggregate task success. Extensive experiments across representative VLA policies including pi0.5 and GR00T on the complete 50-task benchmark show that failures are highly non-uniform across skills, with contact-rich manipulation skills forming persistent bottlenecks. These results demonstrate that Behavior-Skill complements full-task evaluation by exposing intermediate capability profiles for analyzing and improving long-horizon VLA policies. Behavior-Skill is publicly available at https://github.com/nubot-nudt/Behavior-Skill.

## TL;DR

Reliable execution of long-horizon mobile manipulation tasks remains challenging because overall task success depends on the successful completion of multiple constituent skills. Existing benchmarks, however, still rely primarily on full-task rollouts and aggregate task-level metrics, making intermediate failures difficult to observe and analyze.

## Related
<!-- [[other-paper-citekey]] -->
