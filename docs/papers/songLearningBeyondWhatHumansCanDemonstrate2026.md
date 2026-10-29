---
citekey: "songLearningBeyondWhatHumansCanDemonstrate2026"
title: "Learning Beyond What Humans Can Demonstrate"
authors: ["Yuchen Song", "Aditya Mittal", "Unnat Jain"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24996"
doi: "10.48550/arXiv.2609.24996"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Learning Beyond What Humans Can Demonstrate

> Yuchen Song, Aditya Mittal, Unnat Jain · 2026
> [arXiv](https://arxiv.org/abs/2609.24996) · [PDF](https://arxiv.org/pdf/2609.24996)

## Abstract

Behavior cloning for robot manipulation relies on expert demonstrations. However, for tasks that require dynamic stability, precise contact timing, or dexterous coordination, human operators may find it hard or even impossible to collect data. We study this infeasible-demonstration regime and propose GLIDE: Guardrails for Learning from Infeasible Demonstrations Efficiently, a framework that infers task-specific failure modes and converts them into executable guardrails for data collection and policy deployment. Given a task description and the conditioning teleoperation code, GLIDE writes guardrails that use system states to filter teleoperation and policy commands, constrain failure-prone actions, and iteratively improve from trajectory feedback. Across three tasks, GLIDE discovers emergent guardrails that go beyond domain-expert hardcoded ones, improving data collection over naive VR teleoperation and domain-expert hardcoded guardrails. After refinement, GLIDE raises data-collection success from 0-10 percent to 70-90 percent across the three tasks. During policy execution, mixed-data guarded policies reach 70 percent, 60 percent, and 60 percent success on Tomato plate transfer, Marker handover and stand, and Wine serving tasks. These results show that GLIDE can support policy learning when direct demonstrations are infeasible. Project website: http://guardrail-policy.github.io/

## TL;DR

Behavior cloning for robot manipulation relies on expert demonstrations. However, for tasks that require dynamic stability, precise contact timing, or dexterous coordination, human operators may find it hard or even impossible to collect data.

## Related
<!-- [[other-paper-citekey]] -->
