---
citekey: "meighanHALOHeterogeneousAllocationLocalizedObservationsVehicleRoutingProblem2026"
title: "HALO: Heterogeneous Allocation Via Localized Observations for the Vehicle Routing Problem"
authors: ["Andrew Meighan", "Hyungsub Kim", "Or Dantsker"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38760"
doi: "10.48550/arXiv.2609.38760"
tags: [paper, embodied-ai, "cs.MA", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# HALO: Heterogeneous Allocation Via Localized Observations for the Vehicle Routing Problem

> Andrew Meighan, Hyungsub Kim, Or Dantsker · 2026
> [arXiv](https://arxiv.org/abs/2609.38760) · [PDF](https://arxiv.org/pdf/2609.38760)

## Abstract

Scalable robotic fleets have become increasingly popular for various applications such as package delivery, warehouse management, and military operations. Prior fleet control algorithms solve centralized routing problems with up to $1{,}000$ tasks in controlled environments, yet they fail to consider realistic constraints such as limited observation and communication ranges typical of decentralized fleets. Thus, deploying existing fleet control algorithms into real-world settings is currently infeasible. To tackle this, we propose Heterogeneous Allocation via Localized Observations (HALO) to solve the Vehicle Routing Problem (VRP). HALO is a hybrid method that splits the VRP into allocation and routing portions to provide onboard, real-time solutions to robots in dynamic environments. During the allocation phase, HALO utilizes a heterogeneous graph neural network framework with unique message passing layers to explicitly separate the learning of spatial distributions and task-to-robot compatibility. Evaluation results on a partially observable, online variant of the VRP show HALO significantly outperforms the heuristic baseline while maintaining similar solution quality to an all-knowing offline variant of HALO. While HALO is explicitly designed for partially observable environments, it imposes no strict upper bound on the observation space allowing us to test HALO on the traditional static, single-depot VRP. Here, HALO outperforms state-of-the-art architectures strictly optimized for the static variant of the VRP by up to $14.06\%$. Throughout all testing, this framework maintains the quickest execution times which emphasizes its potential for large-scale, real-time deployment.

## TL;DR

Scalable robotic fleets have become increasingly popular for various applications such as package delivery, warehouse management, and military operations. Prior fleet control algorithms solve centralized routing problems with up to $1{,}000$ tasks in controlled environments, yet they fail to consider realistic constraints such as limited observation and communication ranges typical of decentralized fleets.

## Related
<!-- [[other-paper-citekey]] -->
