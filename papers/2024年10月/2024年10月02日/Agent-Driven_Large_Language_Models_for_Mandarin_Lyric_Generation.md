# 基于代理的大型语言模型助力普通话歌词创作

发布时间：2024年10月02日

`LLM应用` `人工智能`

> Agent-Driven Large Language Models for Mandarin Lyric Generation

# 摘要

> 生成式大型语言模型展现了卓越的上下文学习能力，只需简单提示即可应对多种任务。然而，以往的旋律到歌词研究因高质量数据稀缺和创造性标准模糊而受限。当前，多数研究聚焦于通用主题或情感，这在语言模型能力提升的背景下显得价值有限。在普通话等音调语言中，音高受旋律和音调双重影响，歌词与旋律的匹配度因此变化。我们的研究通过 Mpop600 数据集证实，词曲作者在创作时确实考虑了这种匹配。为此，我们设计了一个多智能体系统，将任务细分为韵律、音节数、对齐和一致性等子任务。通过基于扩散的歌唱声音合成器进行听力测试，评估了不同智能体组生成的歌词质量。

> Generative Large Language Models have shown impressive in-context learning abilities, performing well across various tasks with just a prompt. Previous melody-to-lyric research has been limited by scarce high-quality aligned data and unclear standard for creativeness. Most efforts focused on general themes or emotions, which are less valuable given current language model capabilities. In tonal contour languages like Mandarin, pitch contours are influenced by both melody and tone, leading to variations in lyric-melody fit. Our study, validated by the Mpop600 dataset, confirms that lyricists and melody writers consider this fit during their composition process. In this research, we developed a multi-agent system that decomposes the melody-to-lyric task into sub-tasks, with each agent controlling rhyme, syllable count, lyric-melody alignment, and consistency. Listening tests were conducted via a diffusion-based singing voice synthesizer to evaluate the quality of lyrics generated by different agent groups.

[Arxiv](https://arxiv.org/abs/2410.01450)