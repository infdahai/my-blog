---
citekey: "abouagourMINDInstructionConditionedIncrementalGrounding2026"
title: "MIND: Instruction-Conditioned Incremental Grounding for Robots"
authors: ["Mohamed Abouagour", "Junhyun Nam", "Wonse Jo", "Byung-Cheol Min"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19262"
doi: "10.48550/arXiv.2610.19262"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# MIND: Instruction-Conditioned Incremental Grounding for Robots

> Mohamed Abouagour, Junhyun Nam, Wonse Jo, Byung-Cheol Min · 2026
> [arXiv](https://arxiv.org/abs/2610.19262) · [PDF](https://arxiv.org/pdf/2610.19262)

## Abstract

Robots following persistent language instructions must decide which cached room judgments remain valid as their environment changes. We present MIND (Maintenance via INstruction-conditioned Dependencies), a framework for maintaining target-room decisions without re-evaluating every room after each event. A language model compiles each instruction into dependencies for semantic qualification and target selection. The controller intersects semantic dependencies with event footprints, refreshes affected judgments, and updates reachability and selection separately. For fixed deterministic evaluation, planning, and selection, conservative dependency and footprint coverage preserves the decisions of full recomputation. On 240 five-event ProcTHOR sequences with an exact benchmark predicate, MIND reduces mean semantic evaluations from 30.6 to 11.2 while preserving all 1,200 post-event decisions. Frozen-evaluator experiments with Phi-4 and Qwen3-14B also preserve all 1,200 decisions, without improving the evaluators' underlying task accuracy. In 32 closed-loop AI2-THOR episodes using exact-predicate qualification and metadata-derived footprints, MIND matches the final target decision of full recomputation in every episode. Unitree G1 experiments demonstrate target reuse and reselection across room transitions without additional semantic evaluations under MIND, and abstention after a barrier and an object removal at 4 evaluations against 15 to 18. Additional materials are available at https://mind-icra27.github.io/.

## TL;DR

Robots following persistent language instructions must decide which cached room judgments remain valid as their environment changes. We present MIND (Maintenance via INstruction-conditioned Dependencies), a framework for maintaining target-room decisions without re-evaluating every room after each event.

## Related
<!-- [[other-paper-citekey]] -->
