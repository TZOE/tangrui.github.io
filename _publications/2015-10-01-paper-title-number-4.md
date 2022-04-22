---
title: "RDP-Net: Region Detail Preserving Network for Change Detection"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-4
excerpt: "R., Tang, R.. (2020).RDP-Net: Region Detail Preserving Network for Change Detection. IEEE Trans. Geosci. Remote Sens.. SCI, Top Journal, IF: 5.855 (Major reviewer) <br/><img src='/images/RDPnet.jpg'>"

---
Change detection (CD) is an essential earth observation technique. It captures the dynamic information of land objects. With the rise of deep learning, neural networks (NN) have shown great potential in CD. However, current NN models introduce backbone architectures that lose the detail information during learning. Moreover, current NN models are heavy in parameters, which prevents their deployment on edge devices such as drones. In this work, we tackle this issue by proposing RDP-Net: a region detail preserving network for CD. We propose an efficient training strategy that quantifies the importance of individual samples during the warmup period of NN training. Then, we perform non-uniform sampling based on the importance score so that the NN could learn detail information from easy to hard. Next, we propose an effective edge loss that improves the network's attention on details such as boundaries and small regions. As a result, we provide a NN model that achieves the state-of-the-art empirical performance in CD with only 1.70M parameters. We hope our RDP-Net would benefit the practical CD applications on compact devices and could inspire more people to bring change detection to a new level with the efficient training strategy.
<img src='/images/RDPnet.jpg'>
[Download paper here](https://arxiv.org/abs/2202.09745)
