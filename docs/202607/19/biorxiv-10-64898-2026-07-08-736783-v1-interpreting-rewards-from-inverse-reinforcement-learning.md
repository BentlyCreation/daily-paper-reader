---
title: Interpreting Rewards from Inverse Reinforcement Learning
title_zh: 逆向强化学习中的奖励解释
authors: "Chow, J., Yang, Y., Laschowski, B."
date: 2026-07-13
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.08.736783v1.full.pdf"
tags: ["query:lbm"]
score: 6.0
evidence: 多智能体交互中的逆强化学习；从行为中学习潜在动机
tldr: 逆强化学习虽能恢复行为背后的奖励函数，但解释其含义仍是理解智能决策的难题。为此，提出了一个集成奖励函数分析、潜在模式分配与短历史行为分析的新框架，并用切换逆强化学习在多智能体社交交互数据上验证。结果将潜在模式解读为谨慎与易变两种动机轮廓，揭示了奖励函数中的行为动态。该框架为逆向工程和解释智能行为中的潜在奖励提供了有效途径。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1854, \"height\": 299, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1843, \"height\": 709, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1768, \"height\": 768, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1769, \"height\": 859, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1781, \"height\": 627, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-006.webp\", \"caption\": \"\", \"page\": 0, \"index\": 6, \"width\": 1821, \"height\": 867, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-007.webp\", \"caption\": \"\", \"page\": 0, \"index\": 7, \"width\": 1779, \"height\": 1264, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-08-736783-v1/fig-008.webp\", \"caption\": \"\", \"page\": 0, \"index\": 8, \"width\": 1780, \"height\": 622, \"label\": \"Figure\"}]"
motivation: 逆强化学习可恢复奖励函数，但难以解释其背后的动机，影响对智能行为的理解。
method: 提出结合奖励函数分析、潜在模式分配与短历史行为分析的框架，并用切换逆强化学习实证。
result: 框架将恢复的奖励函数中的潜在模式解释为谨慎与易变的动机轮廓。
conclusion: 该框架为逆向工程和解释潜在奖励提供了有前景的方法。
---

## 摘要
逆向强化学习可以从观察到的行为中恢复奖励函数，但解释这些奖励仍然是理解智能行为和决策的基本挑战。为解决这一挑战，我们引入了一个新的奖励解释框架，该框架结合了奖励函数分析、潜在模式分配和短历史行为分析，以推断潜在动机和行为动态。作为概念验证，我们使用切换逆向强化学习在一个大规模多智能体社交互动数据集上实例化了该框架。我们的框架将学习到的潜在模式解释为谨慎和易变的动机特征，表明恢复的奖励函数可以揭示行为动态的独特模式。更广泛地说，这些发现表明，所提出的框架为逆向工程和解释智能行为与决策背后的潜在奖励提供了一种有前景的方法。

## Abstract
Inverse reinforcement learning can recover reward functions from observed behavior, but interpreting those rewards remains a fundamental challenge for understanding intelligent behavior and decision-making. To address this challenge, we introduce a novel framework for reward interpretation that combines reward-function analysis, latent mode assignments, and short-history behavioral analysis to infer latent motivations and behavioral dynamics. As a proof-of-concept, we instantiated the framework using switching inverse reinforcement learning on a large-scale dataset of multi-agent social interactions. Our framework interpreted the learned latent modes as  cautious and  volatile motivational profiles, demonstrating that recovered reward functions can reveal distinct patterns of behavioral dynamics. More broadly, these findings suggest that the proposed framework provides a promising approach for reverse-engineering and interpreting latent rewards underlying intelligent behavior and decision-making.