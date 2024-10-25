# OpenMathInstruct-2：借助海量开源指令数据，加速数学 AI 的发展。

发布时间：2024年10月02日

`LLM应用` `人工智能`

> OpenMathInstruct-2: Accelerating AI for Math with Massive Open-Source Instruction Data

# 摘要

> 数学推理在LLM开发中仍是一个重大挑战，但因数据访问受限，许多前沿进展已转为闭源。这阻碍了研究人员探究不同数据处理方式的影响。为此，我们利用\texttt{Llama3.1}系列模型，精心设计了数据合成实验，发现：（a）简洁的解决方案格式更优，（b）强教师模型生成的数据胜过弱学生模型，（c）SFT能容忍低质量数据，（d）问题多样性至关重要。基于这些发现，我们构建了包含14M对问题-解决方案的OpenMathInstruct-2数据集，规模是之前开源数据集的近八倍。实验表明，使用该数据集微调的\texttt{Llama-3.1-8B-Base}在MATH任务上提升了15.9\%。为推动开源发展，我们公开了相关代码、模型及数据集。

> Mathematical reasoning continues to be a critical challenge in large language model (LLM) development with significant interest. However, most of the cutting-edge progress in mathematical reasoning with LLMs has become \emph{closed-source} due to lack of access to training data. This lack of data access limits researchers from understanding the impact of different choices for synthesizing and utilizing the data. With the goal of creating a high-quality finetuning (SFT) dataset for math reasoning, we conduct careful ablation experiments on data synthesis using the recently released \texttt{Llama3.1} family of models. Our experiments show that: (a) solution format matters, with excessively verbose solutions proving detrimental to SFT performance, (b) data generated by a strong teacher outperforms \emph{on-policy} data generated by a weak student model, (c) SFT is robust to low-quality solutions, allowing for imprecise data filtering, and (d) question diversity is crucial for achieving data scaling gains. Based on these insights, we create the OpenMathInstruct-2 dataset, which consists of 14M question-solution pairs ($\approx$ 600K unique questions), making it nearly eight times larger than the previous largest open-source math reasoning dataset. Finetuning the \texttt{Llama-3.1-8B-Base} using OpenMathInstruct-2 outperforms \texttt{Llama3.1-8B-Instruct} on MATH by an absolute 15.9\% (51.9\% $\rightarrow$ 67.8\%). Finally, to accelerate the open-source efforts, we release the code, the finetuned models, and the OpenMathInstruct-2 dataset under a commercially permissive license.

[Arxiv](https://arxiv.org/abs/2410.01560)