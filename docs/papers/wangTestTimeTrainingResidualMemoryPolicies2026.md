---
citekey: "wangTestTimeTrainingResidualMemoryPolicies2026"
title: "Test-Time Training as Residual Memory for Robot Policies"
authors: ["Haoxuan Wang", "Gengyu Zhang", "Ramana Rao Kompella", "Gaowen Liu", "Yan Yan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04701"
doi: "10.48550/arXiv.2610.04701"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Test-Time Training as Residual Memory for Robot Policies

> Haoxuan Wang, Gengyu Zhang, Ramana Rao Kompella, Gaowen Liu, Yan Yan · 2026
> [arXiv](https://arxiv.org/abs/2610.04701) · [PDF](https://arxiv.org/pdf/2610.04701)

## Abstract

Memory is essential for long-horizon robotic manipulation, where successful actions may depend on past events that are no longer recoverable from the current observation. As episodes grow longer, however, retaining the full history becomes increasingly costly, creating a fundamental scalability challenge for memory-augmented policies. Existing approaches address this challenge by either storing selected past observations in a bounded memory bank or compressing interaction history into a fixed-size parametric state through Test-Time Training (TTT). Yet these formulations do not explicitly distinguish between historical information that can already be recovered from the policy's current context and information that must persist beyond it. We introduce TTT-RM, which repurposes TTT as Residual Memory, using fast weights not to generically compress history but to complement a bounded memory bank by preserving task-relevant historical information that cannot be recovered from the policy's current context. Concretely, TTT-RM learns a history decoder that reconstructs historical representations from the current observation and retrieved memory. The resulting reconstruction residual captures what this context fails to explain and serves as the learning target for TTT. The TTT slow weights are optimized against this residual target so that online fast-weight updates learn to encode complementary historical information over time. The fast-weight state is then queried to produce a residual memory representation that conditions action generation. Extensive experiments on memory-intensive simulation benchmarks and real-world tasks show that TTT-RM consistently improves across multiple memory designs, outperforms diverse baselines, and supports sustained execution on a three-minute, eight-stage stowing task.

## TL;DR

Memory is essential for long-horizon robotic manipulation, where successful actions may depend on past events that are no longer recoverable from the current observation. As episodes grow longer, however, retaining the full history becomes increasingly costly, creating a fundamental scalability challenge for memory-augmented policies.

## Related
<!-- [[other-paper-citekey]] -->
