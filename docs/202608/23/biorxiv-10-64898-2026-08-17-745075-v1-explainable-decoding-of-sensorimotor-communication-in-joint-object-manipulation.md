---
title: Explainable Decoding of Sensorimotor Communication in Joint Object Manipulation
title_zh: 联合物体操作中感觉运动通信的可解释解码
authors: "Liu, Y., Verdel, D., Leib, R., Burdet, E., Franklin, D. W."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.17.745075v1.full.pdf"
tags: ["query:intent-avoid"]
score: 6.0
evidence: 基于多模态感觉运动信号的多智能体意图解码
tldr: 人类在联合物体操作中常面临信息不对称，例如两人抬桌时仅一人知道目的地，他们需借助运动学、相互作用力和物体状态进行无声沟通。现有方法难以解释这些信号的上下文依赖含义。本文提出可解释机器学习框架，解码实时多模态信号中的意图，并量化各特征的信息量；将解码结果输入漂移扩散模型，可准确预测不知情伙伴的目标选择和决策时间。研究揭示了人类通过行动沟通的原理，为协作机器人通过物理交互推断和表达意图提供了设计原则。
source: biorxiv
selection_source: fresh_fetch
motivation: 联合操作中信息不对称时，人类依赖运动学和触觉线索沟通，但其含义依赖于上下文，难以刻画。
method: 提出可解释机器学习框架，解码多模态信号中的意图并量化特征贡献，再集成漂移扩散模型预测决策。
result: 解码信号准确预测不知情伙伴的目标选择与决策时间，并识别出关键信息特征。
conclusion: 揭示行动沟通机制，为协作机器人通过物理交互推断和表达意图提供原则。
---

## 摘要
人类经常在信息不对称的情况下协作，例如当两个人搬桌子而只有一个人知道目的地时。他们无需言语，利用运动学、交互力和物体状态的线索进行协调。表征这种感觉运动通信是困难的，因为这些信号既执行任务又传递信息，其含义依赖于上下文。在这里，我们研究了一个虚拟搬桌子任务，其中一方知道目标，而另一方从视觉-触觉反馈中推断目标。参与者灵活地调整运动学和触觉线索以适应上下文来传达意图。我们引入了一个可解释的机器学习框架，从持续的多模态信号中解码意图，并量化个体特征在何处提供信息。将解码信号整合到漂移扩散模型中，可以准确预测不知情伙伴的目标选择及决策时间。总之，我们的框架解释了人类如何通过行动进行沟通，并为协作机器人通过物理交互推断和表达意图提供了原则。

## Abstract
Humans often collaborate under asymmetric information, for example when two people carry a table and only one knows the destination. They coordinate without speech using cues from movement kinematics, interaction forces, and object states. Characterizing this sensorimotor communication is difficult because these signals both execute the task and convey information, whose meaning is context-dependent. Here, we investigated a virtual table-carrying task where one partner knew the target while the other inferred it from visuo-haptic feedback. Participants flexibly adapted kinematic and haptic cues across contexts to convey intention. We introduce an explainable machine-learning framework that decodes intent from ongoing multimodal signals and quantifies where individual features are informative. Incorporating the decoded signals into a drift-diffusion model accurately predicted the uninformed partner's target choices and decision times. Together, our framework explains how humans communicate through action and offers principles for collaborative robots to infer and express intent through physical interaction.