---
citekey: "lyuLUCIDAgenticAIFrameworkDigitalTwinLoopQoS2026"
title: "LUCID: An Agentic AI Framework on Digital-Twin in the Loop for QoS-Guaranteeing Robotic Control"
authors: ["Hyeonsu Lyu", "Minwoo Kim", "Sehyun Ryu", "Hyun Jong Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28437"
doi: "10.48550/arXiv.2608.28437"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-08-31
---

# LUCID: An Agentic AI Framework on Digital-Twin in the Loop for QoS-Guaranteeing Robotic Control

> Hyeonsu Lyu, Minwoo Kim, Sehyun Ryu, Hyun Jong Yang · 2026
> [arXiv](https://arxiv.org/abs/2608.28437) · [PDF](https://arxiv.org/pdf/2608.28437)

## Abstract

Cloud robotics relies on the timely uplink of high-volume sensing streams, yet dynamic environments continually shift the feasible combinations of trajectories, active-robot count, and per-robot QoS. Because existing approaches formulate trajectory planning (TP) and radio resource management (RRM) as a single fixed optimization problem, they cannot reconfigure these coupled decisions as conditions evolve, resulting in transient QoS violations. However, evolving operator intents change which quantities-such as the active-robot count and per-robot QoS-are fixed, optimized, or relaxed. Furthermore, the computational cost of evaluating trajectory-dependent wireless conflicts has made it difficult to build large-scale Digital-Twin-in-the-Loop (DITL) testbeds responsive enough for such dynamic orchestration. We present LUCID, an LLM-agent--orchestrated, uplink-aware cloud-robotics pipeline that moves TP--RRM from solving a fixed formulation to dynamically orchestrating optimization problem schemas within a DITL environment. Driven by the operator's high-level intent, LUCID treats the TP--RRM formulation as a bounded template whose variables, objectives, and constraints are dynamically configured, while SimBridge enables repeated ray-tracing evaluation by converting large-scale robotics scenes into wireless-ready DTs. By integrating collision-free path planning with a spectral-radius RRM validator, LUCID identifies wireless bottlenecks and restructures the problem schema on the fly to efficiently find the verified feasible state. Experiments confirm that LUCID robustly adapts to changing intents, active-robot counts, and scenes, while a multimodal surrogate model, FastConfigNet, reduces planning latency.

## TL;DR

Cloud robotics relies on the timely uplink of high-volume sensing streams, yet dynamic environments continually shift the feasible combinations of trajectories, active-robot count, and per-robot QoS. Because existing approaches formulate trajectory planning (TP) and radio resource management (RRM) as a single fixed optimization problem, they cannot reconfigure these coupled decisions as conditions evolve, resulting in transient QoS violations.

## Related
<!-- [[other-paper-citekey]] -->
