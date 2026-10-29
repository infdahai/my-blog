---
citekey: "sahooTANDEMTaskMotionPlanningNeededDemonstrationsEfficientVision2026"
title: "TANDEM: Task and Motion Planning with As-Needed Demonstrations for Efficient Vision-Language-Action Model Fine-tuning"
authors: ["Samrat Sahoo", "Liang Ji", "Tom Silver", "Yixuan Huang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28314"
doi: "10.48550/arXiv.2609.28314"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# TANDEM: Task and Motion Planning with As-Needed Demonstrations for Efficient Vision-Language-Action Model Fine-tuning

> Samrat Sahoo, Liang Ji, Tom Silver, Yixuan Huang · 2026
> [arXiv](https://arxiv.org/abs/2609.28314) · [PDF](https://arxiv.org/pdf/2609.28314)

## Abstract

Human teleoperators spend substantial time demonstrating behaviors that robots can already perform autonomously, limiting the scalability of data collection for robot foundation models. Task and motion planning (TAMP) can automate many of these behaviors, but a fixed planning domain may not support every stage of a long-horizon manipulation task. We present TANDEM (Tamp with As-Needed Demonstrations for Efficient Model fine-tuning), a system that combines TAMP with selective human teleoperation to collect demonstrations for tasks beyond the planner's capabilities. Our key idea is to represent human assistance as an on-demand planning capability. Given a language instruction and visual observation, TANDEM uses pretrained vision-language models to extend the planning domain with missing predicates and human-executed magic operators. This allows the planner to interleave autonomous and human-executed stages without task-specific intervention points. After each human stage, TANDEM re-perceives the scene and checks whether the intended effects hold before resuming autonomous planning. To support fine-tuning vision-language-action (VLA) models, TANDEM also uses example pretraining trajectories to align planner-generated motions with the target model's pretraining distribution. We evaluate TANDEM on five long-horizon manipulation tasks beyond the TAMP domain's capabilities. On a representative long-horizon task, TANDEM collects 2.9x as many demonstrations as full-task teleoperation at the same human intervention time. Fine-tuning a pretrained \pi_{0.5}-DROID model on 20 TANDEM demonstrations per task increases average task success from 0% to 60% across the five tasks.

## TL;DR

Human teleoperators spend substantial time demonstrating behaviors that robots can already perform autonomously, limiting the scalability of data collection for robot foundation models. Task and motion planning (TAMP) can automate many of these behaviors, but a fixed planning domain may not support every stage of a long-horizon manipulation task.

## Related
<!-- [[other-paper-citekey]] -->
