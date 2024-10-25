# 驾驭多模态大型语言模型，实现多模态序列推荐

发布时间：2024年08月19日

`LLM应用` `推荐系统` `多模态数据`

> Harnessing Multimodal Large Language Models for Multimodal Sequential Recommendation

# 摘要

> 大型语言模型在推荐系统领域展现出巨大潜力，现有研究多聚焦于将用户行为日志转化为文本提示，并利用提示调优技术使模型适用于推荐任务。同时，多模态推荐系统通过融合图像、文本等数据，为仅依赖文本信息的推荐范式带来新挑战。尽管多模态大型语言模型已能处理多模态输入，但其多模态推荐能力仍待探索。为此，我们提出多模态大型语言模型增强的序列多模态推荐模型 (MLLM-MSR)，通过两阶段用户偏好总结方法捕捉动态偏好，并利用监督微调技术使模型适用于多模态推荐任务。在多个数据集上的评估显示，MLLM-MSR 能有效捕捉并适应用户偏好的动态变化。

> Recent advances in Large Language Models (LLMs) have demonstrated significant potential in the field of Recommendation Systems (RSs). Most existing studies have focused on converting user behavior logs into textual prompts and leveraging techniques such as prompt tuning to enable LLMs for recommendation tasks. Meanwhile, research interest has recently grown in multimodal recommendation systems that integrate data from images, text, and other sources using modality fusion techniques. This introduces new challenges to the existing LLM-based recommendation paradigm which relies solely on text modality information. Moreover, although Multimodal Large Language Models (MLLMs) capable of processing multi-modal inputs have emerged, how to equip MLLMs with multi-modal recommendation capabilities remains largely unexplored. To this end, in this paper, we propose the Multimodal Large Language Model-enhanced Sequential Multimodal Recommendation (MLLM-MSR) model. To capture the dynamic user preference, we design a two-stage user preference summarization method. Specifically, we first utilize an MLLM-based item-summarizer to extract image feature given an item and convert the image into text. Then, we employ a recurrent user preference summarization generation paradigm to capture the dynamic changes in user preferences based on an LLM-based user-summarizer. Finally, to enable the MLLM for multi-modal recommendation task, we propose to fine-tune a MLLM-based recommender using Supervised Fine-Tuning (SFT) techniques. Extensive evaluations across various datasets validate the effectiveness of MLLM-MSR, showcasing its superior ability to capture and adapt to the evolving dynamics of user preferences.

[Arxiv](https://arxiv.org/abs/2408.09698)