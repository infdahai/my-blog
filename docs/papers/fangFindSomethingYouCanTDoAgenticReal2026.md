---
citekey: "fangFindSomethingYouCanTDoAgenticReal2026"
title: "Find Something You Can't Do: Agentic Real-World Reinforcement Learning for Self-Improving VLA Models"
authors: ["Yuan Fang", "Zechu Li", "Haolei Tong", "Puze Liu", "Georgia Chalvatzaki"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.32069"
doi: "10.48550/arXiv.2609.32069"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# Find Something You Can't Do: Agentic Real-World Reinforcement Learning for Self-Improving VLA Models

> Yuan Fang, Zechu Li, Haolei Tong, Puze Liu, Georgia Chalvatzaki · 2026
> [arXiv](https://arxiv.org/abs/2609.32069) · [PDF](https://arxiv.org/pdf/2609.32069)

## Abstract

Vision--language--action (VLA) models provide strong priors for robotic manipulation but are typically deployed as frozen policies, unable to improve from their own failures. Real-world reinforcement learning (RL) offers a path to continued improvement, yet manual environment resets and task-success supervision hinder autonomous learning. We introduce \textbf{FIND}, an agentic real-world RL framework that closes the loop between scene understanding, weakness-aware practice, self-evaluation, and policy improvement in a persistent workspace. FIND reframes autonomous practice as a scene-conditioned, performance-aware task-selection problem: instead of restoring a predefined scene after each rollout, it uses the resulting scene to determine what to practice next. A vision--language agent identifies feasible tasks from a predefined library, prioritizes those with lower recent success rates, and evaluates outcomes using paired pre- and post-execution observations. We instantiate FIND with a frozen $π_{0.5}$ VLA and residual off-policy RL. Across eight real-world manipulation tasks, the independent human-assessed success rate improves from $55\%$ to $71.9\%$. A representative run completes 456 autonomous episodes within 6 hours of interaction, requiring 30 scene-recovery interventions and no human-provided reward labels during online learning. Ablations and systematic evaluations further examine key design choices, agent evaluation accuracy, and human intervention requirements. Our website is made publicly available at: FIND.github.io.

## TL;DR

Vision--language--action (VLA) models provide strong priors for robotic manipulation but are typically deployed as frozen policies, unable to improve from their own failures. Real-world reinforcement learning (RL) offers a path to continued improvement, yet manual environment resets and task-success supervision hinder autonomous learning.

## Related
<!-- [[other-paper-citekey]] -->
