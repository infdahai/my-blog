---
citekey: "parkSimultaneousForwardInverseHumanLoopOptimization2026"
title: "Simultaneous Forward and Inverse Human-in-the-Loop Optimization"
authors: ["Kyeongwon Park", "Steven H. Collins"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22630"
doi: "10.48550/arXiv.2609.22630"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Simultaneous Forward and Inverse Human-in-the-Loop Optimization

> Kyeongwon Park, Steven H. Collins · 2026
> [arXiv](https://arxiv.org/abs/2609.22630) · [PDF](https://arxiv.org/pdf/2609.22630)

## Abstract

Subjective user experience is important to human-robot interaction, but the outcomes users value, and how those preferences vary across individuals and contexts, are often unknown. While inverse learning approaches using human data can help identify user rewards, in many assistive settings the experimental costs of executing a control policy, measuring biomechanical or physiological outcomes, and collecting user feedback often limit the number of queries and optimization iterations. Here, we present Simultaneous Forward and Inverse Human-In-the-Loop Optimization (SFIHILO), which efficiently infers individual-specific reward functions from preferences over human outcomes and identifies a final control policy that maximizes the learned reward. SFIHILO bootstraps a forward model to predict user outcomes from control policies, uses this model for active querying to accelerate inverse reward learning, and then optimizes the final control policy without additional user trials. We score candidate policies by their expected reduction in uncertainty across both forward and inverse beliefs, targeting a regional preference boundary to robustly inform this simultaneous learning process. In simulation, we show that SFIHILO was effective across user heterogeneity, outcome dimensionalities, precision requirements, noise levels, and nonstationarity; compared with mutual information approaches, the proposed active querying strategy significantly improved sample efficiency in inverse learning while preserving forward model accuracy. This approach demonstrates the potential to infer latent human goals, enabling more transferable and effective human-robot interaction.

## TL;DR

Subjective user experience is important to human-robot interaction, but the outcomes users value, and how those preferences vary across individuals and contexts, are often unknown. While inverse learning approaches using human data can help identify user rewards, in many assistive settings the experimental costs of executing a control policy, measuring biomechanical or physiological outcomes, and collecting user feedback often limit the number of queries and optimization iterations.

## Related
<!-- [[other-paper-citekey]] -->
