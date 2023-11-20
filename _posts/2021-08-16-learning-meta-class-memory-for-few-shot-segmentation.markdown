---
layout: post
title:  "Learning Meta-class Memory for Few-Shot Semantic Segmentation"
date:   2021-08-16
categories: DeepLearning VideoCaptioning ChangeCaptioning ReinforcementLearning
---

![main](/assets/img/seg.PNG)


<div class="grid-wrapper">
  <div style="grid-column: span 3;">
    <p class="blue" style="margin-top:0px; margin-bottom:0px;">
      &nbsp;&nbsp; <a href="https://wu-zhonghua.github.io/" class="author-link">Zhonghua Wu</a>
      <b>Xiangxi Shi</b>
      &nbsp;&nbsp; <a href="https://guosheng.github.io/" class="author-link">Guosheng Lin</a>
      &nbsp;&nbsp; <a href="https://www.ntu.edu.sg/home/asjfcai/" class="author-link">Jianfei Cai</a>
    </p>
    <p style="margin-top:0px;"><i>ICCV, 2021</i></p>
    <p align="justify">
Currently, the state-of-the-art methods treat few-shot semantic segmentation task as a conditional foreground-background segmentation problem, assuming each class is independent. In this paper, we introduce the concept of meta-class, which is the meta information (eg certain middle-level features) shareable among all classes. To explicitly learn meta-class representations in few-shot segmentation task, we propose a novel Meta-class Memory based few-shot segmentation method (MM-Net), where we introduce a set of learnable memory embeddings to memorize the meta-class information during the base class training and transfer to novel classes during the inference stage. Moreover, for the k-shot scenario, we propose a novel image quality measurement module to select images from the set of support images. A high-quality class prototype could be obtained with the weighted sum of support image features based on the quality measure. Experiments on both PASCAL-5^ i and COCO datasets show that our proposed method is able to achieve state-of-the-art results in both 1-shot and 5-shot settings. Particularly, our proposed MM-Net achieves 37.5% mIoU on the COCO dataset in 1-shot setting, which is 5.1% higher than the previous state-of-the-art.
    </p>
    <div class="center">
      <p>
        <a class="link" href="https://arxiv.org/abs/2108.02958">Paper</a>
      | <a class="link" href="https://scholar.googleusercontent.com/scholar.bib?q=info:C15V6KqIcTcJ:scholar.google.com/&output=citation&scisdr=ClEwqH7BEJLQw8cO3wQ:AFWwaeYAAAAAZVsIxwT8UdATP8k5KHw61CuCzEM&scisig=AFWwaeYAAAAAZVsIxyzU1R6vMSffWxG4-gMSqcw&scisf=4&ct=citation&cd=-1&hl=en">Bibtex</a>
      </p>
    </div>
  </div>
</div>
