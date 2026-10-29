---
citekey: "wangCrackingMobileManipulationFailureDiagnosisAgenticSystem2026"
title: "Cracking Mobile Manipulation: From Failure Diagnosis to Agentic Robot System"
authors: ["Zixuan Wang", "Jia-Ning Li", "Yinzhou Tang", "Yanzhao Yu", "Biao Wu", "Meng Fang", "Xin Li", "Yiwu Zhong"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19600"
doi: "10.48550/arXiv.2610.19600"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Cracking Mobile Manipulation: From Failure Diagnosis to Agentic Robot System

> Zixuan Wang, Jia-Ning Li, Yinzhou Tang, Yanzhao Yu, Biao Wu, Meng Fang, Xin Li, Yiwu Zhong · 2026
> [arXiv](https://arxiv.org/abs/2610.19600) · [PDF](https://arxiv.org/pdf/2610.19600)

## Abstract

Recent vision-language-action (VLA) models have shown strong performance on local robot manipulation, yet their success does not readily translate to long-horizon mobile manipulation. In our experiments, a pretrained subtask VLA achieves 80% success rate on atomic manipulation tasks but only 19% when these skills are composed into mobile manipulation. We argue that this gap stems from failures across the execution process rather than from local manipulation capability alone. To uncover these bottlenecks, we systematically diagnose failures in long-horizon mobile manipulation and identify three dominant regimes: task planning, navigation and base positioning, and local manipulation. Based on this diagnosis, we develop failure-guided agentic intervention that augments a fixed subtask VLA with demonstration-based planning guidance, adaptive visual memory, accessibility-aware base adjustment, and local end-effector adjustment. On RoboCasa365, these interventions progressively improve task success from 19% to 47%, with the finalized system reaching 49% on held-out episode seeds, compared with 18% for the baseline. The same design improves performance from 14% to 37% on BEHAVIOR-1K and from 5/20 to 13/20 on real-robot tasks. These results suggest that reliable mobile manipulation can be advanced by diagnosing and intervening on the current bottleneck, rather than uniformly scaling the underlying policy. Our code will be released at https://github.com/PKU-VaLuE-Lab/Cracking-Mobile-Manipulation.git.

## TL;DR

Recent vision-language-action (VLA) models have shown strong performance on local robot manipulation, yet their success does not readily translate to long-horizon mobile manipulation. In our experiments, a pretrained subtask VLA achieves 80% success rate on atomic manipulation tasks but only 19% when these skills are composed into mobile manipulation.

## Related
<!-- [[other-paper-citekey]] -->
