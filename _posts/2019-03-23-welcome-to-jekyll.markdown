---
layout: post
title:  "Video Captioning with Boundary-aware Hierarchical Language Decoding and Joint Video Prediction"
date:   2020-7-18 
categories: DeepLearning ComputerVision VideoCaptioning
---


![main](/assets/img/vtt_main.png)

<div class="grid-wrapper">
  <div style="grid-column: span 3;">
    <p class="blue" style="margin-top:0px; margin-bottom:0px;">
      <b>Xiangxi Shi</b>
      &nbsp;&nbsp; <a href="https://www.ntu.edu.sg/home/asjfcai/" class="author-link">Jianfei Cai</a>
      &nbsp;&nbsp; <a href="https://gujiuxiang.com/" class="author-link">Jiuxiang Gu</a>
      &nbsp;&nbsp; <a href="https://raihanjoty.github.io/" class="author-link">Shafiq Joty</a>
    </p>
    <p style="margin-top:0px;"><i>ArXiv, 2020</i></p>
    <p align="justify">
The explosion of video data on the Internet requires effective and efficient technology to generate captions automatically for people, especially those who are visually impaired. Despite the great progress of video captioning research, particularly in video feature encoding, the language decoder is still largely based on the prevailing recurrent structure such as LSTM, which tends to prefer frequent words that align with the video and do not generalize well to new videos. In this paper, we propose a boundary-aware hierarchical language decoder for video captioning, which consists of a high-level decoder, working as a global (caption-level) language model, and a low-level decoder, working as a local (phrase-level) language model. Most importantly, we introduce a binary gate into the low-level language decoder to detect the phrasal boundaries. Together with other advanced components including a joint video prediction module, a shared soft attention, and a boundary-aware video encoding module, our integrated video captioning framework can discover hierarchical language information and distinguish the subjects from the objects of the verbs in a sentence, which are usually confusing during caption generation. Extensive experiments on two widely-used video captioning datasets, MSR-Video-to-Text (MSR-VTT) and YouTube-to-Text (MSVD), show that our method is highly competitive, compared with the state-of-the-art methods.
    </p>
    <div class="center">
      <p>
        <a class="link" href="https://arxiv.org/pdf/1807.03658.pdf">Paper</a>
      | <a class="link" href="https://scholar.googleusercontent.com/scholar.bib?q=info:phndiI9iblAJ:scholar.google.com/&output=citation&scisdr=CgVaNFdhELbVx1mKsfs:AAGBfm0AAAAAXrmPqfvesnF0ye3hky2G9TsvPW2hssWE&scisig=AAGBfm0AAAAAXrmPqcFEZO8UveTfzfeZfLpjZiGOODMP&scisf=4&ct=citation&cd=-1&hl=en">Bibtex</a>
      </p>
    </div>
  </div>
</div>

