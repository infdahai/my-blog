---
citekey: "bhatPROBEManipulationGroundedVisualQuestionAnsweringVLMAgents2026"
title: "PROBE: Manipulation-Grounded Visual Question Answering with VLM Agents"
authors: ["Vineet Bhat", "Siyi Chen", "Alex Zook", "Xuning Yang", "Stan Birchfield", "Valts Blukis", "Jonathan Tremblay"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.17129"
doi: "10.48550/arXiv.2608.17129"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# PROBE: Manipulation-Grounded Visual Question Answering with VLM Agents

> Vineet Bhat, Siyi Chen, Alex Zook, Xuning Yang, Stan Birchfield, Valts Blukis, Jonathan Tremblay · 2026
> [arXiv](https://arxiv.org/abs/2608.17129) · [PDF](https://arxiv.org/pdf/2608.17129)

## Abstract

Vision-language Models (VLMs) excel at 2D grounding, spatial reasoning and agentic tool-based planning in static scenes. However, consider asking a home robot "Is my medication still in the cabinet?" The answer may be physically hidden behind a row of containers that must first be moved aside. Answering such questions in real-world cluttered environments requires reasoning in dynamic scenes: distractors must be manipulated to reveal occluded objects, and each action changes the scene the model must reason over. We formalize this setting as Manipulation-Grounded Visual Question Answering (MG-VQA) and introduce PROBE, a framework for benchmarking and finetuning VLM agents on such tasks. We first develop PROBE-Sim, a high-fidelity tabletop simulator with everyday objects and a robot manipulator equipped with grasping and pushing tools. PROBE-Sim is used to create PROBE-Bench: an evaluation suite of 150 tasks across 6 question types on cluttered tabletop scenes, where a VLM perceives, picks up or pushes objects before answering. We observe consistent trend across all frontier VLMs: agentic tool-based methods outperform their perception-only baselines (8.0% on average) across all task types. We further design PROBE-Agent, a finetuning recipe to distill successful trajectories from a powerful teacher foundation model to a smaller open-weight model using a mixed data recipe that encourages manipulation-efficient question answering. PROBE Agent finetuned models outperform their off-the-shelf agent baseline (11.5% on average) and demonstrate positive transfer to unseen objects and a held-out task. We validate sim-to-real transfer by deploying PROBE-Agent finetuned policies in real-world tabletop environments.

## TL;DR

Vision-language Models (VLMs) excel at 2D grounding, spatial reasoning and agentic tool-based planning in static scenes. However, consider asking a home robot "Is my medication still in the cabinet?" The answer may be physically hidden behind a row of containers that must first be moved aside.

## Related
<!-- [[other-paper-citekey]] -->
