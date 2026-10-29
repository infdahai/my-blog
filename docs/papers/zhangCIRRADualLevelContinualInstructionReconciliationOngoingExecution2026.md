---
citekey: "zhangCIRRADualLevelContinualInstructionReconciliationOngoingExecution2026"
title: "CIRRA: Dual-Level Continual Instruction Reconciliation with Ongoing Execution for Embodied Robot Agents in Interactive Household Tasks"
authors: ["Ci Zhang", "Enfu Nan", "Arman Akbari", "Lin Zhao", "Li Wang", "Chen Wang", "Weiwei Chen", "Yanzhi Wang", "Geng Yuan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.08862"
doi: "10.48550/arXiv.2610.08862"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# CIRRA: Dual-Level Continual Instruction Reconciliation with Ongoing Execution for Embodied Robot Agents in Interactive Household Tasks

> Ci Zhang, Enfu Nan, Arman Akbari, Lin Zhao, Li Wang, Chen Wang, Weiwei Chen, Yanzhi Wang, Geng Yuan · 2026
> [arXiv](https://arxiv.org/abs/2610.08862) · [PDF](https://arxiv.org/pdf/2610.08862)

## Abstract

Household robots must accommodate new user instructions while executing ongoing tasks. Existing agents often regenerate or extensively revise the remaining task sequence, introducing plan ambiguity, logical inconsistency, and redundant execution. We formulate continual instruction reconciliation and propose CIRRA (Continual Instruction Reconciliation for Robot Agents), a dual-level framework combining LLM-based semantic reasoning with rule-constrained structural integration. CIRRA first grounds incoming instructions to unique executable skills and resolves underspecified actions and execution locations. It then preserves the ongoing subtask sequence as an execution backbone and generates integration candidates by inserting incoming subtasks into location-matched segments. The semantic reasoner evaluates only modified segments to identify dependencies and conflicts and select the most logically coherent local integration. This structure-preserving process maintains alignment with ongoing execution, mitigates ambiguity and inconsistency, and reuses shared subtasks to reduce redundant execution. We also introduce CHIRP (Continual Household Instruction Reconciliation and Planning), a text-based benchmark of 120 episodes across eight household environments and six categories of everyday activities. On CHIRP, CIRRA achieves 74.2% decision agreement, exceeding the strongest replanning baseline by 30 percentage points; every correct fusion decision yields a correctly placed, conflict-free schedule. On a Unitree G1 humanoid, CIRRA interrupts ongoing skills at the correct moment in every trial and significantly outperforms all baselines on every metric.

## TL;DR

Household robots must accommodate new user instructions while executing ongoing tasks. Existing agents often regenerate or extensively revise the remaining task sequence, introducing plan ambiguity, logical inconsistency, and redundant execution.

## Related
<!-- [[other-paper-citekey]] -->
