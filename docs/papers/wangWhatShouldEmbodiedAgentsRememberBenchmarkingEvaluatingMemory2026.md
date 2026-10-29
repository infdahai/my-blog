---
citekey: "wangWhatShouldEmbodiedAgentsRememberBenchmarkingEvaluatingMemory2026"
title: "What Should Embodied Agents Remember? Benchmarking and Evaluating Memory Modality for Embodied Agents"
authors: ["Junxiang Wang", "Yuchen Liu", "Yi Wu", "Guofei Chen", "Nir Pechuk", "Tao Chen", "Zackory Erickson", "Yuzhe Qin", "Tianyu Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12561"
doi: "10.48550/arXiv.2610.12561"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# What Should Embodied Agents Remember? Benchmarking and Evaluating Memory Modality for Embodied Agents

> Junxiang Wang, Yuchen Liu, Yi Wu, Guofei Chen, Nir Pechuk, Tao Chen, Zackory Erickson, Yuzhe Qin, Tianyu Li · 2026
> [arXiv](https://arxiv.org/abs/2610.12561) · [PDF](https://arxiv.org/pdf/2610.12561)

## Abstract

Memory allows large language model (LLM) agents to use past experience, often stored as textual records, when responding to requests. For embodied agents that control robots, visual and spatial observations introduce a broader choice of memory modalities, affecting both the information available for subsequent tasks and the model inference costs of constructing and using memory. We introduce MeMoREval, a benchmark for studying this problem through a controlled experience-request protocol. Agents first experience a sequence of events without knowing the subsequent tasks, and subsequently they use memory to respond to information and action requests without receiving new observations. The benchmark comprises 53 tasks across four simulated indoor environments and measures task success alongside the inference costs of memory construction and use. Our reference evaluations reveal that storing frames outperforms storing generated descriptions at lower write-time inference cost for the primary model, while storing frames with scene graphs achieves the highest aggregate task success for every tested model. Extensions to accumulated experience, selective frame retention, and visual input to memory writers demonstrate how the benchmark accommodates further memory-design investigations. Two physical-robot demonstrations establish the feasibility of applying its protocol beyond simulation.

## TL;DR

Memory allows large language model (LLM) agents to use past experience, often stored as textual records, when responding to requests. For embodied agents that control robots, visual and spatial observations introduce a broader choice of memory modalities, affecting both the information available for subsequent tasks and the model inference costs of constructing and using memory.

## Related
<!-- [[other-paper-citekey]] -->
