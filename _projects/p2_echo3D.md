---
layout: page
title: Echo3D
description: 从稀疏无姿态二维超声切片重建三维心脏——免定位、免标定的术中三维成像
img: assets/img/projects/echo3d.png
importance: 2
category: 心脏三维建模
related_publications: true
---

三维心脏模型对术前规划与术中导航至关重要，但常规三维超声依赖专用探头与固定扫描轨迹，设备昂贵、
操作门槛高。本方向研究**从常规二维超声切片序列重建三维心脏**：

- 从稀疏、无姿态标注（pose-agnostic）的 2D 切片恢复完整 3D 心脏几何
- 免定位传感器、免标定流程，兼容任意存量超声设备
- 面向术中场景的在线重建（Online Learning）与伪影鲁棒性

{% cite chen20253d luo2023recon %}

---

<p>
  <a href="https://demo.cardioai-xue.top/echo3d" target="_blank" class="btn btn-primary">
    🚀 在线演示
  </a>
  <span class="text-muted">（上传切片序列即可重建可交互三维心脏模型）</span>
</p>
