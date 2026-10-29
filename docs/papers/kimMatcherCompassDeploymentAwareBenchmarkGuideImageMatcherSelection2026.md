---
citekey: "kimMatcherCompassDeploymentAwareBenchmarkGuideImageMatcherSelection2026"
title: "MatcherCompass: A Deployment-Aware Benchmark to Guide Image Matcher Selection in the Wild"
authors: ["Hyunwoo Kim", "Giseop Kim"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25688"
doi: "10.48550/arXiv.2609.25688"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# MatcherCompass: A Deployment-Aware Benchmark to Guide Image Matcher Selection in the Wild

> Hyunwoo Kim, Giseop Kim · 2026
> [arXiv](https://arxiv.org/abs/2609.25688) · [PDF](https://arxiv.org/pdf/2609.25688)

## Abstract

Field robots operating across time of day and sensing modalities require accurate image correspondences within onboard time and resource budgets. However, accuracy and runtime reported for individual methods on a single device provide limited guidance for choosing a matcher and its configuration on a target platform. We present MatcherCompass, a deployment-aware benchmark for choosing local feature matchers in field robotics. Under common input and pose-evaluation procedures, we compare nine classical and learned matching pipelines across four image resolutions and supported numerical precisions. Four visual conditions cover viewpoint variation, day--night matching in visible and thermal imagery, and daytime visible--thermal matching. We evaluate pose accuracy using the area under the error--recall curve (AUC) at $5^\circ$, $10^\circ$, and $20^\circ$, and measure runtime, GPU memory, and energy per image pair on four GPU platforms spanning workstation and onboard computers. The results show that changes in hardware, input resolution, and numerical precision can move a matcher across a runtime budget boundary, altering the feasible choices. We organize the measurements into a selection guide that returns all configurations satisfying user-specified time and resource limits, together with their accuracy under the selected visual condition. MatcherCompass provides measured evidence for choosing matching pipelines that fit a robot's sensing conditions and computing hardware. Project page: https://matchercompass.github.io/.

## TL;DR

Field robots operating across time of day and sensing modalities require accurate image correspondences within onboard time and resource budgets. However, accuracy and runtime reported for individual methods on a single device provide limited guidance for choosing a matcher and its configuration on a target platform.

## Related
<!-- [[other-paper-citekey]] -->
