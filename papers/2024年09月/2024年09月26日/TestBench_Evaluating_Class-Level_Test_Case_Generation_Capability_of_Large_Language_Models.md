# TestBench：评估大型语言模型在类级别测试用例的生成能力

发布时间：2024年09月26日

`LLM应用` `软件开发` `软件测试`

> TestBench: Evaluating Class-Level Test Case Generation Capability of Large Language Models

# 摘要

> 软件测试是软件开发中的关键环节，有助于识别风险并降低维护成本。随着大型语言模型（LLM）的发展，基于 LLM 的软件测试技术，尤其是测试用例生成技术，日益增多。然而，对 LLM 在此任务中的实际能力评估仍显不足。本文中，我们推出了 TestBench，一个针对 LLM 类级测试用例生成的基准。我们收集了来自 GitHub 上 9 个大型项目的 108 个 Java 程序，涵盖不同主题领域。我们设计了三种提示类型：自包含、完整和简单上下文。此外，我们提出了一个细粒度评估框架，涵盖测试用例的五个维度：语法、编译、测试正确性、代码覆盖率和缺陷检测率。我们还提出了一种启发式算法来修复 LLM 生成的错误测试用例。我们在 TestBench 上测试了 CodeLlama-13b、GPT-3.5 和 GPT-4，结果显示，大型模型能更好地利用上下文信息，生成更高质量的测试用例。而小型模型在处理完整上下文中的大量信息时可能遇到困难，但使用简化上下文后，性能显著提升。我们的研究不仅展示了当前进展，还为未来通过优化上下文处理来提升测试用例生成模型的效果指明了方向。

> Software testing is a crucial phase in the software life cycle, helping identify potential risks and reduce maintenance costs. With the advancement of Large Language Models (LLMs), researchers have proposed an increasing number of LLM-based software testing techniques, particularly in the area of test case generation. Despite the growing interest, limited efforts have been made to thoroughly evaluate the actual capabilities of LLMs in this task.
  In this paper, we introduce TestBench, a benchmark for class-level LLM-based test case generation. We construct a dataset of 108 Java programs from 9 real-world, large-scale projects on GitHub, each representing a different thematic domain. We then design three distinct types of prompts based on context descriptions, including self-contained context, full context, and simple context. Besides, we propose a fine-grained evaluation framework that considers five aspects of test cases: syntactic correctness, compilation correctness, test correctness, code coverage rate, and defect detection rate. Furthermore, we propose a heuristic algorithm to repair erroneous test cases generated by LLMs. We evaluate CodeLlama-13b, GPT-3.5, and GPT-4 on the TestBench, and our experimental results indicate that larger models demonstrate a greater ability to effectively utilize contextual information, thus generating higher-quality test cases. Smaller models may struggle with the noise introduced by the extensive information contained within the full context. However, when using the simplified version, namely the simple context, which is derived from the full context via abstract syntax tree analysis, the performance of these models improves significantly. Our analysis highlights the current progress and pinpoints future directions to further enhance the effectiveness of models by handling contextual information for test case generation.

[Arxiv](https://arxiv.org/abs/2409.17561)