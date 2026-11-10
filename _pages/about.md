---
permalink: /
title: "吴俊羽"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

你好，我是吴俊羽。

我对具身智能很感兴趣，目前正在进行世界模型方向的研究。

这个主页用于整理我的研究兴趣、学习记录和项目实践。

## 科研经历

### EvoWorld: A World-Model-Centric Framework for Continuous Self-Evolution of Modular Embodied Skills

**ECCV 2026**

- 针对单体 VLA 在碎片化数据下的灾难性遗忘问题，参与提出“动力学—技能解耦”架构：动作条件视频世界模型负责认知核心，VLA 模型组成可插拔专家库，MLLM 路由器按场景与任务语义调度。
- 建立 VLM 诊断驱动的闭环自进化机制，由世界模型反事实推演进行候选专家打分，并根据失败归因定向更新对应模块。
- 在 4 种 VLA 骨干和 5 类技能上，任务成功率相对提升 62%–83%。

### [HAI: Hierarchical Anchored Interaction for Multi-View Bimanual World Models](https://hai-anon.github.io/)

**NeurIPS 2026**

- 针对双臂世界模型中的左右臂动作不可互换、多视角证据不对称和长程场景漂移问题，参与提出 HAI 分层条件化架构。
- 设计锚定动态生成机制，将动作条件特征与逐视角持久场景锚点融合，抑制长程 rollout 中的物体身份与几何漂移。
- 在 AgiBot（11,627 条轨迹）与 DROID 上进行评估，PSNR、SSIM、LPIPS、FID、FVD 等指标全面优于基线。

### [VERDI: Verified Contradictions for Continual World-Model Optimization](https://verdiwm-anno.github.io/)

**Under review**

- 设计 Optimization Fingerprint，通过共享、可逆、剂量校准的推理探针，刻画动作缩放、上下文保持、首帧锚定和采样噪声等干预因素的响应模式。
- 构建干预修复几何与证据归档机制，以指纹距离和支持集重叠度检索历史修复，并按置信度分配试错预算。
- 在 9 个异构骨干、27 个留一 campaign 和 216 个迁移决策上验证，修复效果符号预测准确率达 83%，GPU 开销降低 69%。

## 实习经历

### 北京智源研究院

**2026/04–至今 · 具身世界模型预训练实习生**

### 蔚来

**2026/10–至今 · 自动驾驶世界模型基模研究型实习生**

## 研究兴趣

- 具身智能（Embodied Intelligence）
- 世界模型（World Models）
- 智能体与环境交互

## 当前方向

我正在探索如何让智能体通过世界模型理解环境、预测未来，并在交互中形成更可靠的决策能力。

## 联系与代码

你可以在 [GitHub](https://github.com/wujunyu687-lab) 查看我的公开代码与后续更新。
