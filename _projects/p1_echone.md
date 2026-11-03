---
layout: page
title: EchoONE
description: 统一多切面超声心动图分割模型——一个模型完成全部标准切面的像素级解析
img: assets/img/projects/echone.png
importance: 1
category: 心脏超声智能分析
related_publications: true
---

超声心动图检查依赖多个标准切面（胸骨旁长轴、短轴、心尖四腔等），临床自动分析要求对每个切面分别分割
心肌、心腔等结构。传统方法为每个切面单独训练模型，部署与维护成本高。

**EchoONE** 提出"一切割模型"（One Model for All Planes）的统一分割框架：在单一网络内学习多切面共享的
心脏解剖先验与切面特有的形态差异，实现：

- 一个模型覆盖全部标准切面，显著降低部署成本
- 切面间知识迁移，缓解小样本切面标注不足
- 与下游测量（容积、射血分数）流程无缝衔接

{% cite hu2025echoone %}

---

<p>
  <a href="http://localhost:7860" target="_blank" class="btn btn-primary">
    🚀 在线演示
  </a>
  <span class="text-muted">（本地/实验室服务器部署的演示服务；提供 DICOM 图像或超声视频，在线返回分割结果）</span>
</p>
