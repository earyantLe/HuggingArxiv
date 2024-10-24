# 以火攻火：ChatGPT 在源代码任务上的可信度究竟有多高？

发布时间：2024年05月21日

`Agent

这篇论文主要探讨了ChatGPT在多代理协作软件开发中的应用，其中ChatGPT既作为开发者又作为测试者，进行代码生成、补全及修复，并自我验证其工作。这种研究关注的是如何通过代理（Agent）的协作来提高软件开发的质量，特别是在代码验证方面的能力。因此，它属于Agent分类。` `软件开发` `人工智能`

> Fight Fire with Fire: How Much Can We Trust ChatGPT on Source Code-Related Tasks?

# 摘要

> 随着ChatGPT等大型语言模型在软件开发中的应用日益广泛，确保其生成的代码质量已成为关键。新近研究提出，让ChatGPT在多代理协作软件开发中既充当开发者又充当测试者。这种协作模式使ChatGPT能为其编写的代码生成测试报告，进而自我检查并修复错误。但这些研究未评估这些测试报告在验证代码上的实际效果。为此，我们开展了一项详尽的实证研究，旨在评估ChatGPT在代码生成、补全及修复中的自我验证能力。我们让ChatGPT（1）编写正确代码并自我验证其正确性；（2）完成无漏洞代码并自我检查漏洞；（3）修复问题代码并自我确认问题是否已解决。通过对两个代码生成数据集、一个代码补全数据集和两个程序修复数据集的分析，我们发现：（1）ChatGPT常误判其错误代码为正确；（2）其行为中出现自我矛盾的幻觉；（3）通过提出引导性问题，可增强其自我验证能力，这些问题涉及ChatGPT是否认同关于错误代码生成、修复及漏洞的断言；（4）尽管ChatGPT生成的测试报告能揭示更多代码漏洞，但对于错误代码和修复失败的解释往往不准确。基于这些发现，我们为ChatGPT的进一步研究和应用提供了方向。

> With the increasing utilization of large language models such as ChatGPT during software development, it has become crucial to verify the quality of code content it generates. Recent studies proposed utilizing ChatGPT as both a developer and tester for multi-agent collaborative software development. The multi-agent collaboration empowers ChatGPT to produce test reports for its generated code, enabling it to self-verify the code content and fix bugs based on these reports. However, these studies did not assess the effectiveness of the generated test reports in validating the code. Therefore, we conduct a comprehensive empirical investigation to evaluate ChatGPT's self-verification capability in code generation, code completion, and program repair. We request ChatGPT to (1) generate correct code and then self-verify its correctness; (2) complete code without vulnerabilities and then self-verify for the presence of vulnerabilities; and (3) repair buggy code and then self-verify whether the bugs are resolved. Our findings on two code generation datasets, one code completion dataset, and two program repair datasets reveal the following observations: (1) ChatGPT often erroneously predicts its generated incorrect code as correct. (2) The self-contradictory hallucinations in ChatGPT's behavior arise. (3) The self-verification capability of ChatGPT can be enhanced by asking the guiding question, which queries whether ChatGPT agrees with assertions about incorrectly generated or repaired code and vulnerabilities in completed code. (4) Using test reports generated by ChatGPT can identify more vulnerabilities in completed code, but the explanations for incorrectly generated code and failed repairs are mostly inaccurate in the test reports. Based on these findings, we provide implications for further research or development using ChatGPT.

[Arxiv](https://arxiv.org/abs/2405.12641)