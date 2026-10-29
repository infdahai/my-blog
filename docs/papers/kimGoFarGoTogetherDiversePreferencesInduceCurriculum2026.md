---
citekey: "kimGoFarGoTogetherDiversePreferencesInduceCurriculum2026"
title: "To Go Far, Go Together: Diverse Preferences Induce a Curriculum for Reward Optimization"
authors: ["Taehyung Kim", "Jongeun Choi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.18770"
doi: "10.48550/arXiv.2608.18770"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# To Go Far, Go Together: Diverse Preferences Induce a Curriculum for Reward Optimization

> Taehyung Kim, Jongeun Choi · 2026
> [arXiv](https://arxiv.org/abs/2608.18770) · [PDF](https://arxiv.org/pdf/2608.18770)

## Abstract

Learning a reward model from human feedback and optimizing a policy against it is one approach to aligning AI systems with individual users. From a fairness perspective, existing work improves such alignment by developing data-efficient and accurate reward models that capture minority preferences despite scarce data. We push this line of inquiry one step further and argue that data-efficient and accurate per-user reward models are not sufficient: users whose reward models are difficult to \textit{optimize} at the policy level can become a new underserved group. We start from the observation that one user's reward model can be easy to optimize from the initial policy while another's is not. We argue that, given a sufficiently diverse user population, a curriculum naturally emerges between easy- and hard-to-optimize reward models. Building on this insight, we propose CurriPO, which grows a tree-structured curriculum to accommodate diverse user-specific objectives, covering the population in a single traversal. Specifically, CurriPO automatically constructs a curriculum over diverse user reward models, allowing it to branch from the existing curriculum and reuse reward models previously incorporated into the curriculum. To the best of our knowledge, this is the first work to explicitly exploit multi-user structure to address optimization in AI alignment. Extensive experiments on personalized continuous control in a simulated environment show that CurriPO achieves $1.2$--$2.1\times$ the population satisfaction of the strongest baseline while substantially reducing training time. Additional analysis attributes much of this improvement to the users left underserved by conventional optimization.

## TL;DR

Learning a reward model from human feedback and optimizing a policy against it is one approach to aligning AI systems with individual users. From a fairness perspective, existing work improves such alignment by developing data-efficient and accurate reward models that capture minority preferences despite scarce data.

## Related
<!-- [[other-paper-citekey]] -->
