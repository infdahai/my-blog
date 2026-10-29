---
citekey: "liRouteAdaptMultiExpertDiffusionPlannersUnseenRegions2026"
title: "To Route or to Adapt? Multi-Expert Diffusion Planners in Unseen Regions"
authors: ["Yun Li", "Ehsan Javanmardi", "Simon Thompson", "Jiachen Gong", "Qunli Zhang", "Zifan Zeng", "Shiming Liu", "Peng Wang", "Yidu Zhang", "Manabu Tsukada"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31095"
doi: "10.48550/arXiv.2610.31095"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# To Route or to Adapt? Multi-Expert Diffusion Planners in Unseen Regions

> Yun Li, Ehsan Javanmardi, Simon Thompson, Jiachen Gong, Qunli Zhang, Zifan Zeng, Shiming Liu, Peng Wang, Yidu Zhang, Manabu Tsukada · 2026
> [arXiv](https://arxiv.org/abs/2610.31095) · [PDF](https://arxiv.org/pdf/2610.31095)

## Abstract

Diffusion trajectory planners with domain-specific experts face a practical question in unseen regions: can they rely on selecting among existing experts, or must the planner itself adapt? We study this question using a planner with a shared adapter and per-domain expert adapters. Across three real-world held-out maps, none of eight test-time routing schemes improves the fleet-mean lateral offset over the static default, which uses the same expert for every scene. Even an oracle that selects the best expert for each scene reduces the mean offset by only 0.9 m. In contrast, reward-based fine-tuning on just 20 target-region scenes yields substantially larger gains. On matched evaluation slices, joint replay achieves a fleet-mean offset of 6.9 m, compared with 12.4 m for the static default. Comparisons under the same target-region training budget show that target-region training drives the improvement, while replaying training scenes limits forgetting on the original ODDs. On nuPlan, fine-tuning across training cities also improves open-loop offsets, although closed-loop performance deteriorates. Further diagnostics reveal that two test-time adaptation baselines achieve low offsets by producing degenerate trajectories. These results show the limited headroom for selecting among existing experts and the greater open-loop gains available from adapting the planner.

## TL;DR

Diffusion trajectory planners with domain-specific experts face a practical question in unseen regions: can they rely on selecting among existing experts, or must the planner itself adapt? We study this question using a planner with a shared adapter and per-domain expert adapters.

## Related
<!-- [[other-paper-citekey]] -->
