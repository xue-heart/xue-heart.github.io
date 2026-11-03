---
layout: page
title: EchoQC
description: 可解释深度学习框架实现超声心动图视频智能质量控制
img: assets/img/5.jpg
importance: 4
category: 心脏超声智能分析
related_publications: true
---

超声图像质量高度依赖操作者经验，低质量图像是临床 AI 落地的首要噪声源。与南京大学医学院附属
医院合作，我们提出**可解释的质量控制（QC）深度学习框架**：

- 自动识别超声视频中的伪影与不可诊断片段，给出帧级/视频级质量评分
- 可解释机制定位影响判读质量的图像区域，为操作者提供实时反馈
- 作为前置模块嵌入实验室全部下游分析流程，保障临床部署可靠性 {% cite du2025deep %}

---

<p>
  <a href="https://demo.cardioai-xue.top/echoqc" target="_blank" class="btn btn-primary">
    🚀 在线演示
  </a>
  <span class="text-muted">（上传超声视频，输出质量评分与伪影定位热图）</span>
</p>
