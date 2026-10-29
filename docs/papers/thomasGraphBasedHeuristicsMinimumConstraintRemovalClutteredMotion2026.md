---
citekey: "thomasGraphBasedHeuristicsMinimumConstraintRemovalClutteredMotion2026"
title: "Graph-Based Heuristics for Minimum Constraint Removal in Cluttered Robot Motion Planning"
authors: ["Antony Thomas", "Fulvio Mastrogiovanni", "Marco Baglietto"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12609"
doi: "10.48550/arXiv.2610.12609"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Graph-Based Heuristics for Minimum Constraint Removal in Cluttered Robot Motion Planning

> Antony Thomas, Fulvio Mastrogiovanni, Marco Baglietto · 2026
> [arXiv](https://arxiv.org/abs/2610.12609) · [PDF](https://arxiv.org/pdf/2610.12609)

## Abstract

Humanoid and service robots operating in clut- tered human environments may encounter motion planning problems that are infeasible when all surrounding objects are treated as fixed obstacles. The Minimum Constraint Removal problem, which we refer to as MCR, addresses this situation by identifying the minimum number of constraints, such as movable objects, whose removal enables a collision-free path. However, computing an optimal MCR solution is NP-hard. In this work, we propose a graph-based heuristic pipeline that combines bidirectional feasible-set generation with fixed- length searches over reduced MCR graphs. We further derive an extended feasible-set generator for instances in which the candidates produced by the first generator do not contain a complete optimal removal set. Across six benchmarks, the evaluated pipeline matches the exact solution in three cases and, in the remaining cases, selects at most 31.25% more obstacles than the optimum, while being between 3.4 and 33.7 times faster than exact search. In one of the benchmarks, involving a manipulation task amidst clutter, selecting two rather than seven obstructing objects reduces the combined MCR, inverse- kinematics, and motion planning time from 84.72 s to 30.59 s. These results indicate that the proposed approach provides a practical compromise between computational efficiency and solution quality for motion planning among movable obstacles.

## TL;DR

Humanoid and service robots operating in clut- tered human environments may encounter motion planning problems that are infeasible when all surrounding objects are treated as fixed obstacles. The Minimum Constraint Removal problem, which we refer to as MCR, addresses this situation by identifying the minimum number of constraints, such as movable objects, whose removal enables a collision-free path.

## Related
<!-- [[other-paper-citekey]] -->
