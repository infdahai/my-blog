---
citekey: "zhaoPAVEPredictiveAlignmentValueGuidedEvolutionWorldAction2026"
title: "PAVE: Predictive Alignment and Value-Guided Evolution for World-Action Policies"
authors: ["Botong Zhao", "Fang Yu", "Tim", "Senhua Zhu", "Xinyuan Chen", "Yue Lu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30378"
doi: "10.48550/arXiv.2608.30378"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# PAVE: Predictive Alignment and Value-Guided Evolution for World-Action Policies

> Botong Zhao, Fang Yu, Tim, Senhua Zhu, Xinyuan Chen, Yue Lu · 2026
> [arXiv](https://arxiv.org/abs/2608.30378) · [PDF](https://arxiv.org/pdf/2608.30378)

## Abstract

Direct vision-language-action policies generate continuous robot actions efficiently, but standard behavior cloning leaves two complementary gaps: their representations are not explicitly required to describe how the scene evolves over multiple time scales, and deployment trajectories of unequal quality are often reused without separating useful dynamics from undesirable behavior. We introduce \method, a direct world-action policy that combines outcome-agnostic predictive learning with outcome-aware policy improvement. \method first retains a local fixed-offset JEPA objective and adds trajectory-relative multi-horizon transition alignment at 25%, 50%, 75%, and 100% of the remaining episode. These training-only targets require the current policy representation to preserve both local physical changes and longer-range task progress, without supplying explicit future tokens to the action head. \method then trains an independent distributional value critic on cumulative deployment trajectories, computes action-chunk-aligned $N$-step advantages, and converts them into positive, negative, or null text conditions for a flow-matching actor. Thus, every valid trajectory can teach what physically happened, while the actor is deployed only under the condition associated with relatively better actions. The multi-horizon predictor and critic are removed from online execution, preserving direct action generation from the current observation, language instruction, and proprioception. \redclaim{Across the three simulation benchmarks, \method achieves the strongest overall performance while preserving the direct actor's online execution path.}

## TL;DR

Direct vision-language-action policies generate continuous robot actions efficiently, but standard behavior cloning leaves two complementary gaps: their representations are not explicitly required to describe how the scene evolves over multiple time scales, and deployment trajectories of unequal quality are often reused without separating useful dynamics from undesirable behavior. We introduce \method, a direct world-action policy that combines outcome-agnostic predictive learning with outcome-aware policy improvement.

## Related
<!-- [[other-paper-citekey]] -->
