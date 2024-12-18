# HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力

发布时间：2024年03月18日

`LLM应用` `社交媒体` `内容审核`

> HateCOT: An Explanation-Enhanced Dataset for Generalizable Offensive Speech Detection via Large Language Models

# 摘要

> 社交媒体的广泛使用催生了对有害内容准确高效检测的需求，以减轻其负面影响。在此背景下，众多用于识别有害内容的数据集和模型应运而生，但它们在处理“有害内容”界定差异及数据集标注不一的问题时，常常难以实现良好的泛化能力。本文推出了 HateCOT 数据集，包含 52000 个源自多样化现有资源的样本，其中的解释部分由 GPT-3.5-Turbo 和人工精心筛选编纂而成。研究显示，基于 HateCOT 预训练的有害内容检测模型，在面对跨领域和任务差异时，能在零样本和小样本环境下显著提升三大基准数据集上开源语言模型的表现。更进一步，HateCOT 数据集还能助力模型在资源匮乏的情况下实现有效的 K 小样本微调。

> The ubiquitousness of social media has led to the need for reliable and efficient detection of offensive content to limit harmful effects. This has led to a proliferation of datasets and models related to detecting offensive content. While sophisticated models have attained strong performance on individual datasets, these models often do not generalize due to differences between how "offensive content" is conceptualized, and the resulting differences in how these datasets are labeled. In this paper, we introduce HateCOT, a dataset of 52,000 samples drawn from diverse existing sources with explanations generated by GPT-3.5-Turbo and human-curated. We show that pre-training models for the detection of offensive content on HateCOT significantly boots open-sourced Language Models on three benchmark datasets in both zero and few-shot settings, despite differences in domain and task.} We further find that HateCOT enables effective K-shot fine-tuning in the low-resource settings.

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/gpt_template.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/zero_shot.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/indomain_finetune.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/icl.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/qa_heatmap.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/prompt_template.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/qa1.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/qa2.png)

![HateCOT 数据集：针对大型语言模型，提供丰富解释以提升对各类攻击性言论检测的泛化能力](../../../paper_images/2403.11456/qa3.png)

[Arxiv](https://arxiv.org/abs/2403.11456)