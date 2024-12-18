# 提升自主代理的UI定位功能

发布时间：2024年10月17日

`Agent` `软件开发` `自动化`

> ClickAgent: Enhancing UI Location Capabilities of Autonomous Agents

# 摘要

> 随着数字设备（如电脑和智能手机）的普及，图形用户界面 (GUI) 的重要性日益凸显，自动化工具的需求也随之增长。尽管 GPT-4V 等多模态大型语言模型 (MLLM) 在撰写邮件等任务中表现优异，但在 GUI 交互上却显得力不从心，限制了其在日常任务自动化中的应用。为此，我们推出了 ClickAgent，一种专为构建自主代理设计的新框架。ClickAgent 中，MLLM 负责推理和行动规划，而独立的 UI 定位模型（如 SeeClick）则精准识别屏幕上的 UI 元素。这一创新有效弥补了当前 MLLM 在 UI 元素定位上的短板。  在 AITW 基准测试中，ClickAgent 的表现远超 CogAgent、AppAgent 和 Auto-UI 等基于提示的自主代理。我们的测试涵盖了 Android 智能手机模拟器和实际设备，以任务成功率为核心指标，全面评估了 ClickAgent 的性能。

> With the growing reliance on digital devices equipped with graphical user interfaces (GUIs), such as computers and smartphones, the need for effective automation tools has become increasingly important. While multimodal large language models (MLLMs) like GPT-4V excel in many areas, they struggle with GUI interactions, limiting their effectiveness in automating everyday tasks. In this paper, we introduce ClickAgent, a novel framework for building autonomous agents. In ClickAgent, the MLLM handles reasoning and action planning, while a separate UI location model (e.g., SeeClick) identifies the relevant UI elements on the screen. This approach addresses a key limitation of current-generation MLLMs: their difficulty in accurately locating UI elements. ClickAgent outperforms other prompt-based autonomous agents (CogAgent, AppAgent) on the AITW benchmark. Our evaluation was conducted on both an Android smartphone emulator and an actual Android smartphone, using the task success rate as the key metric for measuring agent performance.

[Arxiv](https://arxiv.org/abs/2410.11872)