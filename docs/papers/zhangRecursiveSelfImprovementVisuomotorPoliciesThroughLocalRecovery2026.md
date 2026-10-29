---
citekey: "zhangRecursiveSelfImprovementVisuomotorPoliciesThroughLocalRecovery2026"
title: "Recursive Self-Improvement of Visuomotor Policies through Local Recovery Supervision"
authors: ["Yuzhi Zhang", "Xinyu Liu", "Yu Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05151"
doi: "10.48550/arXiv.2610.05151"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Recursive Self-Improvement of Visuomotor Policies through Local Recovery Supervision

> Yuzhi Zhang, Xinyu Liu, Yu Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.05151) · [PDF](https://arxiv.org/pdf/2610.05151)

## Abstract

Visuomotor policies can execute familiar tasks yet lack the corrective behavior needed after their own mistakes. We present a framework for recursive self-improvement through local recovery supervision. Each round audits the current policy, generates corrective demonstrations at supported failure states, and uses them to update the policy that drives the next round of collection. An offline auditor locates unresolved failures using coarse and dense temporal evidence and specifies observable repair goals. A fixed multimodal agent acts as a tool-using teacher, generating recovery actions through observation, computation, execution, and feedback. The frozen student tests whether each teacher endpoint supports further progress. If continuation fails, the system restores that endpoint and extends the demonstration. Action-level quality assessment then defines continuous training windows with aligned observations, quality weights, and validity masks. Only the student is deployed. In a preliminary LIBERO-Goal study, recovery-augmented post-training achieves 88 successful episodes out of 100 validation scenes, compared with 78 for original-data continuation from the same $\pi_0$ checkpoint. An earlier BC-RNN study on robomimic Can improves success from 102/130 to 112/130 using 26 local recovery segments. Both comparisons match 2,000 additional optimization steps.

## TL;DR

Visuomotor policies can execute familiar tasks yet lack the corrective behavior needed after their own mistakes. We present a framework for recursive self-improvement through local recovery supervision.

## Related
<!-- [[other-paper-citekey]] -->
