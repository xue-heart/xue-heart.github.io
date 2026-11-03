---
layout: page
title: Ctrl-GenAug
description: 可控生成式数据增强——为医学序列分类任务合成语义与顺序可控的样本
img: assets/img/projects/zhou2024ctrl.png
importance: 4
category: 生成式人工智能
related_publications: true
---

医学数据标注昂贵、隐私敏感，生成式增强为下游识别任务提供了新的数据引擎，但现有方法对
视频/三维序列缺乏**语义可控性**与**时序可控性**，且忽视合成样本的质量控制，导致"垃圾进垃圾出"。

**Ctrl-GenAug**（IJCV 2026）提出通用可控生成增强框架：

- 语义与序列顺序双重可控的扩散生成，定向合成困难类别与罕见模式
- 合成样本质量甄别机制，自动抑制噪声样本污染训练集
- 在医学序列分类任务上验证：下游性能与数据效率同步提升 {% cite zhou2024ctrl %}

---

<p>
  <a href="https://demo.cardioai-xue.top/ctrlgenaug" target="_blank" class="btn btn-primary">
    🚀 在线演示
  </a>
  <span class="text-muted">（在线体验可控生成：指定语义条件生成超声序列样本）</span>
</p>
