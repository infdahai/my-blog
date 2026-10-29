---
citekey: "zhuSkillWeaverAgenticExplorationNeuralInteractionSkillsScalableData2026"
title: "SkillWeaver: Agentic Exploration over Neural Interaction Skills for Scalable Robot Data Generation"
authors: ["He Zhu", "Lusen Zhao", "Kwan Man Cheng", "Su Li", "Katerina Fragkiadaki"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36171"
doi: "10.48550/arXiv.2609.36171"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# SkillWeaver: Agentic Exploration over Neural Interaction Skills for Scalable Robot Data Generation

> He Zhu, Lusen Zhao, Kwan Man Cheng, Su Li, Katerina Fragkiadaki · 2026
> [arXiv](https://arxiv.org/abs/2609.36171) · [PDF](https://arxiv.org/pdf/2609.36171)

## Abstract

Large-scale demonstrations have driven unprecedented progress in robot learning, yet collecting robot data through teleoperation is expensive and difficult to scale to diverse environments and long-horizon tasks. Simulation offers a scalable alternative, but existing data-generation pipelines often rely on open-loop controllers, scripted skill sequences, or task-specific programs. We introduce SkillWeaver, an agentic framework that autonomously generates robot experience by exploring over Neural Interaction Skills (NIS): reusable, parameterized, closed-loop policies that expose learned physical interaction capabilities to a reasoning agent. Given a task and a simulated environment, a VLM agent reasons about what to do next, invokes and parameterizes NIS to interact with the environment, observes their outcomes, and generates verification, reflection, and memory to guide subsequent exploration. We instantiate NIS as reinforcement-learned policies for closed-loop, contact-rich manipulation and organize exploration as verifier-guided tree search, enabling the agent to discover successful long-horizon behaviors without relying on predetermined execution pipelines. SkillWeaver scales autonomously to 39.1K demonstrations across 14.1K scenes, which we distill into visuomotor policies. Across simulation benchmarks and real-world manipulation, training on SkillWeaver-generated experience substantially improves generalization to novel objects, spatial configurations, tasks, and environments, and enables zero- and few-shot sim-to-sim and sim-to-real transfer. Our results suggest agentic exploration over neural interaction skills as a scalable alternative for robot data generation.

## TL;DR

Large-scale demonstrations have driven unprecedented progress in robot learning, yet collecting robot data through teleoperation is expensive and difficult to scale to diverse environments and long-horizon tasks. Simulation offers a scalable alternative, but existing data-generation pipelines often rely on open-loop controllers, scripted skill sequences, or task-specific programs.

## Related
<!-- [[other-paper-citekey]] -->
