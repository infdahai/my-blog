---
citekey: "phamSuccessfulButUnsafeAnalyticalBenchmarkRevealingCollisionsVision2026"
title: "Successful but Unsafe: An Analytical Benchmark for Revealing Collisions in Vision-and-Language Navigation"
authors: ["Hieu D. Pham", "Quoc-An Luong", "Dung D. Le"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14682"
doi: "10.48550/arXiv.2610.14682"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Successful but Unsafe: An Analytical Benchmark for Revealing Collisions in Vision-and-Language Navigation

> Hieu D. Pham, Quoc-An Luong, Dung D. Le · 2026
> [arXiv](https://arxiv.org/abs/2610.14682) · [PDF](https://arxiv.org/pdf/2610.14682)

## Abstract

Vision-and-language navigation (VLN) agents are typically evaluated by whether they reach a target and how efficiently they follow an instructed route, yet these metrics provide little information about collision behavior. Moreover, continuous VLN evaluation commonly uses a sliding regime, where an agent can slide along obstacles after a collision, potentially masking the effect of unsafe actions on navigation performance. We introduce VLN-Safe, a benchmark for analyzing collision safety under two complementary evaluation regimes: sliding, reflecting common VLN evaluation practice, and blocking, where collision-inducing actions prevent forward motion and more directly expose their consequences. Across six published agents on R2R-CE, 38.5-56.8% of successful episodes contain contact under sliding, while switching to blocking decreases success rate by 11.7-36.1 percentage points. We further analyze signals for anticipating imminent collisions and find that depth geometry and recent movement history are more informative than policy-derived signals, while safe alternatives near the policy's preferred action are rarely available. Motivated by these findings, we introduce a training-free collision guard that vetoes risky forward actions, executes an escape maneuver, and returns control to the original policy. Under blocking, the guard reduces collision steps by 62-98% and improves success rate by 6.9-29.3 percentage points across five recurrent, topological, and vision-language-action agents. Under sliding, it leaves success rate unchanged while raising the share of collision-free successes by 4.1-12.4 points. These results reveal a substantial gap between task success and collision-safe navigation and show that lightweight collision-aware intervention can improve both safety and navigation performance.

## TL;DR

Vision-and-language navigation (VLN) agents are typically evaluated by whether they reach a target and how efficiently they follow an instructed route, yet these metrics provide little information about collision behavior. Moreover, continuous VLN evaluation commonly uses a sliding regime, where an agent can slide along obstacles after a collision, potentially masking the effect of unsafe actions on navigation performance.

## Related
<!-- [[other-paper-citekey]] -->
