---
citekey: "guCognitiveActionReasoningProactiveHumanCenteredMultimodalObservations2026"
title: "Cognitive Action Reasoning for Proactive Robots from Human-Centered Multimodal Observations"
authors: ["Zhihao Gu", "Kechao Zhu", "Yuanfeng Wu", "Mohan Liu", "Ankit Kumar Shaw", "ChenDong Hong", "Xuanyu Chen", "Dengchen Mei", "Xu Tianyi", "Lin Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23486"
doi: "10.48550/arXiv.2609.23486"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Cognitive Action Reasoning for Proactive Robots from Human-Centered Multimodal Observations

> Zhihao Gu, Kechao Zhu, Yuanfeng Wu, Mohan Liu, Ankit Kumar Shaw, ChenDong Hong, Xuanyu Chen, Dengchen Mei, Xu Tianyi, Lin Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.23486) · [PDF](https://arxiv.org/pdf/2609.23486)

## Abstract

Robots operating in human-centered environments are typically designed to execute explicit instructions, and most robot-learning datasets likewise pair observations with task instructions or low-level actions. Although recent work has begun to explore proactive embodied assistance, existing resources target different settings and action levels, leaving real-world human-centered multimodal decision-making underexplored. We formulate this problem as \textit{Proactive Robot Action Reasoning} (\textit{ProRobo}), an upstream cognitive decision problem in which a robot must determine which action to take based on multimodal human and environmental cues without explicit action instructions. To support ProRobo, we introduce \textit{ProAction}, a real-world multimodal dataset containing 10K samples of visual observations, audio signals, and text inputs across 12 daily-life scenarios in five common scenes. To construct cognitively grounded high-level action supervision, we develop a two-stage human-in-the-loop pipeline that combines appraisal-guided candidate generation with Affective Theory-of-Mind-guided human refinement, explicitly incorporating contextual judgment about human states, urgency, feasibility, and potential risk into action annotation. Based on this supervision, we benchmark representative Multimodal Large Language Models (MLLMs) and introduce \textit{MMC2Act}, a reference model that implicitly learns the mapping from multimodal observations to cognitively grounded high-level actions. Experiments across modality settings, subject-disjoint generalization, cross-dataset transfer, and human evaluation show that general-purpose MLLMs struggle with proactively reasoning high-level actions from multimodal cues, whereas training on \textit{ProAction} substantially improves performance.

## TL;DR

Robots operating in human-centered environments are typically designed to execute explicit instructions, and most robot-learning datasets likewise pair observations with task instructions or low-level actions. Although recent work has begun to explore proactive embodied assistance, existing resources target different settings and action levels, leaving real-world human-centered multimodal decision-making underexplored.

## Related
<!-- [[other-paper-citekey]] -->
