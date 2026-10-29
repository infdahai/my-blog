---
citekey: "yuLearningFleetExperienceCollectiveExperienceLearning962026"
title: "Learning from Fleet Experience: Collective Experience Learning Across 96 Robots"
authors: ["Chao Yu", "Shu'ang Yu", "Hao Lin", "Hongzhi Zang", "Yuxiang Yan", "Chenxi Jiang", "Zhen Guo", "Chuankang Li", "Yihao Chen", "Xin Xu", "Xu Fu", "Jiakai Zhou", "Liangzhi Shi", "Hongyi Ren", "Yiwei Liu", "Jing Wu", "Yuanqing Wang", "Chen Wu", "Bo Dai", "Chunyu Yang", "Hongliang Huang", "Shuoyu Yue", "Weiqi Yin", "Yinuo Chen", "Ruihua Chen", "Chunyang Zhu", "Han Xiao", "Yanghao Li", "Ruipu Wu", "Zhikai Cai", "Xiu Chen", "Xu Tan", "Si Liu", "Yuchen Yan", "Jialin Zhang", "Wen Zeng", "Yiming Zhou", "Zixiao Huang", "Xinlei Chen", "Guanghui Ren", "Quanlu Zhang", "Boxun Li", "Maoqing Yao", "Yu Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.25736"
doi: "10.48550/arXiv.2610.25736"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Learning from Fleet Experience: Collective Experience Learning Across 96 Robots

> Chao Yu, Shu'ang Yu, Hao Lin, Hongzhi Zang, Yuxiang Yan, Chenxi Jiang, Zhen Guo, Chuankang Li, Yihao Chen, Xin Xu, Xu Fu, Jiakai Zhou, Liangzhi Shi, Hongyi Ren, Yiwei Liu, Jing Wu, Yuanqing Wang, Chen Wu, Bo Dai, Chunyu Yang, Hongliang Huang, Shuoyu Yue, Weiqi Yin, Yinuo Chen, Ruihua Chen, Chunyang Zhu, Han Xiao, Yanghao Li, Ruipu Wu, Zhikai Cai, Xiu Chen, Xu Tan, Si Liu, Yuchen Yan, Jialin Zhang, Wen Zeng, Yiming Zhou, Zixiao Huang, Xinlei Chen, Guanghui Ren, Quanlu Zhang, Boxun Li, Maoqing Yao, Yu Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.25736) · [PDF](https://arxiv.org/pdf/2610.25736)

## Abstract

Robot deployment generates experience that can support policy improvement, but continued reliance on expert corrective actions makes learning difficult to scale across growing fleets. We propose learning from fleet experience: using deployed robots' own executions as a source of supervision for further policy improvement. We call this paradigm Collective Experience Learning (CEL), in which robots pool execution experience to update a shared policy that returns to the fleet. Following expert-supervised initialization, we realize CEL through failure-guided experience retrieval fine-tuning (FERT). FERT uses failure contexts to retrieve relevant segments from successful trajectories and prioritizes their recorded actions for supervised updates, without collecting additional expert demonstrations or corrective actions. Operators provide binary episode-outcome labels and environment resets. A fault-tolerant asynchronous training system (FATS) coordinates robot execution, cloud inference and policy optimization despite local interruptions. Across five real-world manipulation tasks, the resulting policies achieve success rates of 93.3-99.2%, evaluated over 120 trials per task on robots excluded from training data collection. With collection time per robot held fixed, larger fleets provide more experience and generally improve performance across the evaluated sizes. On multi-stage phone packaging, learning with 96 robots raises success from 79.2% to 98.3%. These results support CEL as a scalable approach to improving robot policy reliability through experience generated during deployment.

## TL;DR

Robot deployment generates experience that can support policy improvement, but continued reliance on expert corrective actions makes learning difficult to scale across growing fleets. We propose learning from fleet experience: using deployed robots' own executions as a source of supervision for further policy improvement.

## Related
<!-- [[other-paper-citekey]] -->
