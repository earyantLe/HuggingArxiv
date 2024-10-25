# 无监督文本表示学习：通过指令调优实现零-shot密集检索

发布时间：2024年09月24日

`RAG` `信息检索`

> Unsupervised Text Representation Learning via Instruction-Tuning for Zero-Shot Dense Retrieval

# 摘要

> 密集检索系统常用于信息检索，但依赖于昂贵或难以获取的标签数据进行监督建模。我们提出了一种新颖的无监督文本表示学习方法，通过指令调整预训练的大型语言模型，在双编码器框架下生成合成查询，增强语料库表示。实验结果显示，我们的方法在低资源环境下显著提升了检索性能，超越了多个竞争模型，且模型尺寸更小。

> Dense retrieval systems are commonly used for information retrieval (IR). They rely on learning text representations through an encoder and usually require supervised modeling via labelled data which can be costly to obtain or simply unavailable. In this study, we introduce a novel unsupervised text representation learning technique via instruction-tuning the pre-trained encoder-decoder large language models (LLM) under the dual-encoder retrieval framework. We demonstrate the corpus representation can be augmented by the representations of relevant synthetic queries generated by the instruct-tuned LLM founded on the Rao-Blackwell theorem. Furthermore, we effectively align the query and corpus text representation with self-instructed-tuning. Specifically, we first prompt an open-box pre-trained LLM to follow defined instructions (i.e. question generation and keyword summarization) to generate synthetic queries. Next, we fine-tune the pre-trained LLM with defined instructions and the generated queries that passed quality check. Finally, we generate synthetic queries with the instruction-tuned LLM for each corpora and represent each corpora by weighted averaging the synthetic queries and original corpora embeddings. We evaluate our proposed method under low-resource settings on three English and one German retrieval datasets measuring NDCG@10, MRR@100, Recall@100. We significantly improve the average zero-shot retrieval performance on all metrics, increasing open-box FLAN-T5 model variations by [3.34%, 3.50%] in absolute and exceeding three competitive dense retrievers (i.e. mDPR, T-Systems, mBART-Large), with model of size at least 38% smaller, by 1.96%, 4.62%, 9.52% absolute on NDCG@10.

[Arxiv](https://arxiv.org/abs/2409.16497)