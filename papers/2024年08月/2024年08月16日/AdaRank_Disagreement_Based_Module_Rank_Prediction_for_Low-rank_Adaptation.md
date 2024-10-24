# AdaRank：利用分歧进行模块排名预测，专为低秩适应设计

发布时间：2024年08月16日

`LLM理论` `人工智能` `机器学习`

> AdaRank: Disagreement Based Module Rank Prediction for Low-rank Adaptation

# 摘要

> 随着语言和多模态模型规模的不断增长，预训练通用基础模型并适应下游任务已成为标准做法。然而，面对庞大的模型规模，适应效率成为关键挑战，促使了如LoRA等高效微调方法的兴起。尽管研究表明微调后期层与预训练权重差异更大，LoRA仍普遍采用统一秩。借鉴特征学习和模块关键性的理论，我们创新性地提出基于模型分歧的技术来动态预测模块秩。实证显示，AdaRank在未见数据上表现更佳，且独特之处在于无需额外目标或正则化器，确保了预训练和适应阶段的完整性，从而提升了适应的准确性和性能。相关代码已公开于https://github.com/google-research/google-research/tree/master/adaptive_low_rank。

> With the rise of language and multimodal models of ever-increasing size, pretraining a general-purpose foundational model and adapting it to downstream tasks has become common practice. To this end, adaptation efficiency can be a critical bottleneck given the large model sizes, hence efficient finetuning methods such as LoRA have become prevalent. However, LoRA is typically applied with the same rank across all model layers, despite mounting evidence from transfer learning literature that during finetuning, later layers diverge more from pretrained weights. Inspired by the theory and observations around feature learning and module criticality, we develop a simple model disagreement based technique to predict the rank of a given module relative to the other modules. Empirically, AdaRank generalizes notably better on unseen data than using uniform ranks with the same number of parameters. Compared to prior work, AdaRank has the unique advantage of leaving the pretraining and adaptation stages completely intact: no need for any additional objectives or regularizers, which can hinder adaptation accuracy and performance. Our code is publicly available at https://github.com/google-research/google-research/tree/master/adaptive_low_rank.

[Arxiv](https://arxiv.org/abs/2408.09015)