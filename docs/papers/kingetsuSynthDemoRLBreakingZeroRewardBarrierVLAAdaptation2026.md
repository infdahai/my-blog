---
citekey: "kingetsuSynthDemoRLBreakingZeroRewardBarrierVLAAdaptation2026"
title: "SynthDemo-RL: Breaking the Zero-Reward Barrier in VLA Adaptation with LLM-Guided Synthetic Demonstrations"
authors: ["Hiroaki Kingetsu", "Hiroaki Kurihara", "Kaoru Yokoo", "Kenji Fukumizu", "Manohar Kaul"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21650"
doi: "10.48550/arXiv.2609.21650"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# SynthDemo-RL: Breaking the Zero-Reward Barrier in VLA Adaptation with LLM-Guided Synthetic Demonstrations

> Hiroaki Kingetsu, Hiroaki Kurihara, Kaoru Yokoo, Kenji Fukumizu, Manohar Kaul · 2026
> [arXiv](https://arxiv.org/abs/2609.21650) · [PDF](https://arxiv.org/pdf/2609.21650)

## Abstract

Fine-tuning Vision-Language-Action (VLA) models commonly relies on human teleoperation demonstrations, while reinforcement learning (RL) with sparse binary rewards faces an exploration challenge when successful trajectories are rarely sampled. We propose SynthDemo-RL, a teacher-student framework in which an automated teacher converts simulator-privileged state into successful manipulation trajectories, a VLA student is distilled from them by supervised fine-tuning (SFT), and PPO with binary task-success rewards refines the student. We study reward coverage, the fraction of tasks for which at least one success is observed under the fixed evaluation protocol, as a complement to the average success rate. On LIBERO-PRO, a public benchmark of perturbed LIBERO tasks for which no demonstrations exist, 27 of 57 scored tasks are at exactly 0% success for a pi_0.5 policy fine-tuned on the original LIBERO tasks. Direct PPO from this policy, under the same PPO recipe and the same RL compute as SynthDemo-RL's refinement stage, rescues 10 of these 27 tasks and leaves 17 at 0%. SynthDemo-RL, with 50 synthesized trajectories per task and no new human demonstrations, rescues all 27 and reaches average success rates of 97.8% and 97.1% on the Position and Task axes of LIBERO-PRO, respectively. On standard LIBERO, the same pipeline reaches 96.0% with no human demonstrations, within 1.7 points of pi_0.5 trained on 50 human demonstrations per task. We further validate the pipeline on RoboTwin 2.0 and verify that trajectories from a policy trained in a MuJoCo twin execute open-loop on a physical robot.

## TL;DR

Fine-tuning Vision-Language-Action (VLA) models commonly relies on human teleoperation demonstrations, while reinforcement learning (RL) with sparse binary rewards faces an exploration challenge when successful trajectories are rarely sampled. We propose SynthDemo-RL, a teacher-student framework in which an automated teacher converts simulator-privileged state into successful manipulation trajectories, a VLA student is distilled from them by supervised fine-tuning (SFT), and PPO with binary task-success rewards refines the student.

## Related
<!-- [[other-paper-citekey]] -->
