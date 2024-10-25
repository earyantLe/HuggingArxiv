# LLM 助力文本模拟攻击，直指无身份推荐系统

发布时间：2024年09月18日

`LLM应用` `网络安全` `推荐系统`

> LLM-Powered Text Simulation Attack Against ID-Free Recommender Systems

# 摘要

> 无ID推荐范式旨在解决传统推荐系统在处理冷启动用户或新ID项目时的局限性。然而，研究发现，这种系统易受新型文本模拟攻击（TextSimu）的影响，该攻击通过模拟流行项目的特征，利用大型语言模型（LLM）推广特定目标项目。TextSimu在黑盒和白盒环境中均有效，依赖于流行度提取模块和N-persona一致性模拟策略。为应对这类攻击，我们探索了检测LLM生成推广文本的方法。实验证明，TextSimu比现有攻击更具威胁性，但我们的防御方法能有效识别其生成的恶意文本。通过揭示这一漏洞，我们希望推动更强大无ID推荐系统的发展。

> The ID-free recommendation paradigm has been proposed to address the limitation that traditional recommender systems struggle to model cold-start users or items with new IDs. Despite its effectiveness, this study uncovers that ID-free recommender systems are vulnerable to the proposed Text Simulation attack (TextSimu) which aims to promote specific target items. As a novel type of text poisoning attack, TextSimu exploits large language models (LLM) to alter the textual information of target items by simulating the characteristics of popular items. It operates effectively in both black-box and white-box settings, utilizing two key components: a unified popularity extraction module, which captures the essential characteristics of popular items, and an N-persona consistency simulation strategy, which creates multiple personas to collaboratively synthesize refined promotional textual descriptions for target items by simulating the popular items. To withstand TextSimu-like attacks, we further explore the detection approach for identifying LLM-generated promotional text. Extensive experiments conducted on three datasets demonstrate that TextSimu poses a more significant threat than existing poisoning attacks, while our defense method can detect malicious text of target items generated by TextSimu. By identifying the vulnerability, we aim to advance the development of more robust ID-free recommender systems.

[Arxiv](https://arxiv.org/abs/2409.11690)