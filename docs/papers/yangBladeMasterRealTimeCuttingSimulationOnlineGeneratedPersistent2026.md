---
citekey: "yangBladeMasterRealTimeCuttingSimulationOnlineGeneratedPersistent2026"
title: "BladeMaster: Real-Time Robotic Cutting Simulation with Online-Generated Persistent Discontinuities"
authors: ["Zhanyu Yang", "Yunuo Chen", "Yanjia Huang", "Joseph Masterjohn", "Yin Yang", "Chenfanfu Jiang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27342"
doi: "10.48550/arXiv.2609.27342"
tags: [paper, embodied-ai, "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# BladeMaster: Real-Time Robotic Cutting Simulation with Online-Generated Persistent Discontinuities

> Zhanyu Yang, Yunuo Chen, Yanjia Huang, Joseph Masterjohn, Yin Yang, Chenfanfu Jiang · 2026
> [arXiv](https://arxiv.org/abs/2609.27342) · [PDF](https://arxiv.org/pdf/2609.27342)

## Abstract

Cutting changes both the shape and topology of deformable objects, making accurate simulation challenging for robotic manipulation. A simulator must track the cutting tool as a cut develops, preserve the resulting discontinuities after tool withdrawal, and enable newly exposed surfaces to interact with the tool and with each other. Existing formulations often prescribe cut surfaces in advance or couple material separation to auxiliary geometric fields. We introduce BladeMaster, a GPU-accelerated cutting framework based on the total Lagrangian material point method (TLMPM). Our key idea is to encode the cutting history directly on material points through persistent side labels generated online from the blade geometry. These labels govern particle-grid coupling, preserving connectivity within intact material while preventing spurious coupling across cut faces after tool withdrawal. Our formulation supports progressive and intersecting cuts without predefined cut surfaces or particle duplication. Material-material contact enables cut surfaces to recontact and slide against each other without reconnecting, while two-way tool-material coupling allows material reaction forces to influence tool motion. Experiments demonstrate tool-driven cutting followed by manipulation, with faster-than-real-time performance on representative tasks.

## TL;DR

Cutting changes both the shape and topology of deformable objects, making accurate simulation challenging for robotic manipulation. A simulator must track the cutting tool as a cut develops, preserve the resulting discontinuities after tool withdrawal, and enable newly exposed surfaces to interact with the tool and with each other.

## Related
<!-- [[other-paper-citekey]] -->
