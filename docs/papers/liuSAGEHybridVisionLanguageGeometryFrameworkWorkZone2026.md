---
citekey: "liuSAGEHybridVisionLanguageGeometryFrameworkWorkZone2026"
title: "SAGE: A hybrid vision-language and geometry framework for work-zone pathway prediction under temporary traffic control"
authors: ["Jiaxi Liu", "Keshu Wu", "Weizhe Tang", "Bofeng Cao", "Sikai Chen", "Xiaopeng Li", "Steven T. Parker", "Bin Ran"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31835"
doi: "10.48550/arXiv.2610.31835"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# SAGE: A hybrid vision-language and geometry framework for work-zone pathway prediction under temporary traffic control

> Jiaxi Liu, Keshu Wu, Weizhe Tang, Bofeng Cao, Sikai Chen, Xiaopeng Li, Steven T. Parker, Bin Ran · 2026
> [arXiv](https://arxiv.org/abs/2610.31835) · [PDF](https://arxiv.org/pdf/2610.31835)

## Abstract

Temporary traffic control redirects vehicles through work zones, requiring automated vehicles to connect an interpretation of the visible devices to a continuous passing path. Geometric predictors can provide several plausible paths, yet selecting the one consistent with the temporary control remains difficult. We propose SAGE (Semantic-to-Action Grounded Execution), a read-decide-execute-check framework that separates path construction, path preference, and control compliance within a shared candidate space. The central idea is to use a vision-language model's (VLM's) trajectory as a preference over intact geometric candidates. A role-decoupled generator constructs the candidates, and rank fusion combines each candidate's geometric score with its agreement with the VLM trajectory. Supervision structured around the Manual on Uniform Traffic Control Devices (MUTCD) trains SAGE-VLM to state the lane status and hazard side before its passage decision and trajectory. The predicted hazard side enters image-space predicates derived from MUTCD provisions, which support a final intervention bounded in score and displacement. On 2,306 real-world ROADWork validation episodes, the candidates include a path within 10 px of the human demonstration in 87% of episodes, yet selection regret accounts for 53% of the geometric ranker's error. SAGE reduces average and final displacement errors by 8.3% and 12.0% relative to the ranker, mostly in the far field, and hard-constraint violations by 37%. The trajectory opinion improves all four tested generator-selector combinations. SAGE is comparable to state-of-the-art VLM modules in accuracy, with a faster-responding VLM, and outperforms four other adapted driving VLMs in displacement error and safety measures. Project page: https://hhjj233.github.io/SAGE-page/.

## TL;DR

Temporary traffic control redirects vehicles through work zones, requiring automated vehicles to connect an interpretation of the visible devices to a continuous passing path. Geometric predictors can provide several plausible paths, yet selecting the one consistent with the temporary control remains difficult.

## Related
<!-- [[other-paper-citekey]] -->
