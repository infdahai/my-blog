---
title: 专题 · Zero-WAM(2608.26103) 全文精读：ICL 人类视频任务规格
description: 真正把 ICL 带入具身；人类视频做 in-context 任务规格；HumanGen 74.2K 对；IFP 目标；与 DreamZero 区分
tags: [专题, ZeroWAM, ICL, in-context, world-action, HumanGen, 人类视频, 精读]
created: 2026-08-30
feishu_wiki: https://huazhi-ai.feishu.cn/wiki/GRvow3LzYiuUerkP5g1cG09nnyf
feishu_docx: JvoqdqZ1EoA0hhxze8rcm8q4nl2
arxiv: 2608.26103
---

# 专题 · Zero-WAM(2608.26103) 全文精读：ICL 人类视频任务规格

> **论文**：✔ arXiv **2608.26103** · *Zero-WAM: In-Context World-Action Modeling from Human Videos for Open-Ended Task Generalization*（Robbyant + HKUST(GZ)/HKUST）  
> **站点**：https://robbyant-research.github.io/Zero-WAM/  
> **这是真正名为 "Zero-WAM" 的论文** —— 不要把本项目里的 DreamZero(2602.15922) 当成它。  
> **飞书**：主文档下子文档

---

## 0 · 一句话

**Zero-WAM = 把 LLM 的 in-context learning（ICL）范式整套搬到具身：用「人类视频」当任务规格(in-context prompt)，让策略零样本地执行从未训练过的操作任务——无需任何参数更新、无需该任务的机器人数据。**

**与 DreamZero 的本质区别**：
- DreamZero 的"zero-shot"靠**世界先验 + 条件化**，跨本体仍要 post-training（梯度）。
- **Zero-WAM 才是真 ICL**：跨任务泛化靠**部署时给一段人类视频**，训练时不需见过该任务，**完全不更新参数**。

---

## 1 · 问题：零样本跨任务泛化

- 具身核心挑战：策略要执行**训练中没见过的任务**，只用部署时可获得的信息。
- **ICL 视角**：LLM 里新任务只要在上下文里指明即可、不更新权重 → 泛化变成"**任务规格化**(task specification)"问题。
- **关键主张**：对操作来说，自然的任务规格不是语言，而是**人类视频** —— 它提供丰富的视觉线索，表达任务如何一步步演化。

---

## 2 · 方法

### 2.1 架构：因果视频-动作模型
- 输入：当前/历史观测 + **in-context 人类视频 prompt（或语言指令）**
- 输出：**预测未来机器人视频 + 可执行动作**
- 视频模型（Wan-2.2 初始化）+ 动作模型 联合。

### 2.2 HumanGen：自动构造人类-机器人 ICL 数据集（核心贡献）
**难题**：任务丰富的配对 human-robot 数据极稀缺。
**解法**：一个**自动流水线**，把"按任务采样的机器人轨迹"转成"语义匹配的人类视频"，产出 **HumanGen：74.2K human-robot ICL 对 / 8.6K 任务**。

### 2.3 IFP 目标（in-context future chunk prediction）
- 标准 next-chunk 预测常只靠**局部机器人历史**就能解（尤其见过的任务）→ 学到"捷径"。
- **IFP**：从当前机器人视频表征监督**多个 strided 的未来块**，逼策略**从人类视频 prompt 提取任务演化信息**，抑制捷径。

### 2.4 训练数据
- Task-diverse VA（video-action）预训练语料 + HumanGen ICL 对。

---

## 3 · 结果

- **RoboTwin 2.0 仿真**：7 个未见任务平均 **46.95%**，比最强 video-action 基线（LingBot-VA）**+29.5 绝对点**。
- **消融（Figure 5）**：逐个任务成功率，Zero-WAM 全面显著高于 WAN-Action / Lingot-VA / w/o pretrain。
- **真实世界**（人类视频引导）：
  - 三物体顺序操作：33.3% vs 基线 10.0%
  - 双桌腿细插入：Zero-WAM 成功（基线 0）—— **人类视频比语言更可靠地传达细粒度任务规格**

