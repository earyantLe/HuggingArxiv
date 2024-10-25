# Reefknot：多模态大型语言模型中关系幻觉问题的全方位基准，涵盖评估、分析与缓解。

发布时间：2024年08月18日

`LLM应用` `人工智能` `计算机视觉`

> Reefknot: A Comprehensive Benchmark for Relation Hallucination Evaluation, Analysis and Mitigation in Multimodal Large Language Models

# 摘要

> 当前多模态大型语言模型（MLLMs）饱受幻觉问题之苦，尤其是那些需要高级推理能力的关系幻觉，而现有研究对此关注不足。为此，我们推出了Reefknot基准，聚焦于关系幻觉，包含超过20,000个真实场景样本。我们系统定义了关系幻觉，并利用Visual Genome数据集构建了真实分布的语义三元组。评估显示，MLLMs在处理关系幻觉上存在显著不足。为此，我们提出了一种基于信心的缓解策略，有效降低了幻觉率。我们期待这些成果能推动多模态智能的信任度提升。相关数据集和代码将在论文接受后公开。

> Hallucination issues persistently plagued current multimodal large language models (MLLMs). While existing research primarily focuses on object-level or attribute-level hallucinations, sidelining the more sophisticated relation hallucinations that necessitate advanced reasoning abilities from MLLMs. Besides, recent benchmarks regarding relation hallucinations lack in-depth evaluation and effective mitigation. Moreover, their datasets are typically derived from a systematic annotation process, which could introduce inherent biases due to the predefined process. To handle the aforementioned challenges, we introduce Reefknot, a comprehensive benchmark specifically targeting relation hallucinations, consisting of over 20,000 samples derived from real-world scenarios. Specifically, we first provide a systematic definition of relation hallucinations, integrating perspectives from perceptive and cognitive domains. Furthermore, we construct the relation-based corpus utilizing the representative scene graph dataset Visual Genome (VG), from which semantic triplets follow real-world distributions. Our comparative evaluation across three distinct tasks revealed a substantial shortcoming in the capabilities of current MLLMs to mitigate relation hallucinations. Finally, we advance a novel confidence-based mitigation strategy tailored to tackle the relation hallucinations problem. Across three datasets, including Reefknot, we observed an average reduction of 9.75% in the hallucination rate. We believe our paper sheds valuable insights into achieving trustworthy multimodal intelligence. Our dataset and code will be released upon paper acceptance.

[Arxiv](https://arxiv.org/abs/2408.09429)