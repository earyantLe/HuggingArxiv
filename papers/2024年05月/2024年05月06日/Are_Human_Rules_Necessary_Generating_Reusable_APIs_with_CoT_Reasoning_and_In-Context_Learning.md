# 人类规则真有必要吗？借助 CoT 推理与上下文学习，我们能够生成可复用的 API。

发布时间：2024年05月06日

`LLM应用` `软件开发`

> Are Human Rules Necessary? Generating Reusable APIs with CoT Reasoning and In-Context Learning

# 摘要

> 本文提出了Code2API，一种创新的方法，旨在自动化地为Stack Overflow上的代码片段实现API化。该方法无需额外训练模型或手工制定规则，便于个人电脑部署，且不依赖外部工具。Code2API利用精心构造的提示，引导大型语言模型生成结构化的API。通过思维链推理和少量样本的上下文学习，我们激发了模型的知识和逻辑推理能力，使其能够逐步深入理解并解决API化任务，模仿开发者的思维方式。在性能评估中，Code2API在识别方法参数和返回语句的准确度上分别达到了65%和66%，超越了当前领先技术APIzator的15.0%和16.5%。用户研究进一步显示，Code2API在生成富有意义的方法名称上超越了APIzator，甚至达到了超越人类表现的水平，开发者更倾向于使用我们方法生成的API，这凸显了我们工具在实际应用中的潜力。此外，我们将框架成功扩展至Python数据集，并在Java上实现了相似的性能，证明了我们工具的泛化能力。

> Inspired by the great potential of Large Language Models (LLMs) for solving complex coding tasks, in this paper, we propose a novel approach, named Code2API, to automatically perform APIzation for Stack Overflow code snippets. Code2API does not require additional model training or any manual crafting rules and can be easily deployed on personal computers without relying on other external tools. Specifically, Code2API guides the LLMs through well-designed prompts to generate well-formed APIs for given code snippets. To elicit knowledge and logical reasoning from LLMs, we used chain-of-thought (CoT) reasoning and few-shot in-context learning, which can help the LLMs fully understand the APIzation task and solve it step by step in a manner similar to a developer. Our evaluations show that Code2API achieves a remarkable accuracy in identifying method parameters (65%) and return statements (66%) equivalent to human-generated ones, surpassing the current state-of-the-art approach, APIzator, by 15.0% and 16.5% respectively. Moreover, compared with APIzator, our user study demonstrates that Code2API exhibits superior performance in generating meaningful method names, even surpassing the human-level performance, and developers are more willing to use APIs generated by our approach, highlighting the applicability of our tool in practice. Finally, we successfully extend our framework to the Python dataset, achieving a comparable performance with Java, which verifies the generalizability of our tool.

[Arxiv](https://arxiv.org/abs/2405.03509)