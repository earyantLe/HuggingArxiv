# 探索模型合并技术在低资源语言中的应用潜力

发布时间：2024年07月04日

`LLM应用` `人工智能` `语言技术`

> Unlocking the Potential of Model Merging for Low-Resource Languages

# 摘要

> 将 LLM 适应新语言通常采用持续预训练后进行监督微调的方式。但在低资源语言中，这种先预训练再微调的方法难以平衡语言建模与任务解决能力。为此，我们提出模型合并策略，无需额外训练即可将不同能力的模型融合，为低资源语言打造任务解决型 LLM。基于 Llama-2-7B 的实验显示，模型合并在数据极度匮乏的情况下，仍能有效提升 LLM 的任务解决能力，超越传统预训练加微调的方法。我们还发现，随着训练令牌增加，模型合并性能趋于饱和，因此引入松弛变量优化合并算法，减少关键参数损失，进一步提升性能。我们期待模型合并能以更高的数据效率，助力更多数据稀缺的语言。

> Adapting large language models (LLMs) to new languages typically involves continual pre-training (CT) followed by supervised fine-tuning (SFT). However, this CT-then-SFT approach struggles with limited data in the context of low-resource languages, failing to balance language modeling and task-solving capabilities. We thus propose model merging as an alternative for low-resource languages, combining models with distinct capabilities into a single model without additional training. We use model merging to develop task-solving LLMs for low-resource languages without SFT data in the target languages. Our experiments based on Llama-2-7B demonstrate that model merging effectively endows LLMs for low-resource languages with task-solving abilities, outperforming CT-then-SFT in scenarios with extremely scarce data. Observing performance saturation in model merging with more training tokens, we further analyze the merging process and introduce a slack variable to the model merging algorithm to mitigate the loss of important parameters, thereby enhancing performance. We hope that model merging can benefit more human languages suffering from data scarcity with its higher data efficiency.

![探索模型合并技术在低资源语言中的应用潜力](../../../paper_images/2407.03994/x1.png)

![探索模型合并技术在低资源语言中的应用潜力](../../../paper_images/2407.03994/x2.png)

[Arxiv](https://arxiv.org/abs/2407.03994)