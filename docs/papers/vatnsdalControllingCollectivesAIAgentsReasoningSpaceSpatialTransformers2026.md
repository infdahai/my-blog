---
citekey: "vatnsdalControllingCollectivesAIAgentsReasoningSpaceSpatialTransformers2026"
title: "Controlling Collectives of AI Agents in Reasoning Space with Spatial Transformers"
authors: ["Frederic Vatnsdal", "Roshan Gopal", "Romina Garcia Camargo", "Vijay Kumar", "Alejandro Ribeiro"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28247"
doi: "10.48550/arXiv.2609.28247"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# Controlling Collectives of AI Agents in Reasoning Space with Spatial Transformers

> Frederic Vatnsdal, Roshan Gopal, Romina Garcia Camargo, Vijay Kumar, Alejandro Ribeiro · 2026
> [arXiv](https://arxiv.org/abs/2609.28247) · [PDF](https://arxiv.org/pdf/2609.28247)

## Abstract

Large Language Models (LLMs) introduce an exciting new paradigm for planning and navigation in robotics, but fail on even simple multi-robot tasks as team sizes grow. We propose COMPASS, a scalable, decentralized multi-robot architecture for controlling large collectives of agentic robots with reasoning space feedback control. Feedback is generated locally on each robot by a spatial transformer which aggregates multi-hop messages across the fleet into a learned feedback token. Our experiments find that collectives of language models demonstrate performance gains from structured diversity of the input command, which can cancel biases; an advantage that is held across scale. Compared against a centralized frontier LLM policy and a language-only communication ablation, we find that the coupled design of COMPASS decisively produces cohesive flocking formations that accurately fly the commanded intent. We show that reasoning feedback works best when composed with a compact learned token. Our ablations show that hand engineered feedback with raw state appearing in the language channel obliterates cohesion. COMPASS generalizes zero-shot to unseen instructions of ambiguous meaning while commanding flocks up to 16 times its training scale, flying up to 1024 robots under natural language commands.

## TL;DR

Large Language Models (LLMs) introduce an exciting new paradigm for planning and navigation in robotics, but fail on even simple multi-robot tasks as team sizes grow. We propose COMPASS, a scalable, decentralized multi-robot architecture for controlling large collectives of agentic robots with reasoning space feedback control.

## Related
<!-- [[other-paper-citekey]] -->
