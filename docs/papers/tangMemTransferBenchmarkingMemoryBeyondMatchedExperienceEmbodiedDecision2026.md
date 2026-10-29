---
citekey: "tangMemTransferBenchmarkingMemoryBeyondMatchedExperienceEmbodiedDecision2026"
title: "MemTransfer: Benchmarking Memory Beyond Matched Experience in Embodied Decision-Making"
authors: ["Haiming Tang", "Xianjie Dai", "Gujie Shao", "Zuyi Guo", "Jingguang Li", "Kailang Ma", "Yihong Tang", "Heye Huang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.32313"
doi: "10.48550/arXiv.2609.32313"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# MemTransfer: Benchmarking Memory Beyond Matched Experience in Embodied Decision-Making

> Haiming Tang, Xianjie Dai, Gujie Shao, Zuyi Guo, Jingguang Li, Kailang Ma, Yihong Tang, Heye Huang · 2026
> [arXiv](https://arxiv.org/abs/2609.32313) · [PDF](https://arxiv.org/pdf/2609.32313)

## Abstract

Memory lets an embodied agent reuse past experience, yet retaining useful information does not ensure that the agent can apply it when conditions change. We present MemTransfer, a benchmark comparing six memory representations, a working-memory baseline and five representations of past experience, under a shared frozen vision-language-model policy. It comprises 100 navigation cases across ten task types in a simulated warehouse, with expert demonstrations supplying the history. Three comparisons vary the starting pose, route availability, and amount and task relevance of history. With one demonstration per task, Full-context and Episodic memory reach 95.3% and 100.0% success at the original demonstration start, but lose 48-49 percentage points at a new test start. Summary changes little between these two test starts, yet with four demonstrations per task it retains a smaller fraction of its unchanged-route success after blocking (39.3%) than Working memory (44.8%) or the two trajectory memories (56-58%). At the new test start, increasing from one to four relevant demonstrations raises Episodic success by 14.3 percentage points, while the other evaluated representations gain no more than 1.3 percentage points. Replacing half of the relevant histories with other-task experience lowers success for both trajectory memories. These results show that robustness to one kind of mismatch does not imply robustness to another, motivating evaluation of both stored information and its use at decision time.

## TL;DR

Memory lets an embodied agent reuse past experience, yet retaining useful information does not ensure that the agent can apply it when conditions change. We present MemTransfer, a benchmark comparing six memory representations, a working-memory baseline and five representations of past experience, under a shared frozen vision-language-model policy.

## Related
<!-- [[other-paper-citekey]] -->
