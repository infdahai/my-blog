---
citekey: "dingJARVISVisualManualsAutonomousAssembly2026"
title: "JARVIS: From Visual Manuals to Autonomous Robotic Assembly"
authors: ["Fan Ding", "Fucai Ke", "Kevin Yuchen Ma", "Xuewen Luo", "Wenyu Liang", "Vishnu Monn Baskaran", "Hamid Rezatofighi", "Yan Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27618"
doi: "10.48550/arXiv.2610.27618"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# JARVIS: From Visual Manuals to Autonomous Robotic Assembly

> Fan Ding, Fucai Ke, Kevin Yuchen Ma, Xuewen Luo, Wenyu Liang, Vishnu Monn Baskaran, Hamid Rezatofighi, Yan Wu · 2026
> [arXiv](https://arxiv.org/abs/2610.27618) · [PDF](https://arxiv.org/pdf/2610.27618)

## Abstract

Visual manuals communicate procedural knowledge through stepwise diagrams, but translating these instructions into reliable long-horizon robotic execution remains challenging. We introduce JARVIS, a method-agnostic benchmark for autonomous visual-manual-guided execution without additional language instructions. JARVIS comprises 236,679 LEGO assembly tasks across 8,987 scenes, with a carefully curated JARVIS-v1 suite of 50 tasks for interactive robotic evaluation. Tasks span varying initial structural complexities and assembly horizons, requiring agents to interpret manuals, ground actions in an evolving workspace, and execute the intended procedure. A structure-aware evaluation protocol captures geometric accuracy, structural relations, construction order, partial progress, and completion. We further introduce JARVIS-agentic, a tool-grounded embodied agent that composes robot primitives into executable programs and uses execution feedback for verification and recovery, without task-specific action trajectories or model parameter updates. Across nine multimodal and reasoning models, task-oriented primitives increase the average assembly score. Performance nevertheless declines sharply with assembly horizon, and execution errors remain difficult to correct. Prior-task experience improves initial performance, while repeated reflection provides inconsistent benefits, highlighting persistent limitations in connecting visual procedural reasoning with reliable physical execution.

## TL;DR

Visual manuals communicate procedural knowledge through stepwise diagrams, but translating these instructions into reliable long-horizon robotic execution remains challenging. We introduce JARVIS, a method-agnostic benchmark for autonomous visual-manual-guided execution without additional language instructions.

## Related
<!-- [[other-paper-citekey]] -->
