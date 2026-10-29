---
citekey: "liuGammaGroundedMultiAgentMemoryMechanicalAuditMemory2026"
title: "Gamma: Grounded Multi-Agent Memory with Mechanical Audit for Memory-Intensive Manipulation"
authors: ["Yudong Liu", "Yueqian Lin", "Zijia Tang", "Yuxi Zheng", "Yuan Li", "Shuai Zhang", "Yi Li", "Taotao Jing", "Shuangjun Liu", "Dashan Gao", "Ning Bi", "Jingwei Sun", "Yiran Chen", "Hai Helen Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12793"
doi: "10.48550/arXiv.2610.12793"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Gamma: Grounded Multi-Agent Memory with Mechanical Audit for Memory-Intensive Manipulation

> Yudong Liu, Yueqian Lin, Zijia Tang, Yuxi Zheng, Yuan Li, Shuai Zhang, Yi Li, Taotao Jing, Shuangjun Liu, Dashan Gao, Ning Bi, Jingwei Sun, Yiran Chen, Hai Helen Li · 2026
> [arXiv](https://arxiv.org/abs/2610.12793) · [PDF](https://arxiv.org/pdf/2610.12793)

## Abstract

Pretrained vision-language-action (VLA) policies fail on memory tasks, behaviour that depends on events observed long before the current frame, because their training data is overwhelmingly Markov and mapping episodic memory directly to action chunks is hard. Yet the same policy, finetuned once to follow a privileged oracle's grounded-subgoal text, nearly solves these tasks: the difficulty lies entirely in mapping memory to a grounded symbolic subgoal. Existing work entrusts this stage to a single VLM that selects keyframes and reasons over raw frames, and falls far short of the oracle: key identities and dynamics are buried in noisy pixels, the reasoning spans hundreds of frames in an unbounded context, and hallucination corrupts the memory itself. We instead present GAMMA (Grounded multi-Agent Memory with Mechanical Audit), which builds the stage as a collaborating two-agent memory system: a detector tool (SAM-3) for spatial grounding, a VLM writer that distils each replan window into one grounded text line, an append-only text memory bank, and a VLM reasoner that reads the bank and emits the next grounded subgoal at the oracle's cadence, wrapped in a propose-verify harness that admits, defers, corrects, or rejects every agent claim against mechanical visual evidence, at training-corpus construction and at deployment alike. On a sixteen-task memory-manipulation suite GAMMA recovers a large fraction of the oracle ceiling with the policy held fixed, reaching the ceiling on several tasks, and transfers with unchanged contracts to a second benchmark.

## TL;DR

Pretrained vision-language-action (VLA) policies fail on memory tasks, behaviour that depends on events observed long before the current frame, because their training data is overwhelmingly Markov and mapping episodic memory directly to action chunks is hard. Yet the same policy, finetuned once to follow a privileged oracle's grounded-subgoal text, nearly solves these tasks: the difficulty lies entirely in mapping memory to a grounded symbolic subgoal.

## Related
<!-- [[other-paper-citekey]] -->
