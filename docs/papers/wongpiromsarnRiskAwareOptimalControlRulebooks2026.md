---
citekey: "wongpiromsarnRiskAwareOptimalControlRulebooks2026"
title: "Risk-Aware Optimal Control with Rulebooks"
authors: ["Tichakorn Wongpiromsarn"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.05199"
doi: "10.48550/arXiv.2609.05199"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-09-08
---

# Risk-Aware Optimal Control with Rulebooks

> Tichakorn Wongpiromsarn · 2026
> [arXiv](https://arxiv.org/abs/2609.05199) · [PDF](https://arxiv.org/pdf/2609.05199)

## Abstract

We consider safety-critical control problems involving multiple requirements with different priorities and uncertainty in their evaluation. We represent these requirements using risk-aware rulebooks, where each requirement is assigned a risk measure and an acceptable threshold, and a priority relation is defined among the requirements. Each requirement induces a risk-evaluation function that maps a policy to the risk associated with its violation. We formulate risk-aware optimal control with rulebooks as a lexicographic optimization problem over excess risks and develop an anytime filtering and branch-and-bound algorithm that progressively tightens the certified optimality gap while characterizing the corresponding set of policies at each priority level. The algorithm returns a policy together with these gaps, which bound its suboptimality. We prove that these gaps are valid for any finite computational budget and, under additional assumptions, converge to zero as the computational budget increases. We evaluate the algorithm on a synthetic benchmark with a known optimum and a realistic highway-merging simulation with CVaR-based collision, rear-braking, headway, and comfort rules.

## TL;DR

We consider safety-critical control problems involving multiple requirements with different priorities and uncertainty in their evaluation. We represent these requirements using risk-aware rulebooks, where each requirement is assigned a risk measure and an acceptable threshold, and a priority relation is defined among the requirements.

## Related
<!-- [[other-paper-citekey]] -->
