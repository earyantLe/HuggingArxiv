# 针对可驾驶区域检测的任务导向预训练

发布时间：2024年09月30日

`LLM理论` `自动驾驶`

> Task-Oriented Pre-Training for Drivable Area Detection

# 摘要

> 预训练技术在深度学习中至关重要，能显著提升模型在各类任务中的表现。通过在大规模数据集上初步训练，并在特定任务数据上微调，预训练为模型打下坚实基础，增强泛化能力并加速收敛。然而，传统预训练方法依赖大量数据和计算资源，且难以捕捉深层次的特定任务特征。本文提出一种面向任务的预训练方法，首先利用 SAM 模型生成冗余分割建议，再通过 SCEF 策略微调 CLIP 模型，筛选出最接近可行驶区域的建议。这种方法生成大量粗略训练数据，再结合手动标注数据进行微调，显著提升模型性能。实验证明，与未经预训练的模型相比，我们的方法实现全面性能提升，且超越传统预训练和最先进的自训练方法。

> Pre-training techniques play a crucial role in deep learning, enhancing models' performance across a variety of tasks. By initially training on large datasets and subsequently fine-tuning on task-specific data, pre-training provides a solid foundation for models, improving generalization abilities and accelerating convergence rates. This approach has seen significant success in the fields of natural language processing and computer vision. However, traditional pre-training methods necessitate large datasets and substantial computational resources, and they can only learn shared features through prolonged training and struggle to capture deeper, task-specific features. In this paper, we propose a task-oriented pre-training method that begins with generating redundant segmentation proposals using the Segment Anything (SAM) model. We then introduce a Specific Category Enhancement Fine-tuning (SCEF) strategy for fine-tuning the Contrastive Language-Image Pre-training (CLIP) model to select proposals most closely related to the drivable area from those generated by SAM. This approach can generate a lot of coarse training data for pre-training models, which are further fine-tuned using manually annotated data, thereby improving model's performance. Comprehensive experiments conducted on the KITTI road dataset demonstrate that our task-oriented pre-training method achieves an all-around performance improvement compared to models without pre-training. Moreover, our pre-training method not only surpasses traditional pre-training approach but also achieves the best performance compared to state-of-the-art self-training methods.

[Arxiv](https://arxiv.org/abs/2409.20166)