# ConStat：大型语言模型中的性能驱动污染检测

发布时间：2024年05月25日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLM）的性能评估问题，特别是数据污染对模型性能评估的影响。论文提出了一种新的污染定义，并开发了一种统计方法（ConStat）来检测和量化这种污染。这些问题和方法论的探讨属于LLM的理论研究范畴，因为它们涉及到模型评估的基本原理和方法，而不是直接的应用或特定的模型实现。因此，这篇论文更适合归类于LLM理论。` `人工智能` `模型评估`

> ConStat: Performance-Based Contamination Detection in Large Language Models

# 摘要

> 公共基准对于评估大型语言模型至关重要，但数据污染可能导致性能虚高，影响模型比较的可靠性。为此，我们需要有效检测并评估污染对性能的影响。现有的检测方法存在漏洞，无法准确量化污染。鉴于此，我们提出了一种新的污染定义，将其视为非泛化的人工膨胀基准性能，而非简单的训练数据中包含基准样本。这一新视角使我们能够识别那些性能虚高的模型，即其性能无法泛化至改写样本、同分布合成样本或同一任务的其他基准。基于此，我们开发了ConStat，一种统计方法，通过比较主要基准与一组参考模型在参考基准上的性能，准确检测和量化污染。我们在广泛的实验中验证了ConStat的有效性，涵盖多种模型、基准及污染情况，并揭示了包括Mistral、Llama、Yi及Open LLM排行榜前三名在内的多个流行模型存在严重污染问题。

> Public benchmarks play an essential role in the evaluation of large language models. However, data contamination can lead to inflated performance, rendering them unreliable for model comparison. It is therefore crucial to detect contamination and estimate its impact on measured performance. Unfortunately, existing detection methods can be easily evaded and fail to quantify contamination. To overcome these limitations, we propose a novel definition of contamination as artificially inflated and non-generalizing benchmark performance instead of the inclusion of benchmark samples in the training data. This perspective enables us to detect any model with inflated performance, i.e., performance that does not generalize to rephrased samples, synthetic samples from the same distribution, or different benchmarks for the same task. Based on this insight, we develop ConStat, a statistical method that reliably detects and quantifies contamination by comparing performance between a primary and reference benchmark relative to a set of reference models. We demonstrate the effectiveness of ConStat in an extensive evaluation of diverse model architectures, benchmarks, and contamination scenarios and find high levels of contamination in multiple popular models including Mistral, Llama, Yi, and the top-3 Open LLM Leaderboard models.

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/devil.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/smile.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x1.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/warning.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/allok.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x2.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x3.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x4.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x5.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x6.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x7.png)

![ConStat：大型语言模型中的性能驱动污染检测](../../../paper_images/2405.16281/x8.png)

[Arxiv](https://arxiv.org/abs/2405.16281)