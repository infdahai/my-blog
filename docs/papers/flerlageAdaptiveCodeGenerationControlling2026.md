---
citekey: "flerlageAdaptiveCodeGenerationControlling2026"
title: "Adaptive Code Generation for Controlling Robots"
authors: ["Justus Flerlage", "Thorsten Wittkopp", "Alexander Acker", "Odej Kao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09588"
doi: "10.48550/arXiv.2610.09588"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Adaptive Code Generation for Controlling Robots

> Justus Flerlage, Thorsten Wittkopp, Alexander Acker, Odej Kao · 2026
> [arXiv](https://arxiv.org/abs/2610.09588) · [PDF](https://arxiv.org/pdf/2610.09588)

## Abstract

Deploying robots as Complex Adaptive Systems (CAS) in unknown and dynamic environments necessitates a transition from rigid command libraries toward intention-based autonomy, as natural language represents the only medium capable of articulating complex goals beyond the capacity of finite instruction sets. While Large Language Models (LLMs) offer a path toward natural language goal description, their integration introduces significant challenges: the formalization gap between imprecise intentions and executable actions, the taxonomy gap induced by unpredictable environments, and the challenge of maintaining temporal state and progress awareness. This work introduces an architectural framework that enables robotic control by leveraging generative AI. The system follows a dual-AI design: an LLM translates high-level intentions into executable program code restricted to a formal robotic library and constrained by verifiable syntax, while a Vision-Language Model (VLM) provides semantic grounding via a distillation process. To ensure robustness, the framework incorporates environment-driven replanning triggers based on geometric and semantic thresholds, complemented by continuous runtime monitoring and an adaptive planning loop. Benchmarked across frontier models, our framework architecture demonstrates that grounding generative AI in a reactive, constrained loop enables robust fulfillment of complex intentions in dynamic and unknown environments.

## TL;DR

Deploying robots as Complex Adaptive Systems (CAS) in unknown and dynamic environments necessitates a transition from rigid command libraries toward intention-based autonomy, as natural language represents the only medium capable of articulating complex goals beyond the capacity of finite instruction sets. While Large Language Models (LLMs) offer a path toward natural language goal description, their integration introduces significant challenges: the formalization gap between imprecise intentions and executable actions, the taxonomy gap induced by unpredictable environments, and the challenge...

## Related
<!-- [[other-paper-citekey]] -->
