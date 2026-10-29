---
citekey: "zhangRethinkingImplicationsHumanFeedbackPreferenceLearningHumanCollaboration2026"
title: "Rethinking the Implications of Human Feedback for Preference Learning in Human-Robot Collaboration"
authors: ["Qiping Zhang", "Kate Candon", "Debasmita Ghose", "Marynel Vázquez"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.13982"
doi: "10.48550/arXiv.2609.13982"
tags: [paper, embodied-ai, "cs.AI", "cs.HC", "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Rethinking the Implications of Human Feedback for Preference Learning in Human-Robot Collaboration

> Qiping Zhang, Kate Candon, Debasmita Ghose, Marynel Vázquez · 2026
> [arXiv](https://arxiv.org/abs/2609.13982) · [PDF](https://arxiv.org/pdf/2609.13982)

## Abstract

In Human-Robot Interaction, the standard approach to learn a reward model that represents human preferences for robot behavior consists of three steps. First, the robot collects limited direct evidence from human feedback (e.g., positive or negative binary feedback). Then, the robot utilizes the direct evidence to derive accepted or rejected labels to feasible but unchosen actions using fixed implication rules. Finally, the robot updates the reward model with both the direct and derived evidence. Unfortunately, the fixed rule can hinder preference learning: in a user study with two collaborative simulation environments, human-provided implication labels often differed from the standard fixed rule, and using the human labels substantially improved reward learning with the Preference Learning from Implicit and Explicit Feedback (PIE) algorithm. Consequently, we propose IMPLIED, an implication modeling method that treats fixed-rule implications as an initial guide while learning to infer and revise accepted and rejected action labels over time. Across evaluations on recorded human-robot interaction trajectories and a physical robot pizza-making study, IMPLIED predicts human implications more accurately than the fixed rule approach and LLM baselines, approaching the performance of a human-label oracle. In turn, IMPLIED reduces preference-estimation error and leads to robot actions that are more often rational with respect to a combined reward (which includes the true preference reward and a task-specific reward) compared to baselines. By learning to reason about the implications of human feedback, this work enables more faithful and efficient robot behavior adaptation during human-robot collaboration.

## TL;DR

In Human-Robot Interaction, the standard approach to learn a reward model that represents human preferences for robot behavior consists of three steps. First, the robot collects limited direct evidence from human feedback (e.g., positive or negative binary feedback).

## Related
<!-- [[other-paper-citekey]] -->
