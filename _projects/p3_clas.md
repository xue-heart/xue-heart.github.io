---
layout: page
title: CLAS
description: 心脏功能智能定量——从超声序列精准估计射血分数等心功能指标
img: assets/img/projects/clas.png
importance: 3
category: 心脏超声智能分析
related_publications: true
---

射血分数（Ejection Fraction, EF）是评估心功能的核心指标，临床依赖专家逐帧描记，主观性强、耗时。
**CLAS**（Cardiac function quantification via Co-Learning of Appearance and Shape）提出外观-形态
协同学习框架：

- 分割与回归联合优化，直接从序列级图像估计 EF
- 时序一致性约束（Temporal-consistent Segmentation），提升运动边界稳定性
- 与心腔分割端到端协同，结果可回溯、可解释

{% cite wei2023co wei2020temporal xue2021left %}

---

<p>
  <a href="https://demo.cardioai-xue.top/clas" target="_blank" class="btn btn-primary">
    🚀 在线演示
  </a>
  <span class="text-muted">（上传心尖切面序列，自动输出 EF 及容积曲线）</span>
</p>
