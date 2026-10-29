---
citekey: "chengEvoDexBenchBenchmarkingGeneralizationRelatedTasksDexterousManipulation2026"
title: "Evo-DexBench: Benchmarking Generalization across Related Tasks for Dexterous Manipulation"
authors: ["Bing Cheng", "Yiran Mao", "Zewei Ye", "Yifan Jin", "Xinyi Chen", "Ruifeng Tu", "Shuhuai Wang", "Tao Lin", "Zhimu Zhou", "Yuxin Du", "Fangwei Zhong", "Junchi Yan", "Bo Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.21180"
doi: "10.48550/arXiv.2610.21180"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# Evo-DexBench: Benchmarking Generalization across Related Tasks for Dexterous Manipulation

> Bing Cheng, Yiran Mao, Zewei Ye, Yifan Jin, Xinyi Chen, Ruifeng Tu, Shuhuai Wang, Tao Lin, Zhimu Zhou, Yuxin Du, Fangwei Zhong, Junchi Yan, Bo Zhao · 2026
> [arXiv](https://arxiv.org/abs/2610.21180) · [PDF](https://arxiv.org/pdf/2610.21180)

## Abstract

General-purpose dexterous manipulation requires policies to transfer knowledge from related tasks to new tasks with only a few target demonstrations. Existing benchmarks often provide too many target demonstrations. They also leave the differences between source and target tasks uncontrolled. As a result, they cannot clearly distinguish knowledge transfer from task memorization. Our key insight is the Core-Gen principle. Core tasks are related tasks that share a functional interaction and provide source knowledge, while a Gen task is a novel target within the same functional family that has only a few demonstrations. This setup tests whether a policy can reuse functional interaction knowledge. Based on this principle, we propose Evo-DexBench, which controls both source-task relatedness and target-task exposure. It comprises 30 tasks in six functional families and a VR teleoperation pipeline. The resulting dataset covers three everyday scenes per task. It contains 1,248 multimodal demonstrations collected with simulated Shadow Hands equipped with 123 taxels. Experiments show that even the best-performing method achieves an average success rate of only 38.5%, highlighting the challenges existing methods face in transferring functional interaction knowledge. Further analysis shows that, across the two tasks, joint Core+Gen training improves performance by 12% and 38%, respectively, over training on Core followed by fine-tuning on Gen. This indicates that joint training makes better use of Core knowledge and that functionally matched Core data yields greater gains in success rate than mismatched data. We release the Evo-DexBench dataset and benchmark to support the evaluation of dexterous manipulation policies' generalization across related tasks.

## TL;DR

General-purpose dexterous manipulation requires policies to transfer knowledge from related tasks to new tasks with only a few target demonstrations. Existing benchmarks often provide too many target demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
