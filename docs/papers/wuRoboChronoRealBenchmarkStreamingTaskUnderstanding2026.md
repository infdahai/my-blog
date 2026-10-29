---
citekey: "wuRoboChronoRealBenchmarkStreamingTaskUnderstanding2026"
title: "RoboChrono: A Real Robot Benchmark for Streaming Task Understanding"
authors: ["Yuzhou Wu", "Longteng Fan", "Zimeng Li", "Yu Wanchan", "Ting Zhang", "Yiyang Ma", "Shihao Li", "Wei Ying", "Jianbin Qin", "Jiajian Jing", "Fangwen Chen", "Yifan Wu", "Zichen Zhang", "Ruiqi Yang", "Weibin Kong", "Yihang Xu", "Haoran Liu", "Zonghang He", "Xuyang Liu", "YiFan Xiong", "Siteng Huang", "Tao Xu", "Zhuo Xu", "Long Chen", "Ruoxiang Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36605"
doi: "10.48550/arXiv.2609.36605"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# RoboChrono: A Real Robot Benchmark for Streaming Task Understanding

> Yuzhou Wu, Longteng Fan, Zimeng Li, Yu Wanchan, Ting Zhang, Yiyang Ma, Shihao Li, Wei Ying, Jianbin Qin, Jiajian Jing, Fangwen Chen, Yifan Wu, Zichen Zhang, Ruiqi Yang, Weibin Kong, Yihang Xu, Haoran Liu, Zonghang He, Xuyang Liu, YiFan Xiong, Siteng Huang, Tao Xu, Zhuo Xu, Long Chen, Ruoxiang Li · 2026
> [arXiv](https://arxiv.org/abs/2609.36605) · [PDF](https://arxiv.org/pdf/2609.36605)

## Abstract

Understanding ongoing robot manipulation requires models to interpret visual observations in relation to interaction history and task progress. We introduce RoboChrono, a benchmark for streaming task understanding comprising 39 scenarios and 34,713 evaluation instances, constructed from real robot executions and complementary bare-hand human recordings. The benchmark evaluates seven tasks grouped into recognition, alignment, and temporal grounding, covering action understanding and anticipation, visual correspondence, temporal ordering, and action localization. Zero-shot evaluation of 18 vision-language models reveals substantial differences across tasks. GPT-6-Astra achieves 98.3% accuracy on Frame Matching but 68.3% on Frame Ordering, while RynnBrain1.1-122B-A10B exhibits a larger gap, reaching 95.4% and 32.9%, respectively. Input ablations on matched questions with five open-weight models further reveal distinct dependencies on visual evidence: removing visual observations reduces Current Action Recognition accuracy by 22.1 percentage points, whereas Next Action Prediction decreases by only 0.7 points. These findings show that strong visual matching does not consistently coincide with strong temporal ordering, and suggest that next-action prediction can be supported by task and action priors even when visual evidence is unavailable. RoboChrono provides a diagnostic setting for examining these differences, highlighting the need for capability-specific evaluation beyond aggregate scores when assessing task understanding in robot manipulation.

## TL;DR

Understanding ongoing robot manipulation requires models to interpret visual observations in relation to interaction history and task progress. We introduce RoboChrono, a benchmark for streaming task understanding comprising 39 scenarios and 34,713 evaluation instances, constructed from real robot executions and complementary bare-hand human recordings.

## Related
<!-- [[other-paper-citekey]] -->
