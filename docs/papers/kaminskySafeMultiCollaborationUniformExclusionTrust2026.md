---
citekey: "kaminskySafeMultiCollaborationUniformExclusionTrust2026"
title: "Safe Multi-Robot Collaboration With Uniform Exclusion Using Trust"
authors: ["Thomas Kaminsky", "Áron Vékássy", "Hammad Izhar", "Angelia Nedić", "Stephanie Gil"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28251"
doi: "10.48550/arXiv.2610.28251"
tags: [paper, embodied-ai, "cs.MA", "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# Safe Multi-Robot Collaboration With Uniform Exclusion Using Trust

> Thomas Kaminsky, Áron Vékássy, Hammad Izhar, Angelia Nedić, Stephanie Gil · 2026
> [arXiv](https://arxiv.org/abs/2610.28251) · [PDF](https://arxiv.org/pdf/2610.28251)

## Abstract

Robot swarms coordinate through directed, time-varying local communication links, some of which may be compromised to allow the transmission of arbitrary malicious data. We provide an algorithm that acts as a wrapper around robot communication---when a robot seeks to update its state using data from some incoming links, our wrapper provides a subset of trusted links whose data can be safely incorporated. It selects these links by testing a stream of trust values---data collected from an anomaly detector on each robot---using Safe Anytime-Valid Inference. We require only that the detector be better than chance. This wrapper ensures safe and performant autonomy by providing two powerful statistical guarantees: it uniformly excludes all compromised links for all time with high user-chosen probability, but nevertheless quickly learns to trust legitimate links. Both guarantees are vital to secure generic tasks, but no previous work provides them simultaneously without restrictive assumptions on connectivity structure or the number of compromised links that are not guaranteed in practice. We study our Safe Wrapper's performance in hardware for two contrasting tasks---neural implicit mapping and heading consensus---deploying on 3 LoCoBots and 8 GoPiGos, respectively. We provide simulations using trust values sampled from hardware to validate that our approach scales well to swarms of hundreds of robots.

## TL;DR

Robot swarms coordinate through directed, time-varying local communication links, some of which may be compromised to allow the transmission of arbitrary malicious data. We provide an algorithm that acts as a wrapper around robot communication---when a robot seeks to update its state using data from some incoming links, our wrapper provides a subset of trusted links whose data can be safely incorporated.

## Related
<!-- [[other-paper-citekey]] -->
