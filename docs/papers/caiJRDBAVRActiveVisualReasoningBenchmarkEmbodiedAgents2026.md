---
citekey: "caiJRDBAVRActiveVisualReasoningBenchmarkEmbodiedAgents2026"
title: "JRDB-AVR: An Active Visual Reasoning Benchmark for Embodied Agents in Real-World Environments"
authors: ["Zhixi Cai", "Fucai Ke", "Sukai Huang", "Maria Garcia de la Banda", "Peter J. Stuckey", "Gholamreza Haffari", "Hamid Rezatofighi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.35032"
doi: "10.48550/arXiv.2609.35032"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# JRDB-AVR: An Active Visual Reasoning Benchmark for Embodied Agents in Real-World Environments

> Zhixi Cai, Fucai Ke, Sukai Huang, Maria Garcia de la Banda, Peter J. Stuckey, Gholamreza Haffari, Hamid Rezatofighi · 2026
> [arXiv](https://arxiv.org/abs/2609.35032) · [PDF](https://arxiv.org/pdf/2609.35032)

## Abstract

In complex embodied visual reasoning scenarios, an agent often has only a limited field of view, and the evidence needed to answer a question may be distributed across time, viewpoint, and interacting objects. A model may therefore give a plausible answer without ever observing the relevant object, time, or view that supports it. Current visual reasoning benchmarks largely evaluate passive observations and final answers, overlooking settings that require active reasoning and evidence acquisition. We introduce JRDB-AVR, a benchmark derived from existing real-world JRDB robotics data through a structured question-generation engine that turns this gap into an explicit evaluation: an embodied agentic system receives a visual reasoning question, requests bounded observations by timestamp and viewing angle, and is evaluated on both the final answer and the grounded visual evidence supporting it. The benchmark contains diverse questions over multiple real-world environments involving temporal search, viewpoint selection, and human-oriented compositional reasoning. We also introduce JRDB-AVR-Agent, a reference active reasoning agentic method that maintains an explicit observation-grounded graph-based world model and answers through solving. Experiments reveal a substantial gap between answer accuracy and evidence accuracy in current baselines, showing that current VLMs can produce unsupported correct answers and that active evidence-aware evaluation is necessary for embodied visual reasoning. Code and benchmark are available at https://github.com/ControlNet/JRDB-AVR.

## TL;DR

In complex embodied visual reasoning scenarios, an agent often has only a limited field of view, and the evidence needed to answer a question may be distributed across time, viewpoint, and interacting objects. A model may therefore give a plausible answer without ever observing the relevant object, time, or view that supports it.

## Related
<!-- [[other-paper-citekey]] -->
