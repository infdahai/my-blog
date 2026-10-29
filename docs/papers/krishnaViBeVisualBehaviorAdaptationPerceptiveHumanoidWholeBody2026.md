---
citekey: "krishnaViBeVisualBehaviorAdaptationPerceptiveHumanoidWholeBody2026"
title: "ViBe: Visual Behavior Adaptation for Perceptive Humanoid Whole-Body Control"
authors: ["Lokesh Krishna", "Sarvesh Venkatesan", "An Zhang", "Quan Nguyen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.09918"
doi: "10.48550/arXiv.2609.09918"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# ViBe: Visual Behavior Adaptation for Perceptive Humanoid Whole-Body Control

> Lokesh Krishna, Sarvesh Venkatesan, An Zhang, Quan Nguyen · 2026
> [arXiv](https://arxiv.org/abs/2609.09918) · [PDF](https://arxiv.org/pdf/2609.09918)

## Abstract

Motion tracking provides a scalable recipe for humanoid whole-body control. By design, the resulting trackers lack exteroceptive feedback hence reacting to the environment remains the responsibility of a higher-level planner. Existing perceptive controllers train geometry-only encoders from scratch, trading semantics for sim-to-real ease, and typically rely on teacher-student distillation for a task of interest. We present ViBe, a post-training framework for adapting motion trackers to perceptive control tasks. We leverage pre-trained visual encoders with a multi-query extractor module to learn task-relevant perceptive feedback. This feedback is grafted onto the tracker's input via low-rank adapters, enabling parameter-efficient fine-tuning. Given a task reward and a reference dataset, this modular controller can be adapted directly via policy optimization. Across four tasks, ViBe shows zero-shot sim-to-real transfer spanning perceptive walking on curbs and parkour, Repose Cube, omni-object loco-manipulation, and dodgeball, with visually robust performance across outdoor, low-light, and RGB distractor conditions. Finally, we solve a goal-oriented Repose Cube task with a deliberately simple planner, demonstrating the efficacy of perceptive controllers, adapted by our approach.

## TL;DR

Motion tracking provides a scalable recipe for humanoid whole-body control. By design, the resulting trackers lack exteroceptive feedback hence reacting to the environment remains the responsibility of a higher-level planner.

## Related
<!-- [[other-paper-citekey]] -->
