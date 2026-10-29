---
citekey: "nguyenTwoEchelonCoveringTourVehicleRoutingProblemDrones2026"
title: "A Two-Echelon Covering Tour Vehicle Routing Problem with Drones for Post-Disaster Relief"
authors: ["Dang Viet Anh Nguyen", "Rajesh Piplani", "Aldy Gunawan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38227"
doi: "10.48550/arXiv.2609.38227"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# A Two-Echelon Covering Tour Vehicle Routing Problem with Drones for Post-Disaster Relief

> Dang Viet Anh Nguyen, Rajesh Piplani, Aldy Gunawan · 2026
> [arXiv](https://arxiv.org/abs/2609.38227) · [PDF](https://arxiv.org/pdf/2609.38227)

## Abstract

We introduce the two-echelon covering tour vehicle routing problem (2E-CTVRP) for the distribution of relief supplies after a disaster. In the first echelon, a fleet of trucks transports supplies and drones from a central depot to satellites at the periphery of the affected area. In the second echelon, drones launched in parallel from the satellites deliver the supplies to the centroids of victim clusters, which are obtained by clustering the victim locations, and each truck waits at a satellite until its drones have returned. The problem combines the assignment of satellites to trucks, the sequencing of the truck routes, and the assignment of clusters to satellites, and minimizes the sum of the arrival times of the trucks at the satellites and at the depot. We formulate the 2E-CTVRP as a mixed integer linear program and propose a hybrid metaheuristic, GRASP-ILS-PR, which combines greedy randomized construction, a single-trajectory search, and periodic path relinking on the assignment of clusters to satellites. On a new benchmark set of 110 instances, GRASP-ILS-PR finds all known optimal solutions within 30 seconds, matches or improves on the one-hour solutions of a commercial solver on most larger instances, and improves on them by up to 11% for instances with 50 satellites. It clearly outperforms a conventional GRASP with evolutionary path relinking and yields more consistent results than a simulated annealing algorithm that uses the same search components. An analysis of two fleet configurations shows that few large trucks minimize the cumulative arrival time in most instances, whereas many small trucks deliver supplies to the victims earlier and more equitably in every instance.

## TL;DR

We introduce the two-echelon covering tour vehicle routing problem (2E-CTVRP) for the distribution of relief supplies after a disaster. In the first echelon, a fleet of trucks transports supplies and drones from a central depot to satellites at the periphery of the affected area.

## Related
<!-- [[other-paper-citekey]] -->
