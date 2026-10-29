---
citekey: "yanWhatMattersQualityAwareVLAPretrainingBenchmarkEmpirical2026"
title: "What Matters in Quality-Aware VLA Pretraining: A Benchmark and Empirical Study"
authors: ["Mingxuan Yan", "Litian Gong", "Dihong Huang", "Zhixu Li", "Tianyu Zhang", "Wenqian Zhang", "Hefeifei Jiang", "Peihao Li", "Jian Zhang", "Mengfei Zhao", "Yikai Tang", "Hai Zhai", "Zehao Wang", "Ruijian Liang", "Yanjia Huang", "Lin Shao", "Changliu Liu", "Kaiyu Hang", "Zhiwen Fan", "Masayoshi Tomizuka", "Jianfei Yang", "Jiachen Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.18869"
doi: "10.48550/arXiv.2610.18869"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# What Matters in Quality-Aware VLA Pretraining: A Benchmark and Empirical Study

> Mingxuan Yan, Litian Gong, Dihong Huang, Zhixu Li, Tianyu Zhang, Wenqian Zhang, Hefeifei Jiang, Peihao Li, Jian Zhang, Mengfei Zhao, Yikai Tang, Hai Zhai, Zehao Wang, Ruijian Liang, Yanjia Huang, Lin Shao, Changliu Liu, Kaiyu Hang, Zhiwen Fan, Masayoshi Tomizuka, Jianfei Yang, Jiachen Li · 2026
> [arXiv](https://arxiv.org/abs/2610.18869) · [PDF](https://arxiv.org/pdf/2610.18869)

## Abstract

How should demonstration quality be used during vision-language-action (VLA) pretraining to improve performance after target-task fine-tuning? We compare weighting, filtering, and conditioning across reward definitions and label granularities using 5,000 naturally suboptimal human demonstrations and 24 target tasks. Within each VLA, we match demonstrations and training budgets. Additional comparisons examine pretraining data size and the roles of quality tags during fine-tuning and inference. Across three VLAs, we find that approach-aware episode conditioning improves mean success over plain behavioral cloning; conditioning and filtering favor episode and chunk labels, respectively, on average, with model-dependent reversals; and constant-tag fine-tuning improves mean success after conditioned pretraining with either tagged or untagged inference. We introduce AXIS-Bench to support these controlled comparisons. Built on crowdsourced simulation demonstrations, it provides recorded object and contact states for recomputing quality labels on shared trajectories. Replayable trajectories support workspace-aligned rendering and user-defined real-world target tasks. In our real-world experiment, simulation pretraining raises success from 9.6\% to 31.7\%. Project page: https://axis-bench.github.io/.

## TL;DR

How should demonstration quality be used during vision-language-action (VLA) pretraining to improve performance after target-task fine-tuning? We compare weighting, filtering, and conditioning across reward definitions and label granularities using 5,000 naturally suboptimal human demonstrations and 24 target tasks.

## Related
<!-- [[other-paper-citekey]] -->
