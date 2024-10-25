# HalluVault：一个创新的基于逻辑编程的变异测试框架，专为发现大型语言模型中与事实相悖的幻觉现象而设计。

发布时间：2024年05月01日

`LLM应用` `软件测试`

> HalluVault: A Novel Logic Programming-aided Metamorphic Testing Framework for Detecting Fact-Conflicting Hallucinations in Large Language Models

# 摘要

> 大型语言模型（LLMs）重塑了语言处理的领域，却在安全性、隐私保护以及避免生成内容上的幻觉——即那些貌似合理却与事实不符的输出——方面遭遇重重挑战。特别棘手的是事实冲突幻觉（FCH），在这种情况下，LLMs产出的内容与已知事实直接相悖。应对FCH的挑战颇为艰巨，主要原因有两个：首先，自动化构建和更新基准数据集存在难度，因为现有方法依赖的静态基准无法涵盖FCH的各种情况。其次，验证LLMs输出的推理过程极为复杂，尤其是在涉及复杂逻辑关系时。为应对这些难题，我们提出了一种创新的逻辑编程方法，以增强变异测试，从而检测FCH。该方法从维基百科等来源搜集数据，通过逻辑推理扩展，生成多样化的测试案例，并通过结构化提示对LLMs进行评估，同时利用语义感知机制来验证它们的一致性。我们的方法在六个不同领域的LLMs上生成测试案例并检测幻觉，发现幻觉率在24.7%到59.8%之间。关键的观察结果显示，LLMs在处理时间概念、管理分布外知识以及逻辑推理能力方面存在挑战。这些结果凸显了我们工具生成的基于逻辑的测试案例在触发和识别幻觉方面的有效性，并强调了社区持续合作以检测和解决LLM幻觉问题的必要性。

> Large language models (LLMs) have transformed the landscape of language processing, yet struggle with significant challenges in terms of security, privacy, and the generation of seemingly coherent but factually inaccurate outputs, commonly referred to as hallucinations. Among these challenges, one particularly pressing issue is Fact-Conflicting Hallucination (FCH), where LLMs generate content that directly contradicts established facts. Tackling FCH poses a formidable task due to two primary obstacles: Firstly, automating the construction and updating of benchmark datasets is challenging, as current methods rely on static benchmarks that don't cover the diverse range of FCH scenarios. Secondly, validating LLM outputs' reasoning process is inherently complex, especially with intricate logical relations involved.
  In addressing these obstacles, we propose an innovative approach leveraging logic programming to enhance metamorphic testing for detecting Fact-Conflicting Hallucinations (FCH). Our method gathers data from sources like Wikipedia, expands it with logical reasoning to create diverse test cases, assesses LLMs through structured prompts, and validates their coherence using semantic-aware assessment mechanisms. Our method generates test cases and detects hallucinations across six different LLMs spanning nine domains, revealing hallucination rates ranging from 24.7% to 59.8%. Key observations indicate that LLMs encounter challenges, particularly with temporal concepts, handling out-of-distribution knowledge, and exhibiting deficiencies in logical reasoning capabilities. The outcomes underscore the efficacy of logic-based test cases generated by our tool in both triggering and identifying hallucinations. These findings underscore the imperative for ongoing collaborative endeavors within the community to detect and address LLM hallucinations.

[Arxiv](https://arxiv.org/abs/2405.00648)