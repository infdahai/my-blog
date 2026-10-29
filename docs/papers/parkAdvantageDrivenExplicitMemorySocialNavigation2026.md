---
citekey: "parkAdvantageDrivenExplicitMemorySocialNavigation2026"
title: "Advantage-Driven Explicit Memory for Social Navigation"
authors: ["Yeonsoo Park", "Mattia Racca", "Guillaume Bono", "Steeven Janny", "Gianluca Monaci", "Tomi Silander", "Christian Wolf"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25610"
doi: "10.48550/arXiv.2608.25610"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Advantage-Driven Explicit Memory for Social Navigation

> Yeonsoo Park, Mattia Racca, Guillaume Bono, Steeven Janny, Gianluca Monaci, Tomi Silander, Christian Wolf · 2026
> [arXiv](https://arxiv.org/abs/2608.25610) · [PDF](https://arxiv.org/pdf/2608.25610)

## Abstract

Robot policies are predominantly learned with classical parametric variants of imitation learning or RL, where training stores the agent's behavior exclusively in the policy's network parameters, putting a heavy burden on the representation learning algorithm. We propose a new navigation agent equipped with non-parametric memory which explicitly indexes prior steps leading to critical events. The advantages are twofold: first, it allows the policy to outsource some of its behavior into an explicit memory; second, it encourages a form of continual learning by allowing an agent to collect data from its testing episodes during deployment and therefore to better generalize to OOD situations. In the context of social navigation, we show that this improves the agent's capability to retain sparse, high-cost failures, such as human collisions. If the policy is trained in simulation, this also naturally addresses the sim-to-real gap, partially, by basing some of the decision making on real data. We integrate the explicit memory into a recurrent PPO architecture and use hidden states for memory retrieval to capture continuous spatiotemporal dynamics. The goal of exploiting rare, high-impact events is achieved by leveraging the RL agent's advantage signals. We train our agent in simulation with a combination of photorealistic rendering and non-visual crowd simulation and show that the agent is robust with respect to OOD social behavior.

## TL;DR

Robot policies are predominantly learned with classical parametric variants of imitation learning or RL, where training stores the agent's behavior exclusively in the policy's network parameters, putting a heavy burden on the representation learning algorithm. We propose a new navigation agent equipped with non-parametric memory which explicitly indexes prior steps leading to critical events.

## Related
<!-- [[other-paper-citekey]] -->
