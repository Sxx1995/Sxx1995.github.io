---
layout: post
title:  "Efficient Reasoning with Hidden Thinking"
date:   2025-01-31
categories: DeepLearning Multimodal Reasoning EfficientInference CoT
---

<!-- Optional header image: add /assets/img/heima.png, or delete the line below -->
![main](/assets/img/heima.png)

<div class="grid-wrapper">
  <div style="grid-column: span 3;">
    <p class="blue" style="margin-top:0px; margin-bottom:0px;">
      <span>Xuan Shen</span>
      &nbsp;&nbsp; <span>Yizhou Wang</span>
      &nbsp;&nbsp; <b>Xiangxi Shi</b>
      &nbsp;&nbsp; <span>Yanzhi Wang</span>
      &nbsp;&nbsp; <span>Pu Zhao</span>
      &nbsp;&nbsp; <a href="https://gujiuxiang.com/" class="author-link">Jiuxiang Gu</a>
    </p>

    <p style="margin-top:0px;"><i>arXiv preprint (cs.CL), 2025</i></p>

    <p align="justify">
      Chain-of-Thought (CoT) reasoning can improve complex problem-solving in Multimodal Large Language Models (MLLMs),
      but verbose textual reasoning is inefficient. This paper proposes <b>Heima</b>, an efficient reasoning framework that performs
      "hidden thinking" by condensing each intermediate CoT into a compact hidden representation using a single thinking token.
      A corresponding Heima Decoder (LLM) can reconstruct variable-length textual reasoning from the hidden representations.
    </p>

    <ul>
      <li><b>Heima Encoder</b>: encodes each step of CoT into a single thinking token to reduce generated tokens.</li>
      <li><b>Heima Decoder</b>: reconstructs human-readable reasoning from hidden thinking tokens for interpretability.</li>
      <li><b>Efficiency</b>: achieves substantially fewer generated tokens while maintaining or improving zero-shot accuracy across MLLM reasoning benchmarks.</li>
    </ul>

    <div class="center">
      <p>
        <a class="link" href="https://arxiv.org/pdf/2501.19201">Paper (arXiv PDF)</a>
        | <a class="link" href="https://arxiv.org/abs/2501.19201">arXiv</a>
        | <a class="link" href="https://github.com/shawnricecake/Heima">Code</a>
        | <a class="link" href="https://doi.org/10.48550/arXiv.2501.19201">DOI</a>
      </p>
    </div>

    <hr/>

    <h3>BibTeX</h3>
    {% raw %}
    <pre><code>@misc{shen2025efficient,
  title   = {Efficient Reasoning with Hidden Thinking},
  author  = {Xuan Shen and Yizhou Wang and Xiangxi Shi and Yanzhi Wang and Pu Zhao and Jiuxiang Gu},
  year    = {2025},
  eprint  = {2501.19201},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  url     = {https://arxiv.org/abs/2501.19201}
}</code></pre>
    {% endraw %}

  </div>
</div>
