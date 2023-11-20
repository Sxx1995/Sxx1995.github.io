---
layout: post
title:  "Remember What You have drawn: Semantic Image Manipulation with Memory"
date:   2021-07-27
categories: DeepLearning VideoCaptioning ChangeCaptioning ReinforcementLearning
---

![main](/assets/img/editing.PNG)


<div class="grid-wrapper">
  <div style="grid-column: span 3;">
    <p class="blue" style="margin-top:0px; margin-bottom:0px;">
      <b>Xiangxi Shi</b>
      &nbsp;&nbsp; <a href="https://wu-zhonghua.github.io/" class="author-link">Zhonghua Wu</a>
      &nbsp;&nbsp; <a href="https://guosheng.github.io/" class="author-link">Guosheng Lin</a>
      &nbsp;&nbsp; <a href="https://www.ntu.edu.sg/home/asjfcai/" class="author-link">Jianfei Cai</a>
      &nbsp;&nbsp; <a href="https://raihanjoty.github.io/" class="author-link">Shafiq Joty</a>
    </p>
    <p align="justify">
Currently, the state-of-the-art methods treat few-shot semantic segmentation task as a conditional foreground-background segmentation problem, assuming each class is independent. In this paper, we introduce the concept of meta-class, which is the meta information (eg certain middle-level features) shareable among all classes. To explicitly learn meta-class representations in few-shot segmentation task, we propose a novel Meta-class Memory based few-shot segmentation method (MM-Net), where we introduce a set of learnable memory embeddings to memorize the meta-class information during the base class training and transfer to novel classes during the inference stage. Moreover, for the k-shot scenario, we propose a novel image quality measurement module to select images from the set of support images. A high-quality class prototype could be obtained with the weighted sum of support image features based on the quality measure. Experiments on both PASCAL-5^ i and COCO datasets show that our proposed method is able to achieve state-of-the-art results in both 1-shot and 5-shot settings. Particularly, our proposed MM-Net achieves 37.5% mIoU on the COCO dataset in 1-shot setting, which is 5.1% higher than the previous state-of-the-art.
    </p>
    <div class="center">
      <p>
        <a class="link" href="https://arxiv.org/abs/2107.12579">Paper</a>
      </p>
    </div>
  </div>
</div>
