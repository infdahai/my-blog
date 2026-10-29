---
citekey: "vuAnchorVLNGeometryAnchoredVisionLanguageGroundingReasoningOpen2026"
title: "AnchorVLN: Geometry-Anchored Vision-Language Grounding Reasoning for Open-Vocabulary Navigation"
authors: ["Long Giang Vu", "Chengkai Yao", "Yuxin Liu", "FNU Aryan", "Rajath Chandrashekar Aralikatti"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12285"
doi: "10.48550/arXiv.2609.12285"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# AnchorVLN: Geometry-Anchored Vision-Language Grounding Reasoning for Open-Vocabulary Navigation

> Long Giang Vu, Chengkai Yao, Yuxin Liu, FNU Aryan, Rajath Chandrashekar Aralikatti · 2026
> [arXiv](https://arxiv.org/abs/2609.12285) · [PDF](https://arxiv.org/pdf/2609.12285)

## Abstract

Vision-Language Navigation (VLN) in unseen indoor environments is useful in real-world robotics, where an agent must follow natural-language instructions, locate objects, and answer spatial questions without a pre-built map or fixed object vocabulary. Multimodal vision-language models (VLMs) provide strong open-vocabulary grounding and zero-shot reasoning, but struggle to emit reliable metric quantities such as range, bearing, and comparative spatial relations directly from images. Existing approaches address this by folding geometry into hand-engineered pipelines or asking models to output waypoints, requiring changes to the control stack for different robots, tasks, or vocabularies. We introduce AnchorVLN, an open-vocabulary VLN system built on a simple rule: the VLM proposes semantics; geometry decides metrics. It is realised as EMBODIED-NAV-MCP, a Model Context Protocol (MCP) server driven by a VLM agent through a compact set of callable tools. Since no tool accepts distance in metres or bearing in radians, the schema enforces the semantic-geometry boundary without modifying the downstream autonomy stack. We benchmark both tasks of the CMU Vision-Language Navigation Challenge 2026: 30 instruction-following questions over 15 scenes and a frozen 45-question object-reference set. The full system achieves 64.4 percent on instruction following, dropping by 13.3 percentage points without controller modeling (t = 2.77). On object reference, geometric anchoring clears the challenge overlap threshold on 10 of 45 questions, versus 0 of 45 for direct coordinate estimation, reducing median center error from 3.37 m to 2.48 m.

## TL;DR

Vision-Language Navigation (VLN) in unseen indoor environments is useful in real-world robotics, where an agent must follow natural-language instructions, locate objects, and answer spatial questions without a pre-built map or fixed object vocabulary. Multimodal vision-language models (VLMs) provide strong open-vocabulary grounding and zero-shot reasoning, but struggle to emit reliable metric quantities such as range, bearing, and comparative spatial relations directly from images.

## Related
<!-- [[other-paper-citekey]] -->
