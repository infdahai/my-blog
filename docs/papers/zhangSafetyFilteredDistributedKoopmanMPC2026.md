---
citekey: "zhangSafetyFilteredDistributedKoopmanMPC2026"
title: "Safety-Filtered Distributed Koopman-MPC"
authors: ["Shengjun Zhang", "Wenhao Li", "Zhenxin Lin", "Zhenglong Sun"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27463"
doi: "10.48550/arXiv.2609.27463"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-25
---

# Safety-Filtered Distributed Koopman-MPC

> Shengjun Zhang, Wenhao Li, Zhenxin Lin, Zhenglong Sun · 2026
> [arXiv](https://arxiv.org/abs/2609.27463) · [PDF](https://arxiv.org/pdf/2609.27463)

## Abstract

Distributed model predictive control (DMPC) often constructs both predictions and collision constraints from neighbor trajectories, so packet loss can remove both. We separate these roles: received trajectories drive Koopman-MPC, while local sensing and shelf geometry define a hard-constrained quadratic program (QP) that projects the applied input. Its radial demand is the least constant acceleration that keeps a supporting-plane clearance nonnegative throughout one zero-order-hold interval. Complementary pair rows recover the coupled demand without exchanging safety decisions. We give an intersample separation theorem under bounded snapshot and directional plant errors, an exact max-min test for simultaneous local feasibility, and a sensing-radius condition for switching interaction graphs. Anticipatory high-order rows may be relaxed for performance, but the finite-hold rows contain no safety slack. Matched eight-robot warehouse simulations use a frozen Koopman model, nonlinear drift, bounded inputs and speed, shelf constraints, a 120 ms control period, and packet dropout. The full controller is collision-free in 20/20 matched trials and reaches 160/160 robot goals; predictive Koopman-MPC without the final projection is collision-free in 1/20 trials. All 38,400 full-method hard-row sets pass the online feasibility test, and every local QP solves. Five-stream fleet sweeps are collision-free and hard-row feasible through 16 robots; the 20-robot boundary fails only after the online margin turns negative, while the reconstructed per-agent critical path remains below the sampling period. Bounded-sensing and differential-drive tests provide additional deployment stress.

## TL;DR

Distributed model predictive control (DMPC) often constructs both predictions and collision constraints from neighbor trajectories, so packet loss can remove both. We separate these roles: received trajectories drive Koopman-MPC, while local sensing and shelf geometry define a hard-constrained quadratic program (QP) that projects the applied input.

## Related
<!-- [[other-paper-citekey]] -->
