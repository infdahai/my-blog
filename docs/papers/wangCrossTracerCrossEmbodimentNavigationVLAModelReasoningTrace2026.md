---
citekey: "wangCrossTracerCrossEmbodimentNavigationVLAModelReasoningTrace2026"
title: "CrossTracer: Cross-Embodiment Navigation via VLA Model Reasoning and Trace Residuals Adapting"
authors: ["Yao Wang", "Siyuan Wang", "Zhirui Sun", "Wenzheng Chi", "Liang Lin", "Jiankun Wang", "Wenjun Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.06688"
doi: "10.48550/arXiv.2608.06688"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# CrossTracer: Cross-Embodiment Navigation via VLA Model Reasoning and Trace Residuals Adapting

> Yao Wang, Siyuan Wang, Zhirui Sun, Wenzheng Chi, Liang Lin, Jiankun Wang, Wenjun Xu · 2026
> [arXiv](https://arxiv.org/abs/2608.06688) · [PDF](https://arxiv.org/pdf/2608.06688)

## Abstract

Vision-language-action (VLA) models provide strong semantic priors for robot navigation, but they often ignore embodiment-specific mobility constraints. A path that is semantically plausible for one robot may be physically infeasible for another. We propose CrossTracer, a hierarchical framework for cross-embodiment navigation through adaptive trace residuals. CrossTracer represents navigation plans as normalized image-plane waypoints, forming a unified pixel-space interface between semantic reasoning and physical grounding. First, Vision-Language Trace Proposer (VL-Tracer) adapts a pretrained VLA model to predict an initial navigation trace from egocentric observations and flexible goal specifications. Second, CE-Adapter refines this trace by predicting embodiment-conditioned residual corrections from visual traversability cues, robot identity, and the initial trace. To train the refinement module without costly manual annotation, Cross-Embodiment RRT* (CE-RRT*) converts panoptic segmentation into robot-conditioned traversability cost maps and generates cost-minimizing pixel-space traces. We evaluate CrossTracer on the NaviTrace benchmark, which tests whether a model can generate embodiment-consistent navigation traces from egocentric observations, language instructions, and robot embodiment types. CrossTracer achieves a total score of 45.68, outperforming the strongest evaluated general-purpose baseline, Gemini-2.5-Pro, by 10.01 points, corresponding to a 28.1% relative improvement. Real-world deployment on wheeled and legged robots further shows improved navigation success and execution efficiency.

## TL;DR

Vision-language-action (VLA) models provide strong semantic priors for robot navigation, but they often ignore embodiment-specific mobility constraints. A path that is semantically plausible for one robot may be physically infeasible for another.

## Related
<!-- [[other-paper-citekey]] -->
