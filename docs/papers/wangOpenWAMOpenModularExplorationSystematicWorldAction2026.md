---
title: OpenWAM：系统化 World-Action Model 预训练的开源模块化探索
description: 把 WAM 预训练变成受控实验程序；分拆 Infra/后端/架构/信息流/推理/数据，提炼"继承什么、世界与动作如何交互、如何缩放"三问与三原则；OpenWAM-α 在 ~6400h EGO+真机数据上训出跨仿真/真机领先 WAM
tags: [WAM, world-action-model, EGO, 预训练, 开源, 具身, 数据×训练, Infra]
year: 2026
arxiv: 2609.07398
created: 2026-09-08
feishu_wiki: https://huazhi-ai.feishu.cn/wiki/UbR0wzaYsiOUs4kc9VzczCgqnLc
feishu_docx: FrKvdm2qloBVM3xJyLlcTMWcnPh
---

# OpenWAM：系统化 World-Action Model 预训练的开源模块化探索

> **一句话**：与其继续堆一个"黑盒 WAM"，不如把 WAM 预训练拆成可控实验，回答三个问题——继承什么、世界与动作学习如何交互、协同如何缩放——并据此训出跨仿真到真机都领先的开放 WAM。

## 核心思想
World-Action Model（WAM）从**视频生成先验**继承世界知识，再经**具身经验**把它导向可执行的控制信号。但现有 WAM 是**单体（monolithic）**：生成主干、视觉表征、架构、信息流、推理过程、训练数据全部紧耦合，无法看清"哪个设计选择重要、为什么"。
OpenWAM 把 WAM 预训练变成**受控实验程序（controlled experimental program）**，用模块化开放栈做系统化探索。

## 三个层次
- **OpenWAM-Infra**：把 WAM 设计空间**分解成可组合模块**，统一训练 / 推理 / 部署 / 评测——这正是一条完整的 Infra 闭环（训练→评测→部署）。
- **OpenWAM-Study**：用受控实验回答三问，并蒸馏出三条原则。
- **OpenWAM-α**：把原则组装成一个开放预训练模型（≈6400 小时 EGO 人 + 真机数据），跨 8 个仿真 benchmark 与真实机器人评测。

## 三问 → 三原则（Study）
| 问题 | 原则 |
|------|------|
| **继承什么** | 上游知识通过**足够强的生成主干 + 紧凑且信息丰富的潜空间**迁移 |
| **世界与世界/动作如何交互** | 世界-动作协同需要**专用动作容量 + 显式的世界→动作信息流 + 同步联合去噪** |
| **协同如何缩放** | 具身预训练主要提升**域外泛化**；egocentric 与 robot 数据**单阶段共训**同时获得世界覆盖与动作接地 |

## 为什么重要（真洞察）
1. **把 WAM 从"玄学堆料"变成可归因的系统工程**：分清哪些模块真正决定性能，是这波 WAM 热里稀缺的"可解释基建"。
2. **可复现 + 开放**：Infra、评测协议、预训练模型、数据配方**全量开源**——直接可作团队自建 WAM/数据引擎的对标底座。
3. **EGO + 真机构成一条数据配方**：6400h 单阶段共训，正好验证本项目"EGO 海量预训练 + 真机金标准精调"的四层栈内核。

## 局限 · 下一步
- 结论建立在单一实现族（同一 Infra）上，跨栈外部效度待考。
- 6400h 规模相对"互联网级"仍小，缩放律边界未知。
- 可跟进：OpenWAM 能否直接接本项目 `HIL/SERL` 的在线精调，形成"开放预训练 → 真机在线更优"的闭环验证。

## 关键链接
- arXiv: https://arxiv.org/abs/2609.07398
- 作者：Yuran Wang, Siqiao Huang, et al.（Hang Zhao / Lin Shao / Hao Dong 等）
