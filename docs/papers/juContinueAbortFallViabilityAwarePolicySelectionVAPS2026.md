---
citekey: "juContinueAbortFallViabilityAwarePolicySelectionVAPS2026"
title: "Continue, Abort, or Fall: Viability-Aware Policy Selection (VAPS) for Safe Humanoid Acrobatics"
authors: ["Siwei Ju", "Lu Liu", "Jan Peters", "Oleg Arenz"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01397"
doi: "10.48550/arXiv.2610.01397"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Continue, Abort, or Fall: Viability-Aware Policy Selection (VAPS) for Safe Humanoid Acrobatics

> Siwei Ju, Lu Liu, Jan Peters, Oleg Arenz · 2026
> [arXiv](https://arxiv.org/abs/2610.01397) · [PDF](https://arxiv.org/pdf/2610.01397)

## Abstract

Dynamic humanoid motions such as flips risk hardware damage due to suboptimal policies, disturbances or sim-to-real gaps. A motion tracking policy offers no way out once the maneuver leaves its reference, and a backup policy needs to take over to protect the hardware for a minimum-damage landing. Which backup to use matters as much as when to switch. We present Viability-Aware Policy Selection (VAPS), which treats safety as a policy-conditioned, receding-horizon decision. Besides a protective fall policy, we also train an abort policy which can abort the motion at any time, landing on its feet. At every control step, learned predictors estimate whether the nominal tracking policy and the abort policy remain viable over a short horizon, and a least-sacrificial hierarchy keeps the most task-ambitious behavior that remains viable. In simulation with randomized disturbances, VAPS sharply reduces head contact and hand contact, which are the dominant sources of hardware damage, with both a Unitree G1 and a LimX Oli; on the LimX Oli, we validate the viability predictors and the full VAPS controller for side-flip motions. VAPS Pareto-dominates the strongest single-network alternatives we could train, including an end-to-end safe-tracking policy and students distilled from VAPS's own oracle-routed decisions, in both task success and head impact. We also show that VAPS is a powerful framework to supervise undertrained policies and protect the hardware.

## TL;DR

Dynamic humanoid motions such as flips risk hardware damage due to suboptimal policies, disturbances or sim-to-real gaps. A motion tracking policy offers no way out once the maneuver leaves its reference, and a backup policy needs to take over to protect the hardware for a minimum-damage landing.

## Related
<!-- [[other-paper-citekey]] -->
