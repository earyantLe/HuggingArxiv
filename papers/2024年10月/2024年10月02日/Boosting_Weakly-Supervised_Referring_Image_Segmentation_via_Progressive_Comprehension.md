# 逐步理解，提升弱监督引用图像分割

发布时间：2024年10月02日

`LLM应用` `计算机视觉`

> Boosting Weakly-Supervised Referring Image Segmentation via Progressive Comprehension

# 摘要

> 本文探讨了弱监督指代图像分割 (WRIS) 问题，特别关注从图像-文本对中直接学习目标定位的挑战。我们发现，输入文本通常已包含定位目标的详细信息，而人类识别目标时往往采用逐步理解的方式。为此，我们提出了渐进理解网络 (PCNet)，通过利用文本中的目标相关线索逐步定位目标。具体来说，我们先用大型语言模型 (LLM) 将文本分解为短语，这些短语作为线索分阶段输入到条件指代模块 (CRM) 中，以更新文本嵌入并增强定位响应图。我们还提出了区域感知收缩 (RaS) 损失，确保视觉定位从粗到细逐步进行。最后，通过实例感知消歧 (IaD) 损失，区分同一图像上不同文本生成的重叠响应图，减少定位歧义。实验证明，我们的方法在三个基准上均优于现有最先进技术。

> This paper explores the weakly-supervised referring image segmentation (WRIS) problem, and focuses on a challenging setup where target localization is learned directly from image-text pairs. We note that the input text description typically already contains detailed information on how to localize the target object, and we also observe that humans often follow a step-by-step comprehension process (\ie, progressively utilizing target-related attributes and relations as cues) to identify the target object. Hence, we propose a novel Progressive Comprehension Network (PCNet) to leverage target-related textual cues from the input description for progressively localizing the target object. Specifically, we first use a Large Language Model (LLM) to decompose the input text description into short phrases. These short phrases are taken as target-related cues and fed into a Conditional Referring Module (CRM) in multiple stages, to allow updating the referring text embedding and enhance the response map for target localization in a multi-stage manner. Based on the CRM, we then propose a Region-aware Shrinking (RaS) loss to constrain the visual localization to be conducted progressively in a coarse-to-fine manner across different stages. Finally, we introduce an Instance-aware Disambiguation (IaD) loss to suppress instance localization ambiguity by differentiating overlapping response maps generated by different referring texts on the same image. Extensive experiments show that our method outperforms SOTA methods on three common benchmarks.

[Arxiv](https://arxiv.org/abs/2410.01544)