---
citekey: "bachoumasSOMAStackObjectsManipulationQuadruped2026"
title: "SOMA: Stack-of-Objects Manipulation using a Quadruped Robot"
authors: ["Stergios E. Bachoumas", "Panagiotis Artemiadis"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20968"
doi: "10.48550/arXiv.2610.20968"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# SOMA: Stack-of-Objects Manipulation using a Quadruped Robot

> Stergios E. Bachoumas, Panagiotis Artemiadis · 2026
> [arXiv](https://arxiv.org/abs/2610.20968) · [PDF](https://arxiv.org/pdf/2610.20968)

## Abstract

Executing heavy-duty physical manipulation in unpredictable environments remains a major challenge for quadrupedal robots lacking dedicated manipulators. This paper presents SOMA, a hierarchical reinforcement learning framework for whole-body non-prehensile manipulation of multi-object stacks using a quadruped robot. Unlike traditional methods restricted to two-dimensional planar pushing, SOMA integrates explicit robot base-height control, unlocking full three-dimensional pushing strategies. This capability enables the quadruped to manipulate complex payload stacks as a unified system while preventing relative sliding or tipping of upper layers. The architecture factorizes control into a high-level manipulation policy using a Simplified Structured State Space Sequence (S5) encoder to reason over long-horizon temporal history and predict bounded target tracking commands via Beta distributions, and a low-level locomotion policy that dynamically adapts leg stance configurations. In extensive simulation benchmarks, SOMA achieves a $90.3\%$ success rate for single-object reposing and up to $90.1\%$ for dynamic two-box stacks under stringent error margins ($0.05\text{ m}$ position error, $1^\circ$ orientation error). Finally, we validate zero-shot sim-to-real transfer on a Unitree Go1 quadruped robot across diverse payload masses and geometries, demonstrating active base-height adjustments to maintain traction and balance during heavy pushing tasks.

## TL;DR

Executing heavy-duty physical manipulation in unpredictable environments remains a major challenge for quadrupedal robots lacking dedicated manipulators. This paper presents SOMA, a hierarchical reinforcement learning framework for whole-body non-prehensile manipulation of multi-object stacks using a quadruped robot.

## Related
<!-- [[other-paper-citekey]] -->
