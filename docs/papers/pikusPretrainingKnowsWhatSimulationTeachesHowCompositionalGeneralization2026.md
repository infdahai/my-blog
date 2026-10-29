---
citekey: "pikusPretrainingKnowsWhatSimulationTeachesHowCompositionalGeneralization2026"
title: "Pretraining Knows What, Simulation Teaches How: Compositional Generalization in a Sim-Trained Robot Agent"
authors: ["Benjamin Pikus", "Daniel Saunders", "Mircea Mironenco", "Salman Mohammadi", "Mathew Mathew", "Sirou Zhu", "Divya Makkar", "Xuhua Huang", "Qinbo Li", "Supreeth Narasimhaswamy", "Siyuan Cen", "Thomas Neff", "Dejia Xu", "Shyamal Buch"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.35817"
doi: "10.48550/arXiv.2610.35817"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# Pretraining Knows What, Simulation Teaches How: Compositional Generalization in a Sim-Trained Robot Agent

> Benjamin Pikus, Daniel Saunders, Mircea Mironenco, Salman Mohammadi, Mathew Mathew, Sirou Zhu, Divya Makkar, Xuhua Huang, Qinbo Li, Supreeth Narasimhaswamy, Siyuan Cen, Thomas Neff, Dejia Xu, Shyamal Buch · 2026
> [arXiv](https://arxiv.org/abs/2610.35817) · [PDF](https://arxiv.org/pdf/2610.35817)

## Abstract

A robot policy needs to understand what a task is asking for in a scene, and how to move the robot to accomplish that task. To achieve these two skills, we introduce Zero-real Agent Policy (ZAP), a recipe that teaches a small off-the-shelf vision-language model to control a robot via a simple tool harness. We use a pretrained 27B parameter model to bootstrap world understanding and reasoning, followed by supervised fine-tuning and GRPO on simple simulated tasks to teach it how to move the robot. Without any real-world robot data during training, ZAP reaches 96.7% success on real-world tasks, matching GPT-6 Astra in our harness and outperforming the MolmoAct2 VLA (33.3%), while running 3x faster and 17x cheaper than GPT-6 Astra. We demonstrate that ZAP also generalizes to completely new objects, goals, strategies, and language by seating a test tube in a rack (and choosing a different hole in the rack when prompted), handing a test tube between arms mid-air, drawing an X on a tic-tac-toe board, and playing chess. These goals and types of manipulation don't appear in our training data. Furthermore, ZAP also transfers to an unseen embodiment. On a single-arm Franka, ZAP reaches 55.9% on RoboLab-120, 4.9 percentage points ahead of the leading VLA/WAM baseline.

## TL;DR

A robot policy needs to understand what a task is asking for in a scene, and how to move the robot to accomplish that task. To achieve these two skills, we introduce Zero-real Agent Policy (ZAP), a recipe that teaches a small off-the-shelf vision-language model to control a robot via a simple tool harness.

## Related
<!-- [[other-paper-citekey]] -->
