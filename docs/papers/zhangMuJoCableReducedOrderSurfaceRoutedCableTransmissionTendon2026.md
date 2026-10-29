---
citekey: "zhangMuJoCableReducedOrderSurfaceRoutedCableTransmissionTendon2026"
title: "MuJoCable: Reduced-Order Surface-Routed Cable Transmission for Tendon-Driven Robots"
authors: ["Yi Zhang", "Qi Shao", "Yicong Lin", "Muyuan Ma", "Tao Sun", "Yue Xie"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.09612"
doi: "10.48550/arXiv.2609.09612"
tags: [paper, embodied-ai, "cs.CE", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# MuJoCable: Reduced-Order Surface-Routed Cable Transmission for Tendon-Driven Robots

> Yi Zhang, Qi Shao, Yicong Lin, Muyuan Ma, Tao Sun, Yue Xie · 2026
> [arXiv](https://arxiv.org/abs/2609.09612) · [PDF](https://arxiv.org/pdf/2609.09612)

## Abstract

Tendon transmissions reduce distal inertia and add compliance, yet routing, slack, and friction govern motion and force transfer. Mainstream rigid-body robotics simulators such as MuJoCo do not jointly resolve moving noncircular contact, unilateral tension, and segment friction. We present MuJoCable, which adds a reduced-order, configuration-dependent cable transmission to MuJoCo. Its routing algorithm jointly optimizes an ordered path across moving analytic and mesh surfaces. A unilateral axial law, directional Capstan propagation, and nodal virtual work map this path to segment tensions and body forces. The warm-started engine plugin applies these forces during simulation and exposes route and load states for design. Pulley benchmarks recover analytical transmission relations with a Capstan-ratio error below 0.5%. On the underactuated 18-joint SpiRobs, MuJoCable reveals friction-driven load growth and proximal redistribution of joint rotation that the native tendon does not represent. Hardware tests on SpiRobs and a tendon-route-coupled finger reproduce observed motion sequences. By making physical threading executable, MuJoCable brings transmission sources of the simulation-to-reality gap into route, cable, and actuator design before fabrication.

## TL;DR

Tendon transmissions reduce distal inertia and add compliance, yet routing, slack, and friction govern motion and force transfer. Mainstream rigid-body robotics simulators such as MuJoCo do not jointly resolve moving noncircular contact, unilateral tension, and segment friction.

## Related
<!-- [[other-paper-citekey]] -->