---

## 4 · ★ "ICL 这件事说明了什么" —— 本论文的完整论证

这是对上一轮"ICL 之辨"的**升级回答**（之前用 DreamZero 误答，现在用真正的 Zero-WAM）：

### 4.1 Zero-WAM 证明了 ICL 在具身的**可行性路径**
- **ICL 不是 LLM 专属**：把"任务 = 上下文"的抽象搬到操作，用**人类视频**作天然任务接口，可行。
- **ICL 的低数据红利**：只需部署时一段人类视频，无需该任务机器人数据/参数更新 → 这正是数据稀缺具身最需要的。

### 4.2 但 ICL 在具身的**数据要求是"配对"而非"海量原生"**
- 关键：HumanGen 是 **74.2K 对**(paired) 的 human-robot 数据 —— **ICL 的燃料是"人类视频 ↔ 机器人轨迹"的语义配对**，不是随便多少人类视频。
- → **你的「配对金标准(E)」数据哲学**在此得到正面印证：ICL 式具身泛化的前提是"跨本体语义对齐配对数据"。

### 4.3 ICL 在具身的**特定任务 = 任务规格化**
- IFP 目标的设计（抑制捷径、逼从视频提取任务）说明：**ICL 在具身的难题不是"会不会多任务"，而是"真从上下文拿任务信息，而非抄训练捷径"** —— 与 LLM ICL 的 shortcut 问题同构。

### 4.4 一句话总结
> **Zero-WAM 证明：ICL（人类视频作 in-context 任务规格）能让具身零样本地跨任务，且不需参数更新；它把泛化变成"任务规格化"问题，把数据要求变成"人类-机器人语义配对(paired)"。这既回答了 ICL 在具身可行，也划定了它的前提——它是一枚「配对金标准数据」的强证据。**

---

## 5 · 与其他文件的咬合

- **与 DreamZero(2602.15922)**：同是 WAM，但**立场相反**——DreamZero 靠预训练世界先验+条件化（跨本体要梯度），Zero-WAM 是真 ICL（跨任务靠 in-context 视频，0 参数更新）。两者合起来：**"世界先验(预训练) × ICL(任务接口)" 是两个正交杠杆**。
- **与 EgoVerse/人 EGO**：都主张"人类视频是可扩展任务信息源"；Zero-WAM 更进一步要**配对**human-robot。
- **与数据×训练**：HumanGen = **"如何把稀缺配对数据用自动管线放大(74.2K)"** —— 正是"数据供给"里配对金标准(E)的工程化。

---

## 6 · 局限（分析补）
- 聚焦**桌面 tabletop 操作**；移动/长时间跨任务未深入。
- 依赖 HumanGen 的**语义匹配质量**（自动管线转换可能引入不完美对齐）。
- 绝对成功率仍有限（尤其细插入），"video prompt → 精确动作"仍难。
- 未与"无需任何数据"的说法对标——仍是 74.2K 预训练 + 8.6K 任务的支撑。

## 7 · 口径
**Zero-WAM(2608.26103) 把 LLM 的 ICL 带入具身：以"人类视频"作部署时 in-context 任务规格，策略零参数更新地执行未见任务；用自动管线把机器人轨迹转成语义匹配人类视频得到 HumanGen(74.2K 对/8.6K 任务)，并用 IFP 目标抑制捷径逼模型真从视频取任务信息；RoboTwin 7 未见任务 46.95%(+29.5pt)，真机完成细插入等未见配置。它是"ICL 具身化"与"配对金标准数据"的强证据。**

## 8 · 关联
DreamZero(区分) · EgoVerse(人数据) · 数据×训练(配对E) · EgoWAM(世界表示) · ovideo-action 基线(WAN/LingBot)
