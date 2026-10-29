---
citekey: "zhangREDIRECT1FixBadHabits2026"
title: "REDIRECT: A 1% Fix for Bad Robot Habits"
authors: ["Yu Zhang", "Jiazhuo Li", "Yancong Wei", "Kangkang Dong", "Xiaojun Zhu", "Houde Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.03997"
doi: "10.48550/arXiv.2610.03997"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# REDIRECT: A 1% Fix for Bad Robot Habits

> Yu Zhang, Jiazhuo Li, Yancong Wei, Kangkang Dong, Xiaojun Zhu, Houde Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.03997) · [PDF](https://arxiv.org/pdf/2610.03997)

## Abstract

Robots can acquire bad habits from a few defective moments in otherwise useful teleoperation. In mixed-quality robot data, normal and problematic demonstrations share most task behavior and differ only at a local action continuation. Full retraining is costly, while fine-tuning on clean data alone offers limited recovery under a small update budget. We ask whether the local difference can instead be fixed with only 1% of the full-training sample-backward budget. Using only episode-level retained/problematic labels, REDIRECT localizes the branch, assigns a coherent retained continuation to the original observations around it, and anchors shared behavior, without frame-level annotations or additional interaction. Across three randomized ManiSkill tasks and three seeds, REDIRECT raises the mean success rate from 68.2% to 90.3%, recovering 88.8% of the clean-retraining gap versus 22.1% for matched-compute fine-tuning. On a PiPER arm, it recovers 86.7-92.9% of the clean-only gap across cup insertion and towel folding. Local robot habits can therefore be repaired by spending the update budget on the behavioral difference rather than relearning shared behavior.

## TL;DR

Robots can acquire bad habits from a few defective moments in otherwise useful teleoperation. In mixed-quality robot data, normal and problematic demonstrations share most task behavior and differ only at a local action continuation.

## Related
<!-- [[other-paper-citekey]] -->
