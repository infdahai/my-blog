








---
citekey: "kimOpenVLAOpenSourceVisionLanguageAction2024a"
title: "OpenVLA: An Open-Source Vision-Language-Action Model"
authors: ["Moo Jin Kim", "Karl Pertsch", "Siddharth Karamcheti", "Ted Xiao", "Ashwin Balakrishna", "Suraj Nair", "Rafael Rafailov", "Ethan Foster", "Grace Lam", "Pannag Sanketi", "Quan Vuong", "Thomas Kollar", "Benjamin Burchfiel", "Russ Tedrake", "Dorsa Sadigh", "Sergey Levine", "Percy Liang", "Chelsea Finn"]
year: 2024
venue: ""
url: ""
doi: "10.48550/arXiv.2406.09246"
zotero_select: "zotero://select/library/items/LDLVZQB9"
tags: [paper, embodied-ai, "Computer Science - Machine Learning", "Computer Science - Robotics"]
status: unread   # unread | reading | done
rating:          # 1-5
created: 2026-04-23
---

# OpenVLA: An Open-Source Vision-Language-Action Model

> Moo Jin Kim, Karl Pertsch, Siddharth Karamcheti, Ted Xiao, Ashwin Balakrishna, Suraj Nair, Rafael Rafailov, Ethan Foster, Grace Lam, Pannag Sanketi, Quan Vuong, Thomas Kollar, Benjamin Burchfiel, Russ Tedrake, Dorsa Sadigh, Sergey Levine, Percy Liang, Chelsea Finn · 2024
> [Open in Zotero](zotero://select/library/items/LDLVZQB9)

## TL;DR
<!-- 一句话总结 -->

## Problem
<!-- 论文要解决什么问题？为什么重要？ -->

## Method
<!-- 核心方法、关键设计、与已有工作的差异 -->

## Results
<!-- 主要实验、关键指标、消融发现 -->

## My Notes
<!-- 个人批注：值得借鉴的点、存疑、与具身智能场景的关联 -->

## Highlights & Annotations
%% begin annotations %%


### Imported on 2026-04-23 16:22

> Addressing these challenges, we introduce OpenVLA, a 7B-parameter open-source VLA trained on a diverse collection of 970k real-world robot demonstrations. (p. 1)

**Note:** 用 Dinov2&&SigLIP混合的 视觉编码器，将图片输入编码器后，映射到文本空间，和任务的文本信息一起输入到 llama2 模型进行训练。


> Yet, there are two key reasons preventing the widespread use of existing VLAs: 1) current models [1, 7, 17, 18] are closed, with limited visibility into model architecture, training procedures, and data mixture, and 2) existing works do not provide best practices for deploying and adapting VLAs to new robots, environments, and tasks — especially on commodity hardware (e.g., consumer-grade GPUs). (p. 2)


**Note:** 这里说的是两个关键问题：

1. 模型闭源。
2. 部署和调试到新机器人的能力很差（和硬件绑定。）


> simpler “patch-as-token” approach (p. 3)


**Note:** 把 action 
做成 词表的 token


> Unlike these works, OpenVLA adopts a more end-to-end approach, directly fine-tuning VLMs to generate robot actions by treating them as tokens in the language model vocabulary. (p. 3)


> re often referred to as vision-language-action models (VLAs), since they fuse robot control actions directly into VLM backbones. (p. 3)


**Note:** 之前的模型，只
把图片做成 token


> (1) a visual encoder that maps image inputs to a number of “image patch embeddings”, (2) a projector that takes the output embeddings of the visual encoder and maps them into the input space of a language model, and (3) a large language model (LLM) backbone. (p. 4)


> Prismatic uses a two-part visual encoder, (p. 4)


> r improved spatial reasoning (p. 4)


**Note:** 用数万亿数据堆出来的三个顶级开源模型（Llama2 + SigLIP + DINOv2），通过一个两层的网络（MLP）强行缝合，再用 100 万条指令数据进行微调，最终炼成了懂物理空间、能听懂人话的 Prismatic-7B。


> we discretize each dimension of the robot actions separately into one of 256 bins. (p. 5)


> we set the bin width to uniformly divide the interval between the 1st and 99th quantile of the actions in the training data. (p. 5)


**Note:** 多目标上, llava 表现的更好


> aVA demonstrated stronger language grounding in tasks that involved multiple objects in the scene and required the policy to manipulate the correct object, (p. 6)


> We compared VLAs with 224 × 224px and 384 × 384px inputs, but found no performance difference in our evaluations, while the latter takes 3x longer to train. We thus opt for a resolution of 224 × 224px for the final OpenVLA model. Note that on many VLM benchmarks, increased resolution does improve performance [44, 86, 87], but we did not see this trend (yet) for VLAs. (p. 6)


**Note:** 高帧率图片
未必效果更好



%% end annotations %%

## Zotero Notes

Comment: Website: https://openvla.github.io/


## Related
<!-- [[other-paper-citekey]] -->


%% Import Date: 2026-04-23T16:22:47.547+08:00 %%
