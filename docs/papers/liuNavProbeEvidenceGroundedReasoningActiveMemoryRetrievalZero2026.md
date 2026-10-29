---
citekey: "liuNavProbeEvidenceGroundedReasoningActiveMemoryRetrievalZero2026"
title: "NavProbe: Evidence-Grounded Reasoning with Active Memory Retrieval for Zero-Shot Navigation"
authors: ["Jingyang Liu", "Sujia Yao", "Jiayuan Gu", "Lan Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27526"
doi: "10.48550/arXiv.2609.27526"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# NavProbe: Evidence-Grounded Reasoning with Active Memory Retrieval for Zero-Shot Navigation

> Jingyang Liu, Sujia Yao, Jiayuan Gu, Lan Xu · 2026
> [arXiv](https://arxiv.org/abs/2609.27526) · [PDF](https://arxiv.org/pdf/2609.27526)

## Abstract

Long-horizon navigation requires an agent to revise its intermediate objectives as evidence accumulates. Full visual histories are costly to process, while compact summaries may omit details needed to reconsider earlier decisions. We introduce NavProbe, a hierarchical zero-shot navigation agent that couples a dynamic subgoal agenda with active evidence retrieval. A compact index links summaries of visited places, transitions, and landmarks to their visual and geometric records. When the current context is insufficient, a task executive retrieves targeted evidence to generate, revise, or resolve subgoals. Reusable conclusions are used to update the index, and a skill policy converts the revised task state into parameterized navigation actions. NavProbe achieves 71.7% SR and 55.8% SPL on R2R-CE and 55.3% SR and 38.6% SPL on RxR-CE, outperforming strong zero-shot baselines. It also achieves 79.3% SR on HM3D-v2 ObjectNav, with qualitative real-robot demonstrations illustrating physical deployment.

## TL;DR

Long-horizon navigation requires an agent to revise its intermediate objectives as evidence accumulates. Full visual histories are costly to process, while compact summaries may omit details needed to reconsider earlier decisions.

## Related
<!-- [[other-paper-citekey]] -->
