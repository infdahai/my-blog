---
citekey: "sathiORDERFictitiousWorldBenchmarkDomainAdaptiveEmbodiedAI2026"
title: "ORDER: A Fictitious-World Benchmark for Domain-Adaptive Embodied AI"
authors: ["Sai Krishna Reddy Sathi", "Anuj Tiwari"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22285"
doi: "10.48550/arXiv.2609.22285"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# ORDER: A Fictitious-World Benchmark for Domain-Adaptive Embodied AI

> Sai Krishna Reddy Sathi, Anuj Tiwari · 2026
> [arXiv](https://arxiv.org/abs/2609.22285) · [PDF](https://arxiv.org/pdf/2609.22285)

## Abstract

Adapting language models to new domains via continual pre-training raises a basic evaluation problem: if the training corpus overlaps with what the model already knows, performance gains cannot be cleanly attributed to new learning rather than pre-existing knowledge. This matters most for knowledge-intensive, task-light (KHTL) robot deployments - pharmaceutical dispensing, hazardous-material handling, facility-specific protocols, where the physical task is simple but the governing rules are proprietary and safety-critical, and where extensive live testing is costly or unsafe. We introduce ORDER (Ontology-driven Decision-making for Embodied Reasoning), a benchmark built on a fictitious world: a 342,069-token synthetic corpus defining a self-consistent physics that cannot appear in any model's pre-training data. ORDER pairs a 500-question knowledge test (ORDER-BENCH) with a harder compositional task, ORDER-SPATIAL: ordering objects for safe manipulation across both familiar and entirely novel scenes. GPT-4.1 without adaptation scores below chance on ORDER-SPATIAL (Kendall's tau = 0.441), showing its priors actively conflict with the invented physics. After continual pre-training, small models improve substantially on both familiar and novel scenes alike evidence of genuine world-model induction rather than memorization. We then carry this through to a robot pipeline: models that answer the knowledge test well often cannot produce valid, executable plans without a further skill-adaptation stage, after which small, fully offline models outperform GPT-4.1 even when GPT-4.1 is given retrieval access to the same rules (Kendall's tau = 0.848 vs. 0.606), on a full perception-to-execution loop demonstrated on a simulated iiwa7 arm with human-in-the-loop correction. Throughout, ORDER-SPATIAL performance, not knowledge-test accuracy is what predicts real plan quality.

## TL;DR

Adapting language models to new domains via continual pre-training raises a basic evaluation problem: if the training corpus overlaps with what the model already knows, performance gains cannot be cleanly attributed to new learning rather than pre-existing knowledge. This matters most for knowledge-intensive, task-light (KHTL) robot deployments - pharmaceutical dispensing, hazardous-material handling, facility-specific protocols, where the physical task is simple but the governing rules are proprietary and safety-critical, and where extensive live testing is costly or unsafe.

## Related
<!-- [[other-paper-citekey]] -->
