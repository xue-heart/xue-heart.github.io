---
layout: page
title: 心肌室壁厚度分析
description: 短轴超声时序形变学习实现左室壁厚度自动测量
img: assets/img/1.jpg
importance: 3
category: 心脏超声智能分析
related_publications: true
---

左室壁厚度（LV Wall Thickness）是肥厚型心肌病、高血压心脏病等诊断的关键结构参数，临床手工测量
工作量大且专家间差异显著。

**TC-Deformer**（Temporal Compatible Deformer）将室壁厚度估计建模为**时序兼容的形变学习**问题：

- 以短轴超声序列为输入，利用心动周期内的时序约束增强心肌边界定位
- 兼容形变场学习，直接从形变特征回归壁厚度，避免脆弱的分割-测距两段式流程
- 与深圳人民医院合作完成临床数据验证 {% cite zhang2023tcdeformer zhang2023wall %}

---

<p>
  <a href="https://demo.cardioai-xue.top/wallthickness" target="_blank" class="btn btn-primary">
    🚀 在线演示
  </a>
  <span class="text-muted">（上传短轴切面序列，自动输出室壁厚度图谱）</span>
</p>
