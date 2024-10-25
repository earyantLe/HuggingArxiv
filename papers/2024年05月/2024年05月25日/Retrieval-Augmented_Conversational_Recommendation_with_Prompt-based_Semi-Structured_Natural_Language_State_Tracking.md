# 基于提示的半结构化自然语言状态跟踪，增强检索以优化对话推荐系统

发布时间：2024年05月25日

`RAG

理由：这篇论文介绍了一种基于大型语言模型（LLMs）的检索增强型对话状态跟踪技术（RA-Rec），专门为对话推荐系统设计。这种技术利用LLMs来理解用户的复杂偏好和意图，并通过半结构化的对话状态跟踪来增强推荐系统的性能。因此，它属于RAG分类，即检索增强生成（Retrieval-Augmented Generation），这是一种利用LLMs进行信息检索和生成的应用。` `对话推荐系统` `用户体验`

> Retrieval-Augmented Conversational Recommendation with Prompt-based Semi-Structured Natural Language State Tracking

# 摘要

> 对话推荐系统需理解用户通过间接方式表达的丰富多样的偏好和意图，如“我在控制体重”，这使得检索相关项目颇具挑战，尤其是依赖不完整或过时的元数据时。幸运的是，许多领域的丰富评论不仅覆盖标准元数据，还提供了与用户兴趣相契合的深入见解，如“适合约会的优雅场所”。近期，大型语言模型（LLMs）的发展让我们得以揭示用户偏好表达与用户评论中复杂语言间的常识联系。LLMs还推动了半结构化对话状态跟踪、复杂意图与偏好理解以及推荐、解释和问答生成的新模式。我们因此推出了RA-Rec，一种基于LLM的检索增强型对话状态跟踪技术，专为对话推荐系统设计，并通过视频、开源GitHub仓库和交互式Google Colab笔记本进行展示。

> Conversational recommendation (ConvRec) systems must understand rich and diverse natural language (NL) expressions of user preferences and intents, often communicated in an indirect manner (e.g., "I'm watching my weight"). Such complex utterances make retrieving relevant items challenging, especially if only using often incomplete or out-of-date metadata. Fortunately, many domains feature rich item reviews that cover standard metadata categories and offer complex opinions that might match a user's interests (e.g., "classy joint for a date"). However, only recently have large language models (LLMs) let us unlock the commonsense connections between user preference utterances and complex language in user-generated reviews. Further, LLMs enable novel paradigms for semi-structured dialogue state tracking, complex intent and preference understanding, and generating recommendations, explanations, and question answers. We thus introduce a novel technology RA-Rec, a Retrieval-Augmented, LLM-driven dialogue state tracking system for ConvRec, showcased with a video, open source GitHub repository, and interactive Google Colab notebook.

![基于提示的半结构化自然语言状态跟踪，增强检索以优化对话推荐系统](../../../paper_images/2406.00033/x1.png)

![基于提示的半结构化自然语言状态跟踪，增强检索以优化对话推荐系统](../../../paper_images/2406.00033/x2.png)

[Arxiv](https://arxiv.org/abs/2406.00033)