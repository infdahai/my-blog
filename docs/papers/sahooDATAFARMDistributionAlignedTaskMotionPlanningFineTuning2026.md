---
citekey: "sahooDATAFARMDistributionAlignedTaskMotionPlanningFineTuning2026"
title: "DATAFARM: Distribution-Aligned Task and Motion Planning for Fine-Tuning Vision-Language-Action Models"
authors: ["Samrat Sahoo", "Yixuan Huang", "Tom Silver"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12316"
doi: "10.48550/arXiv.2609.12316"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# DATAFARM: Distribution-Aligned Task and Motion Planning for Fine-Tuning Vision-Language-Action Models

> Samrat Sahoo, Yixuan Huang, Tom Silver · 2026
> [arXiv](https://arxiv.org/abs/2609.12316) · [PDF](https://arxiv.org/pdf/2609.12316)

## Abstract

Collecting high-quality robot data remains a fundamental challenge for training robot foundation models. Task and motion planning (TAMP) offers a scalable way to generate demonstrations, but our experiments show that raw TAMP trajectories provide surprisingly little benefit when used to fine-tune pretrained vision-language-action (VLA) models, despite successfully solving the target tasks. We hypothesize that this failure arises from a behavioral distribution mismatch between planner-generated trajectories and the data used to pretrain the VLA. To address this mismatch, we introduce DATAFARM: Distribution-Aligned Task And motion planning for Fine-tuning A Robot foundation Model, an approach that incorporates the pretraining distribution directly into TAMP trajectory generation. DATAFARM aligns generated trajectories with the pretraining data in robot joint configurations, motion style, and temporal execution profiles. We evaluate DATAFARM on three tabletop manipulation tasks that TAMP can perform and a cloth-folding task beyond the capability of TAMP. DATAFARM achieves an average success rate of 56.7%, substantially outperforming raw TAMP (8.3%) while approaching human teleoperation (61.7%). On Deformable Object Manipulation, which is outside the fine-tuning distribution, the fine-tuned model retains 85% success, compared with 90% for the pretrained model. These results show that aligning planner-generated demonstrations with the pretraining distribution can make TAMP an effective source of data for VLA fine-tuning. Website and code: https://prpl-group.com/datafarm/

## TL;DR

Collecting high-quality robot data remains a fundamental challenge for training robot foundation models. Task and motion planning (TAMP) offers a scalable way to generate demonstrations, but our experiments show that raw TAMP trajectories provide surprisingly little benefit when used to fine-tune pretrained vision-language-action (VLA) models, despite successfully solving the target tasks.

## Related
<!-- [[other-paper-citekey]] -->
