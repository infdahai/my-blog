---
citekey: "chenCAPCodebookAlignedPredictionTokenizedPolicies2026"
title: "CAP: Codebook-Aligned Prediction for Tokenized Robot Policies"
authors: ["Haoran Chen", "Jingtian Ji", "Samuel Wheeler", "Kaylene Caswell Stocking", "Matthew Walter"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09178"
doi: "10.48550/arXiv.2610.09178"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# CAP: Codebook-Aligned Prediction for Tokenized Robot Policies

> Haoran Chen, Jingtian Ji, Samuel Wheeler, Kaylene Caswell Stocking, Matthew Walter · 2026
> [arXiv](https://arxiv.org/abs/2610.09178) · [PDF](https://arxiv.org/pdf/2610.09178)

## Abstract

Action tokenization converts continuous robot actions into discrete symbols that can be modeled autoregressively. However, existing tokenizer-based policies typically ignore the tokenizer's learned latent code structure: after tokenization, the policy treats tokens as unrelated class indices and learns a new classifier from scratch. We show that this discarded structure is valuable. We introduce Codebook-Aligned Prediction (CAP), a method that directly reuses the tokenizer's code vectors as policy class prototypes while leaving the tokenizer and policy backbone otherwise unchanged. Across four quantizer families, three simulation benchmarks, and two real-robot tasks, CAP consistently improves task success over standard token classification heads while holding the tokenizer (and therefore its reconstruction quality) fixed. Our analysis further shows that these gains are not explained by higher token accuracy or changes in the policy head alone. Instead, reusing the tokenizer codebook provides the policy with valuable information about the tokenizer's learned latent structure across tokens, making token prediction errors more benign in action space and improving the representations learned by the policy backbone. These results suggest that action tokenizers learn useful action-aware latent structure beyond discrete targets that should be preserved when training downstream policies.

## TL;DR

Action tokenization converts continuous robot actions into discrete symbols that can be modeled autoregressively. However, existing tokenizer-based policies typically ignore the tokenizer's learned latent code structure: after tokenization, the policy treats tokens as unrelated class indices and learns a new classifier from scratch.

## Related
<!-- [[other-paper-citekey]] -->
