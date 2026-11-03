---
layout: page
title: IE-CAD
description: 超声心动图视频驱动的冠心病智能诊断与狭窄程度分级
img: assets/img/projects/guo2025echocardiographic.png
importance: 5
category: 临床转化
related_publications: true
---

冠心病（CAD）的一线筛查依赖专家目测超声心动图评估心肌运动，耗时且依赖经验。
**IE-CAD**（Intelligent Echo for CAD）与**北京医院（国家老年医学中心）、阜外医院**合作，
构建超声视频驱动的多任务学习模型：

- 3D DeepLabV3+ 骨干捕获动态心肌轮廓，多任务学习同步完成 CAD 筛查与冠脉狭窄程度分级
- 从局部语义结构提取多维特征，服务"筛查-分级"一体化临床工作流
- 已开展多中心临床数据验证 {% cite guo2025echocardiographic %}

---

<p>
  <a href="https://demo.cardioai-xue.top/iecad" target="_blank" class="btn btn-primary">
    🚀 在线演示
  </a>
  <span class="text-muted">（上传超声视频，输出 CAD 风险评估与狭窄分级）</span>
</p>
