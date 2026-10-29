---
citekey: "ogorelyshevaNoNeedStopFleetLocalizedAnomalyIsolationDead2026"
title: "No Need to Stop the Fleet: Localized Anomaly Isolation via Dead Zones in AGV Fleets"
authors: ["Natalia Ogorelysheva", "Falk Howar", "Jian-Jia Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.08524"
doi: "10.48550/arXiv.2610.08524"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# No Need to Stop the Fleet: Localized Anomaly Isolation via Dead Zones in AGV Fleets

> Natalia Ogorelysheva, Falk Howar, Jian-Jia Chen · 2026
> [arXiv](https://arxiv.org/abs/2610.08524) · [PDF](https://arxiv.org/pdf/2610.08524)

## Abstract

Automated Guided Vehicle (AGV) fleets in production and logistics environments rely on a system-wide emergency stop to handle local anomalies such as malfunctions, hazards, or contaminated areas. While safe, this approach halts the entire fleet even when only a small area is affected, causing unnecessary downtime. This paper proposes dead zones --- a formally defined localized isolation approach that serves as an additional fail-operational mechanism for situations where a full system-wide halt is not strictly needed. Rather than shutting down the entire fleet, a dead zone isolates the anomalous area, allowing unaffected robots to continue operating normally. We introduce two operational strategies: basic dead zone handling, in which affected robots enter a dead zone and stop, and dead zone handling with escaping, in which robots that are sufficiently far from a dead zone reroute around it. For escaping on counterclockwise trajectories we prove collision-freedom with a bounded arrival delay for all escaping robots, provided a minimum pairwise separation is kept between robots. Experimental evaluation confirms the theoretical guarantees and characterizes the throughput tradeoffs between all three approaches: full emergency stop, basic dead zone handling, and dead zone handling with escaping.

## TL;DR

Automated Guided Vehicle (AGV) fleets in production and logistics environments rely on a system-wide emergency stop to handle local anomalies such as malfunctions, hazards, or contaminated areas. While safe, this approach halts the entire fleet even when only a small area is affected, causing unnecessary downtime.

## Related
<!-- [[other-paper-citekey]] -->
