---
layout: post
title:  "Viewpoint-Aware Visual Grounding in 3D Scenes"
date:   2024-4-7
categories: DeepLearning VisualGroudning PointCloud
---

![main](/assets/img/vg.png)


<div class="grid-wrapper">
  <div style="grid-column: span 3;">
    <p class="blue" style="margin-top:0px; margin-bottom:0px;">
      <b>Xiangxi Shi</b>
      &nbsp;&nbsp; <a href="https://wu-zhonghua.github.io/" class="author-link">Zhonghua Wu</a>
      &nbsp;&nbsp; <a href="https://web.engr.oregonstate.edu/~leestef/" class="author-link">Stefan Lee</a>
    </p>
    <p style="margin-top:0px;"><i>CVPR 2024</i></p>
    <p align="justify">
Referring expressions for visual objects often include descriptions of relative spatial arrangements to other objects -- e.g. ``to the right of'' -- that depend on the point of view of the speaker.  In 2D referring expression tasks, this viewpoint is captured unambiguously in the image.  However, grounding expressions with such spatial language in 3D without viewpoint annotations can be ambiguous. In this paper, we investigate the significance of viewpoint information in 3D visual grounding -- introducing a model that explicitly predicts the speaker's viewpoint based on the referring expression and scene. We pretrain this model on a synthetically generated dataset that provides viewpoint annotations and then finetune on 3D referring expression datasets. Further, we introduce an auxiliary uniform object representation loss to encourage viewpoint invariance in learned object representations. We find that our proposed ViewPoint Prediction Network (VPP-Net) achieves state-of-the-art performance on ScanRefer, SR3D, and NR3D -- improving Accuracy@0.25IoU by 1.06%, 0.60%, and 4.80% respectively compared to prior work.
    </p>
    <div class="center">
      <p>
        <a class="link" href="https://arxiv.org/abs/2108.02958">Paper</a>
      | <a class="link" href="https://scholar.googleusercontent.com/scholar.bib?q=info:C15V6KqIcTcJ:scholar.google.com/&output=citation&scisdr=ClEwqH7BEJLQw8cO3wQ:AFWwaeYAAAAAZVsIxwT8UdATP8k5KHw61CuCzEM&scisig=AFWwaeYAAAAAZVsIxyzU1R6vMSffWxG4-gMSqcw&scisf=4&ct=citation&cd=-1&hl=en">Bibtex</a>
      </p>
    </div>
  </div>
</div>
