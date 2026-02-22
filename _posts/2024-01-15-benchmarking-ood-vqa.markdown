---
layout: post
title:  "Benchmarking Out-of-Distribution Detection in Visual Question Answering"
date:   2024-01-15
categories: DeepLearning VQA OODDetection Multimodal Robustness
---

<!-- Optional header image: put an image at /assets/img/vqa_ood.png, or delete the line below -->
![main](/assets/img/vqa_ood.png)

<div class="grid-wrapper">
  <div style="grid-column: span 3;">
    <p class="blue" style="margin-top:0px; margin-bottom:0px;">
      <b>Xiangxi Shi</b>
      &nbsp;&nbsp; <a href="https://web.engr.oregonstate.edu/~leestef/" class="author-link">Stefan Lee</a>
    </p>

    <p style="margin-top:0px;"><i>WACV 2024</i></p>

    <p align="justify">
      When faced with an out-of-distribution (OOD) question or image, VQA systems may provide unreliable answers.
      This work benchmarks a suite of OOD detection approaches for the multimodal VQA task, using popular VQA datasets
      and composite settings to isolate different OOD factors (e.g., visual novelty, linguistic novelty, and image–question agreement).
      The results suggest that answer confidence alone is often a poor signal, while question-generation-based and attention-based
      methods can significantly improve detection, though ungrounded pairs and small image distribution shifts remain challenging.
    </p>

    <div class="center">
      <p>
        <a class="link" href="https://openaccess.thecvf.com/content/WACV2024/papers/Shi_Benchmarking_Out-of-Distribution_Detection_in_Visual_Question_Answering_WACV_2024_paper.pdf">Paper</a>
        | <a class="link" href="https://openaccess.thecvf.com/content/WACV2024/html/Shi_Benchmarking_Out-of-Distribution_Detection_in_Visual_Question_Answering_WACV_2024_paper.html">Project Page</a>
        | <a class="link" href="https://openaccess.thecvf.com/content/WACV2024/supplemental/Shi_Benchmarking_Out-of-Distribution_Detection_WACV_2024_supplemental.pdf">Supplementary</a>
        | <a class="link" href="https://openaccess.thecvf.com/WACV2024">WACV 2024 Open Access</a>
      </p>
    </div>

    <hr/>

    <h3>BibTeX</h3>
    {% raw %}
    <pre><code>@InProceedings{Shi_2024_WACV,
  author = {Shi, Xiangxi and Lee, Stefan},
  title = {Benchmarking Out-of-Distribution Detection in Visual Question Answering},
  booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
  month = {January},
  year = {2024},
  pages = {5485-5495}
}</code></pre>
    {% endraw %}

  </div>
</div>
