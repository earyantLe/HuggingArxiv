# SQL-GEN：借助合成数据与模型融合，跨越文本转SQL的方言鸿沟
发布时间：2024年08月22日

`代码编写`
> SQL-GEN: Bridging the Dialect Gap for Text-to-SQL Via Synthetic Data And Model Merging
>
> Text-to-SQL 系统在 SQLite 方言上取得了显著进展，但适应其他方言如 BigQuery 和 PostgreSQL 仍具挑战。为此，我们推出了 SQL-GEN 框架，通过方言特定教程生成高质量合成数据，有效支持多方言训练数据集的创建。该方法性能提升高达 20%，并缩小了与人工标注数据集的差距。结合合成与人工标注数据，性能再提升 3.3% 至 5.6%。此外，我们创新的专家混合（MoE）初始化方法，通过整合自注意力层和方言关键词，进一步优化了跨方言性能。
>
> https://arxiv.org/abs/2408.12733

**如遇无法添加，请+ vx: iamxxn886**
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/dialect_specific_queries.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/data_generation_pipeline.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/MoE.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/sample_filtering.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/keyword_dist.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/MoE-baseline.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/Our-MoE.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/template_expansion.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12733/sample_generation_example.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.12733](https://arxiv.org/abs/2408.12733)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)