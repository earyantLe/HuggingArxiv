# B4：通过合理测试，迈向代码解决方案的最佳评估

发布时间：2024年09月13日

`LLM应用` `软件开发` `人工智能`

> B4: Towards Optimal Assessment of Plausible Code Solutions with Plausible Tests

# 摘要

> 在代码生成中，从多个方案中挑选最佳解决方案至关重要，这通常依赖于开发者编写的测试用例。然而，可靠的测试用例难得且昂贵，因此研究者们转向自动生成测试用例。但当代码和测试都看似合理却不可靠时，选择最佳方案变得棘手。尽管已有启发式策略，但其理论基础薄弱，最优选择策略的存在仍未解。我们的研究在两方面突破：首先，在贝叶斯框架下，我们基于解决方案与测试间的通过状态后验概率定义了最优策略，并将其转化为整数规划问题。其次，我们提出了一种高效近似方法，确保误差受限于先验知识的准确性。通过整合有效先验知识，我们的策略在理论与实践中均超越现有启发式方法，尤其在LLM生成的代码与测试中，表现尤为突出，相对最强启发式和随机选择，分别提升50%和246%。代码已公开于 https://github.com/ZJU-CTAG/B4。

> Selecting the best code solution from multiple generated ones is an essential task in code generation, which can be achieved by using some reliable validators (e.g., developer-written test cases) for assistance. Since reliable test cases are not always available and can be expensive to build in practice, researchers propose to automatically generate test cases to assess code solutions. However, when both code solutions and test cases are plausible and not reliable, selecting the best solution becomes challenging. Although some heuristic strategies have been proposed to tackle this problem, they lack a strong theoretical guarantee and it is still an open question whether an optimal selection strategy exists. Our work contributes in two ways. First, we show that within a Bayesian framework, the optimal selection strategy can be defined based on the posterior probability of the observed passing states between solutions and tests. The problem of identifying the best solution is then framed as an integer programming problem. Second, we propose an efficient approach for approximating this optimal (yet uncomputable) strategy, where the approximation error is bounded by the correctness of prior knowledge. We then incorporate effective prior knowledge to tailor code generation tasks. Both theoretical and empirical studies confirm that existing heuristics are limited in selecting the best solutions with plausible test cases. Our proposed approximated optimal strategy B4 significantly surpasses existing heuristics in selecting code solutions generated by large language models (LLMs) with LLM-generated tests, achieving a relative performance improvement by up to 50% over the strongest heuristic and 246% over the random selection in the most challenging scenarios. Our code is publicly available at https://github.com/ZJU-CTAG/B4.

[Arxiv](https://arxiv.org/abs/2409.08692)