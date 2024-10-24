# Diver：利用跨度级互信息验证优化大型语言模型解码

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在解码策略上的改进，特别是通过引入点态互信息（PMI）分数来提升解码质量。这种研究侧重于理论层面的模型优化和算法创新，而不是直接的应用开发或Agent行为研究。因此，它更适合归类于LLM理论。` `机器学习`

> Diver: Large Language Model Decoding with Span-Level Mutual Information Verification

# 摘要

> 大型语言模型（LLMs）在接收特定任务指令时表现出色，但面对输入偏差时，标准解码策略往往力不从心。理想的LLM输出应忠实反映输入信息，这一点可通过点态互信息（PMI）分数来衡量。为此，我们创新性地提出了Diver方法，通过跨度级PMI验证提升LLM解码质量。在推理阶段，Diver首先定位可能产生多个候选跨度的偏差点，进而计算这些候选跨度对输入对数似然增益的影响，以确定PMI分数。最终，依据PMI重新排序的输出分布，选出最优跨度。实证研究表明，Diver在多个下游任务中，无论性能还是通用性，均显著超越现有解码技术。

> Large language models (LLMs) have shown impressive capabilities in adapting to various tasks when provided with task-specific instructions. However, LLMs using standard decoding strategies often struggle with deviations from the inputs. Intuitively, compliant LLM outputs should reflect the information present in the input, which can be measured by point-wise mutual information (PMI) scores. Therefore, we propose Diver, a novel approach that enhances LLM Decoding through span-level PMI verification. During inference, Diver first identifies divergence steps that may lead to multiple candidate spans. Subsequently, it calculates the PMI scores by assessing the log-likelihood gains of the input if the candidate spans are generated. Finally, the optimal span is selected based on the PMI re-ranked output distributions. We evaluate our method across various downstream tasks, and empirical results demonstrate that Diver significantly outperforms existing decoding methods in both performance and versatility.

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x1.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x2.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x3.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x4.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x5.png)

![Diver：利用跨度级互信息验证优化大型语言模型解码](../../../paper_images/2406.02120/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02120)