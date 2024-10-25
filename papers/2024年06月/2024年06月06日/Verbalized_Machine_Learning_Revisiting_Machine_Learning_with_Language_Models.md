# 语言模型视角下的机器学习再探：口头化机器学习

发布时间：2024年06月06日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在机器学习中的理论应用，提出了一个名为口头化机器学习（VML）的新框架。该框架通过将参数限制在人类可理解的自然语言范围内，重新定义了机器学习中的经典问题如回归和分类。这种创新的方法不仅涉及LLMs的理论应用，还强调了透明度和解释性，这些都是理论研究的重要方面。因此，这篇论文更适合归类于LLM理论。` `机器学习`

> Verbalized Machine Learning: Revisiting Machine Learning with Language Models

# 摘要

> 受大型语言模型（LLMs）显著进展的启发，我们提出了口头化机器学习（VML）框架。与传统模型在连续参数空间上优化不同，VML将参数限制在人类可理解的自然语言范围内。这一创新视角使得带有文本提示的LLM可视为由文本提示定义的函数。基于此，我们重新审视了回归和分类等经典问题，发现它们能通过LLM驱动的学习与优化解决。VML的显著优势有三：一是先验知识与假设能以自然语言形式轻松融入学习过程；二是优化器能根据数据和先验知识自动选择并调整模型；三是优化过程的每一步都有LLM提供的解释，增强了透明度。我们通过多项研究验证了VML的实效，并期待它成为提升机器学习解释性与信任度的关键一步。

> Motivated by the large progress made by large language models (LLMs), we introduce the framework of verbalized machine learning (VML). In contrast to conventional machine learning models that are typically optimized over a continuous parameter space, VML constrains the parameter space to be human-interpretable natural language. Such a constraint leads to a new perspective of function approximation, where an LLM with a text prompt can be viewed as a function parameterized by the text prompt. Guided by this perspective, we revisit classical machine learning problems, such as regression and classification, and find that these problems can be solved by an LLM-parameterized learner and optimizer. The major advantages of VML include (1) easy encoding of inductive bias: prior knowledge about the problem and hypothesis class can be encoded in natural language and fed into the LLM-parameterized learner; (2) automatic model class selection: the optimizer can automatically select a concrete model class based on data and verbalized prior knowledge, and it can update the model class during training; and (3) interpretable learner updates: the LLM-parameterized optimizer can provide explanations for why each learner update is performed. We conduct several studies to empirically evaluate the effectiveness of VML, and hope that VML can serve as a stepping stone to stronger interpretability and trustworthiness in ML.

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x1.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x2.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x3.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x4.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x5.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x6.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x7.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x8.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x9.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x10.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x11.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x12.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x13.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x14.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x15.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x16.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x17.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x18.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x19.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x20.png)

![语言模型视角下的机器学习再探：口头化机器学习](../../../paper_images/2406.04344/x21.png)

[Arxiv](https://arxiv.org/abs/2406.04344)