---
citekey: "tatenoYUBISTAGContactSemanticRichAlignmentVLAsAutomated2026"
title: "YUBI-STAG: Contact and Semantic-Rich Alignment for VLAs via Automated Video-Language Grounding"
authors: ["Masatoshi Tateno", "Takehiko Ohkawa", "Yueh-Hua Wu", "Hanlong Li", "Tatsuya Matsushima", "Yoichi Sato", "Kei Ota"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09718"
doi: "10.48550/arXiv.2610.09718"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# YUBI-STAG: Contact and Semantic-Rich Alignment for VLAs via Automated Video-Language Grounding

> Masatoshi Tateno, Takehiko Ohkawa, Yueh-Hua Wu, Hanlong Li, Tatsuya Matsushima, Yoichi Sato, Kei Ota · 2026
> [arXiv](https://arxiv.org/abs/2610.09718) · [PDF](https://arxiv.org/pdf/2610.09718)

## Abstract

Vision-Language-Action (VLA) models acquire broad manipulation capabilities via large-scale pretraining, yet eliciting them through language requires fine-grained alignment between instructions and physical interactions. Existing robot demonstrations typically provide only coarse task descriptions, omitting how actions are executed, including which gripper acts, which object is contacted, and how it is grasped and moved. We introduce YUBI-STAG, a framework for Spatio-Temporal Annotation and Grounding that automatically enriches manipulation demonstrations with interaction-rich semantics to align pretrained VLAs with fine-grained manipulation language. Combining contact-object segmentation with vision-language models, YUBI-STAG annotates object identities, attributes and states, per-gripper actions, bimanual coordination, and spatially grounded interactions. To address YUBI-STAG's reliance on localized sequences and multi-stage VLM inference, we distill it into YUBI-VLM. YUBI-VLM directly recovers action structure and annotations from raw, unsegmented video in few inference calls and operates from wrist views alone. We evaluate both frameworks on YUBI-STAG-Bench across temporal, semantic, and spatial grounding tasks. YUBI-VLM retains much of YUBI-STAG's annotation accuracy with fewer inference calls and shorter runtime while generalizing to unseen manipulations. Finally, post-training VLA policies on these annotations aligns them with fine-grained language and contact-aware structure. Bimanual experiments demonstrate improved performance and instruction following, including control over object identity, acting gripper, target location, and spatial relations absent from original labels.

## TL;DR

Vision-Language-Action (VLA) models acquire broad manipulation capabilities via large-scale pretraining, yet eliciting them through language requires fine-grained alignment between instructions and physical interactions. Existing robot demonstrations typically provide only coarse task descriptions, omitting how actions are executed, including which gripper acts, which object is contacted, and how it is grasped and moved.

## Related
<!-- [[other-paper-citekey]] -->
