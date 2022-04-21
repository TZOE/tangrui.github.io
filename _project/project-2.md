---
title: "前列腺增生双极电切AI预警"
excerpt: "2018年全国大学生FPGA创新设计邀请赛特等奖获奖作品<br/><img src='/images/prostate_workflow.png'><br/><video src='/files/robot_demo_Trim.mp4' controls='controls' width='1000' height='600'>"
collection: project
---

基于Tensorflow框架建立halfsqueezenet网络结构，其集成squeezenet轻量级的特点，并在分类之后加入了定位算法，得到了一个在准确度不下降太多的情况下需要更少参数的CNN网络。首先在PC和 Jetson tx2上用自制的数据集训练并验证构建的网络框架以及数据集的准确性；之后在halfsqueezenet前向推理代码通过vivado综合成相应IP；将IP和权重上载到开发板上，利用FPGA 实现对卷积神经网络的加速。

<img src='/images/prostate_workflow.png'>
<video src='/files/robot_demo_Trim.mp4' controls='controls' width='800' height='500'>