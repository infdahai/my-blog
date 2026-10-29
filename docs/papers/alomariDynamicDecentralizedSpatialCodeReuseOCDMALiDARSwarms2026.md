---
citekey: "alomariDynamicDecentralizedSpatialCodeReuseOCDMALiDARSwarms2026"
title: "Dynamic, Decentralized Spatial Code Reuse for OCDMA LiDAR in Robot Swarms"
authors: ["Mohammad Hani Alomari"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28172"
doi: "10.48550/arXiv.2609.28172"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# Dynamic, Decentralized Spatial Code Reuse for OCDMA LiDAR in Robot Swarms

> Mohammad Hani Alomari · 2026
> [arXiv](https://arxiv.org/abs/2609.28172) · [PDF](https://arxiv.org/pdf/2609.28172)

## Abstract

Robots in a LiDAR-equipped swarm mutually interfere when their optical ranging codes collide. Existing mitigations either assign codes statically -- requiring $L=N$ distinguishable codes for $N$ robots -- or react to detected interference without a scalable, coordinated assignment rule beneath them; prior work explicitly identifies the code-assignment scaling problem as unsolved. We propose a decentralized protocol in which robots dynamically reassign spatial reuse codes based on a live, beacon-maintained interference-neighborhood graph, and prove that the number of codes required grows as $O(\log N/\log\log N)$ under constant robot density -- an unbounded improvement over the $\Theta(N)$ growth of static assignment. We validate this result under conditions substantially beyond the idealized proof -- robot mobility, imperfect beacon-based detection, and reactive reassignment -- via Monte Carlo simulation (30 seeds per condition, 95% confidence intervals): the advantage over static assignment widens from roughly $2\times$ at 15 robots to $12\times$ at 120. Against a structurally faithful, fairly constructed model of an existing coordination-free approach, our protocol achieves both substantially greater code-reuse efficiency and 30--40% lower collision risk under an identical, constrained code budget, demonstrating that coordination -- not merely reactivity -- is what closes the scaling gap.

## TL;DR

Robots in a LiDAR-equipped swarm mutually interfere when their optical ranging codes collide. Existing mitigations either assign codes statically -- requiring $L=N$ distinguishable codes for $N$ robots -- or react to detected interference without a scalable, coordinated assignment rule beneath them; prior work explicitly identifies the code-assignment scaling problem as unsolved.

## Related
<!-- [[other-paper-citekey]] -->
