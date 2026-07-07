---
title: Social Information Quality and Environmental Volatility Shape Collective Foraging Behavior
title_zh: 社会信息质量和环境波动塑造集体觅食行为
authors: "Chirkov, V., Kurvers, R. H. J. M., Deffner, D., Romanczuk, P."
date: 2026-06-26
pdf: "https://www.biorxiv.org/content/10.1101/2025.11.14.688412v3.full.pdf"
tags: ["query:lbm"]
score: 7.0
evidence: 多智能体强化学习用于觅食路径规划
tldr: 集体觅食需平衡个体探索与社会信息利用，但社会信息质量与环境波动性的交互影响未知。本研究使用多智能体强化学习模型，让智能体在随机探索、个体追踪和社会吸引间选择，并系统改变资源波动性和社会线索类型。结果表明，低质量社会线索（如位置）在稳定环境中有效但环境波动时失败；高质量社会线索（如收益）使智能体选择性模仿，灵活调整策略。研究揭示信息质量与生态背景的交互是集体行为涌现的重要机制。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究社会信息质量与环境波动性如何共同塑造集体觅食行为。
method: 使用多智能体强化学习模型，智能体在随机探索、个体追踪和社会吸引间选择，系统改变资源波动性与社会线索类型。
result: 低质量社会线索在稳定环境有效但脆弱，高质量社会线索促进行为多样性，灵活适应环境波动。
conclusion: 信息质量与生态背景的交互是集体行为涌现的关键机制。
---

## 摘要
集体觅食在动物界中广泛存在，使动物能更有效地发现资源。然而，集体觅食者需要在私有探索与使用社会信息之间平衡关键的权衡。社会信息可以以非常不同的形式出现，从简单的位置线索到复杂的收益信息。然而，可用的社会线索类型和环境波动如何塑造集体觅食行为尚不完全清楚。我们通过一个空间显式模型来解决这个问题，其中智能体通过多智能体强化学习追踪移动资源。智能体在随机探索、私有追踪和社会吸引之间进行选择。我们系统性地改变了资源波动性和可用社会线索的类型，以分析它们对个体和集体行为的影响。结果表明，社会信息的质量决定了涌现的集体行为。低质量的社会线索（如位置、动作）导致一种脆弱的策略，该策略在稳定环境中有效，但随着波动性增加而失效。相反，高质量的社会信息（如收益）能够产生行为多样性：智能体选择性模仿他人，并根据环境波动灵活地在个体追踪或探索之间切换。我们的发现揭示了信息质量与生态背景之间的相互作用，是支配从个体决策规则中涌现出不同形式集体行为的重要机制。

## Abstract
Collective foraging is widespread across the animal kingdom, allowing animals to more effectively discover resources. However, collective foragers need to balance a key trade off between private exploration and using social information. Social information can come in very distinct forms, ranging from simple positional cues to complex payoff information. However, how the types of available social cues and environmental volatility shape collective foraging behavior is not well understood. We address this using a spatially-explicit model in which agents track a mobile resource via multi-agent reinforcement learning. Agents choose between random exploration, private tracking, and social attraction. We systematically varied resource volatility and the type of available social cues to analyze their effect on individual and collective behavior. Our results show that the quality of social information dictates the emerging collective behavior. Low-quality social cues (e.g., positions, actions) result in a fragile strategy that is effective in stable environments but fails as volatility increases. Conversely, high-quality social information (e.g., payoffs) enables behavioral diversity: Agents selectively copy others and flexibly change between individual tracking or exploration depending on the environmental volatility. Our findings identify the interplay between information quality and ecological context as an important mechanism governing the emergence of distinct forms of collective behavior from individual decision rules.