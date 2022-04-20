---
layout: archive
title: "简历"
permalink: /cvchina/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育背景
======
* 工学硕士, 武汉大学, 电子信息学院, 信号与信息处理专业, 2016.09-2020.06
* 工学学士, 武汉大学, 电子信息学院, 通信工程（卓越工程师计划）排名:4/121

研究方向
======
* 遥感影像解译、计算机视觉、机器学习算法

专业技能
======
* 熟悉 Python、Pytorch，了解 C++、OpenCV

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

主要项目经历
======
* 极化合成孔径雷达 (PolSAR) 影像动态序列建模与场景精细解译（国家自然基金资助项目）  2020.03-2022.06
提出多模态无监督尺度学习，提取PolSAR极化特性的空间分布同质性的特征，探索图像特征域、空间域与密度域的特性，结合近邻图检索，实现无监督的 PolSAR 图像表示与分类，成果已投稿 SCI 一区 Top 期刊 TIP。
•基于近邻图检索，提出半监督多域融合图网络，在极少量标注样本下对PolSAR影像的极化特征与空间特征进行特征建模。在 PolSAR 地物分类任务中达到 SOTA，成果已投稿 SCI 一区 Top 期刊 TGRS。
•提出无监督的自发聚类网络，称为深度图聚类。结合空间信息和极化相干矩阵来表示和聚类数据，脱离标注样本实现分类，在多个 PolSAR数据集上具有 9%-11% 的准确率提升，研究成果已投稿 EI 会议；
* 仓库自动驾驶机器人控制系统构建  2020.06-2021.12
•固定仓库环境下，多个车辆动态规划，自动驾驶完成货物运输任务。分为输入层、AI 规划层、AI 执行层
•输入层通过语音识别获取运输起始点与目的地，AI规划层通过强化学习实现固定环境多目标路径规划，AI 执行层接受 AI 规划层的路径，
通过图像、激光传感器等数据进行强化学习，实现自动驾驶运输货物。
•本人承担项目主要负责人，主要承担工作：方案制定，Unity仿真环境搭建，AI规划层强化算法设计，AI 执行层控制算法设计，AI 执行层强化学习算法设计与实现。
* 面向卫星空天地一体化网络的安全技术研究 2020.01-2021.12
设计卫星网络的群组密钥管理方案，对密钥分发和密钥更新消息进行保护，研究成果已通过专家评审，国防专利申请中；设计安全、高效的星间、星地终端随遇接入与身份认证方案，研究成果形成研究报告已通过专家评审

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
