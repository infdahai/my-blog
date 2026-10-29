---
citekey: "evansGraspTwinZeroShotTaskOrientedGraspOptimizationDigital2026"
title: "GraspTwin: Zero-Shot Task-Oriented Grasp Optimization via a Digital Twin"
authors: ["Daniel J. Evans", "Yinlong Dai", "Simon Stepputtis", "Dylan P. Losey"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.30543"
doi: "10.48550/arXiv.2609.30543"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# GraspTwin: Zero-Shot Task-Oriented Grasp Optimization via a Digital Twin

> Daniel J. Evans, Yinlong Dai, Simon Stepputtis, Dylan P. Losey · 2026
> [arXiv](https://arxiv.org/abs/2609.30543) · [PDF](https://arxiv.org/pdf/2609.30543)

## Abstract

As robots transition from structured factory settings into homes, they are required to interact with an ever-increasing variety of objects. Many tasks require grasping, and often it is not sufficient to just pick up the target object. Consider a task like "pouring coffee" --- to facilitate the subsequent pouring, the robot should grasp the mug by its handle. Existing learning-based approaches for grasping either find robust and collision-free grasps that are largely agnostic to the task (e.g., picking up the mug by its rim), or leverage foundation models to propose task-appropriate grasp locations that lack fine-grained physical grounding (e.g., reaching for and missing the handle). In this work, we bridge these approaches with a real-to-sim-to-real framework. Based on a single RGB-D observation, we construct a digital twin of the environment, query a large foundation model to propose grasps that align with the object's affordances and task description, and then optimize the proposals to ensure robustness and plausibility before executing the result on the real robot. Our key insight is that the grasp proposals of the foundation model should be regarded as semantic priors that serve as seeds for local, gradient-free optimization. We leverage Bayesian optimization with Thompson sampling to draw batches of nearby poses, which are subsequently evaluated in parallel under domain-randomized physics rollouts. The resulting grasp is both task-oriented and physically feasible for execution by the robot arm. Our full zero-shot real-world transfer only takes a few minutes and improves task-oriented grasping success by up to 33% as compared to other state-of-the-art pipelines. Our code is available here: https://github.com/VT-Collab/GraspTwin/

## TL;DR

As robots transition from structured factory settings into homes, they are required to interact with an ever-increasing variety of objects. Many tasks require grasping, and often it is not sufficient to just pick up the target object.

## Related
<!-- [[other-paper-citekey]] -->
