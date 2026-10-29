---
citekey: "nguyenDNPushDistributedNonparallelPushingForceControlMultiSystems2026"
title: "DNPush: Distributed Nonparallel Pushing Force Control of Multi-Robot Systems for Object Transportation"
authors: ["Duy Anh Nguyen", "Pham Duy Hung", "Trung Dung Ngo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04764"
doi: "10.48550/arXiv.2610.04764"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-07
---

# DNPush: Distributed Nonparallel Pushing Force Control of Multi-Robot Systems for Object Transportation

> Duy Anh Nguyen, Pham Duy Hung, Trung Dung Ngo · 2026
> [arXiv](https://arxiv.org/abs/2610.04764) · [PDF](https://arxiv.org/pdf/2610.04764)

## Abstract

This letter proposes DNPush, a Distributed Nonparallel Pushing force controller for cooperative object transport without inter-robot communication. Each robot uses local force measurements, a preassigned force weight, and a locally expressed desired transport direction, without requiring an object model, contact locations, a CoM estimate, or moment arm magnitudes online. DNPush regulates nonparallel force magnitudes from local force direction misalignments through a reciprocal-sine law. Under the stated contact conditions, Lyapunov analysis with LaSalle's invariance principle proves convergence to a unique rotational equilibrium, where perpendicular force contributions cancel and the net torque from normal forces is zero. Object velocity converges to the desired transport direction, and suitable contact regions exist for convex polygons. Simulations isolate the reciprocal-sine scaling mechanism, five-robot coordination, and active rotational damping. Hardware experiments with soft tactile differential-drive robots achieve a velocity direction error of 0.61 deg +/- 0.79 deg over five trials with a fixed transport direction and demonstrate object transport through waypoints with three robots.

## TL;DR

This letter proposes DNPush, a Distributed Nonparallel Pushing force controller for cooperative object transport without inter-robot communication. Each robot uses local force measurements, a preassigned force weight, and a locally expressed desired transport direction, without requiring an object model, contact locations, a CoM estimate, or moment arm magnitudes online.

## Related
<!-- [[other-paper-citekey]] -->
