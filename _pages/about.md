---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<div id='about-me'>

<p><em>Last updated: 27 January 2026</em></p>

<p>I am a first-year Ph.D. student in Computer Science at <strong><a href="https://home.dartmouth.edu">Dartmouth College</a></strong>, advised by Prof. <strong><a href="https://nsingh1.host.dartmouth.edu/">Nikhil Singh</a></strong>, where I pursue cutting-edge research at the intersection of AI Agents and Computer Vision. Previously, I earned my Master's degree in Data Science from <strong><a href="https://www.cuhk.edu.cn/en">The Chinese University of Hong Kong, Shenzhen</a></strong>, under the guidance of Prof. <strong><a href="https://scholar.google.com/citations?user=z-rqsR4AAAAJ&hl=zh-CN">Xiaoguang Han</a></strong>. My academic journey began with a Bachelor's degree in Biomedical Engineering from <strong><a href="https://en.sjtu.edu.cn/">Shanghai Jiao Tong University</a></strong>.</p>

<p>I worked as a research intern at <strong><a href="https://damo.alibaba.com/research-areas?language=en">Alibaba DAMO Academy</a></strong> for five months, mentored by <strong><a href="https://scholar.google.com/citations?user=9o5r8bUAAAAJ&hl=zh-CN">Dr.Tian Zhou</a></strong>. I also served as a Visiting Student with Prof. <strong><a href="https://scholar.google.com/citations?user=p9-ohHsAAAAJ&hl=zh-CN">Ming-Hsuan Yang</a></strong> at <strong><a href="https://www.ucmerced.edu/">UC Merced</a></strong> and Prof. <strong><a href="https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=zh-CN">Chao Ma</a></strong> at the <strong><a href="https://ai.sjtu.edu.cn">AI Institute</a></strong> of <strong><a href="https://en.sjtu.edu.cn/">Shanghai Jiao Tong University</a></strong>. I have previously collaborated with Prof. <strong><a href="https://scholar.google.com.hk/citations?user=SSI90d4AAAAJ&hl=en">Lu Qi</a></strong> and Dr. <strong><a href="https://scholar.google.com/citations?user=FL3ReD0AAAAJ&hl=zh-CN">Xiangtai Li</a></strong> at <strong>TikTok</strong>, as well as with Prof. <strong><a href="https://scholar.google.com/citations?user=bMedjfUAAAAJ&hl=en">Junwei Liang</a></strong> and Dr. <strong><a href="https://scholar.google.com/citations?user=TqS6s4gAAAAJ&hl=zh-CN">Peijie Dong</a></strong> at AI Thrust, <strong><a href="https://www.hkust-gz.edu.cn/">The Hong Kong University of Science and Technology (Guangzhou)</a></strong>.</p>

<p>My previous research background primarily focused on video prediction and spatiotemporal forecasting.</p>

<p>My Ph.D. research interests lie in the intersection of AI Agents and Computer Vision, with a particular focus on <strong>AI Agents</strong>: (1) agent memory mechanisms and architectures, (2) long-term memory storage and retrieval for agents, and (3) memory-augmented agent reasoning and decision-making.</p>

</div>

<div style="margin: 2em 0; padding: 1.5em; background: linear-gradient(135deg, #fff5f5 0%, #fff1f1 100%); border-left: 4px solid #f56565; border-bottom: 1px solid #f56565; border-radius: 8px; box-shadow: 0 2px 8px rgba(245, 101, 101, 0.1);">
    <strong style="color: #c53030; font-size: 1.1em; display: block; margin-bottom: 0.5em;">🤝 Open for Collaboration & Internship Opportunities</strong>
    <p style="margin: 0; color: #742a2a; line-height: 1.6;">I'm open for academic collaborations and actively seeking <span style="background-color: #fed7d7; padding: 2px 6px; border-radius: 4px; font-weight: 700; color: #c53030;">agent-related summer internship opportunities</span> based in the U.S. for 2026 and 2027. If you have suitable opportunities for collaboration or internships, please feel free to email me at <a href="mailto:tangyujin0275@gmail.com" style="color: #c53030; font-weight: 600; text-decoration: none; border-bottom: 1px solid #c53030;">tangyujin0275@gmail.com</a>.</p>
</div>

# News

{: #news .section-title .section-title-news}

- *2026.01*: &nbsp;🎉🎉 One paper is accepted by ICLR 2026.
- *2026.01*: &nbsp;🎉🎉 PredFormer is accepted by TMLR 2026.
- *2025.09*: &nbsp;🎓🎓 Yujin enrolled in Dartmouth College as a Ph.D. student in Computer Science.
- *2025.03*: &nbsp;🔬🔬 Yujin joined Alibaba DAMO Academy as a research intern.
- *2024.10*: &nbsp;🎉🎉 PredFormer is available!  This is the first pure-transformer based model in spatial-temporal predictive learning, which is recurrent-free and convolution-free, outperforming previous models by large margins with superior efficiency. [**Paper**](https://arxiv.org/abs/2410.04733) [ **Code**](https://github.com/yyyujintang/PredFormer) ![Stars](https://img.shields.io/github/stars/yyyujintang/PredFormer)
- *2024.04*: &nbsp;🎉🎉 VMRNN is accepted by [CVPRW24](https://sites.google.com/view/ieeecvf-cvpr2024-precognition)!
- *2024.03*: &nbsp;🎉🎉 PostRainBench is accepted by [ICLRW24](https://www.climatechange.ai/events/iclr2024)!
- *2024.01*: &nbsp;🎉🎉 Yujin created Awesome-Mamba-Papers repository. **This is the first Awesome Mamba repository and promotes Mamba related research**. [Link](https://github.com/yyyujintang/Awesome-Mamba-Papers) ![Stars](https://img.shields.io/github/stars/yyyujintang/Awesome-Mamba-Papers)

# Publications

{: #publications .section-title .section-title-publication}

<div class="publication-list">

<div class="pub-item">
<div class="pub-title"><a href="https://arxiv.org/abs/2509.14181">Bridging past and future: Distribution-aware alignment for time series forecasting</a></div>
<div class="pub-authors">Yifan Hu, Jie Yang, Tian Zhou, Peiyuan Liu, <strong>Yujin Tang</strong>, Rong Jin, Liang Sun.</div>
<div class="pub-venue"><em>International Conference on Learning Representations</em> (<strong>ICLR</strong>), 2026.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://arxiv.org/abs/2410.04733">Video Prediction Transformers without Recurrence or Convolution</a></div>
<div class="pub-authors"><strong>Yujin Tang</strong>, Qi Lu, Xiangtai Li, Chao Ma, Ming-Hsuan Yang.</div>
<div class="pub-venue"><em>Transactions on Machine Learning Research</em> (<strong>TMLR</strong>), 2026.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://arxiv.org/abs/2403.16536">VMRNN: Integrating Vision Mamba and LSTM for Efficient and Accurate Spatiotemporal Forecasting</a></div>
<div class="pub-authors"><strong>Yujin Tang</strong>, Peijie Dong, Zhenheng Tang, Xiaowen Chu, Junwei Liang.</div>
<div class="pub-venue"><em>IEEE Conference on Computer Vision and Pattern Recognition Workshop</em> (<strong>CVPR Workshop</strong>), 2024.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://arxiv.org/abs/2310.02676">PostRainBench: A comprehensive benchmark and a new model for precipitation forecasting</a></div>
<div class="pub-authors"><strong>Yujin Tang</strong>, Jiaming Zhou, Xiang Pan, Zeying Gong, Junwei Liang.</div>
<div class="pub-venue"><em>International Conference on Learning Representations Workshop</em> (<strong>ICLR Workshop</strong>), 2024.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://arxiv.org/abs/2310.00655">Patchmixer: A patch-mixing architecture for long-term time series forecasting</a></div>
<div class="pub-authors">Zeying Gong, <strong>Yujin Tang</strong>, Junwei Liang.</div>
<div class="pub-venue"><em>International Joint Conference on Artificial Intelligence Workshop</em> (<strong>IJCAI Workshop</strong>), 2024.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://link.springer.com/chapter/10.1007/978-3-030-59713-9_26">Ovarian Cancer Early Diagnosis in Proteomics Data Using Composite Asymmetric Convolution</a></div>
<div class="pub-authors">Cheng Yuan, <strong>Yujin Tang</strong> and Dahong Qian.</div>
<div class="pub-venue"><em>International Conference on Medical Image Computing and Computer-Assisted Intervention</em> (<strong>MICCAI</strong>), 2020.</div>
</div>

</div>

# Educations

{: #educations .section-title .section-title-education}

<div class="education-item">
  <div class="logo-container">
    <img src="images/dartmouth-logo.png" alt="Dartmouth College Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Dartmouth College</div>
    <div class="subtitle">Ph.D. in Computer Science</div>
    <div class="date">2025.09 - 2030.07 (expected)</div>
    <div class="description">Advised by Prof. <a href="https://nsingh1.host.dartmouth.edu/">Nikhil Singh</a></div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container">
    <img src="images/cuhksz-logo.png" alt="CUHKSZ Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">The Chinese University of Hong Kong, Shenzhen</div>
    <div class="subtitle">M.Sc. in Data Science</div>
    <div class="date">2021.09 - 2023.07</div>
    <div class="description">Advised by Prof. <a href="https://scholar.google.com/citations?user=z-rqsR4AAAAJ&hl=zh-CN">Xiaoguang Han</a></div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container">
    <img src="images/sjtu-logo.png" alt="SJTU Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Shanghai Jiao Tong University</div>
    <div class="subtitle">B.Eng. in Biomedical Engineering</div>
    <div class="date">2017.09 - 2021.06</div>
    <div class="description">Advised by Prof. <a href="https://bme.sjtu.edu.cn/En/FacultyDetail/41/">Dahong Qian</a></div>
  </div>
</div>

# Internships

{: #internships .section-title .section-title-internship}

<div class="internship-item highlight">
  <div class="logo-container">
    <img src="images/alibaba-logo.png" alt="Alibaba DAMO Academy Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Alibaba DAMO Academy</div>
    <div class="subtitle">Algorithm Engineer Intern</div>
    <div class="date">2025.03 - 2025.07</div>
    <div class="description">Research intern for 5 wonderful months. Working on cutting-edge AI research and development. Mentored by Dr. <a href="https://scholar.google.com/citations?user=9o5r8bUAAAAJ&hl=zh-CN">Tian Zhou</a> and Dr. <a href="https://scholar.google.com/citations?user=D_cOMBgAAAAJ&hl=en">Liang Sun</a></div>
  </div>
</div>

<div class="internship-item">
  <div class="logo-container">
    <img src="images/ucmerced-logo.png" alt="UC Merced Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">UC Merced & Shanghai Jiao Tong University</div>
    <div class="subtitle">Remote Visiting Student @ UC Merced & Onsite Visiting Student @ SJTU</div>
    <div class="date">2024.06 - 2025.03</div>
    <div class="description">Working with Prof. <a href="https://scholar.google.com/citations?user=p9-ohHsAAAAJ&hl=zh-CN">Ming-Hsuan Yang</a> at UC Merced, Prof. <a href="https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=zh-CN">Chao Ma</a> at <a href="https://ai.sjtu.edu.cn">AI Institute, SJTU</a>, and Prof. <a href="https://scholar.google.com.hk/citations?user=SSI90d4AAAAJ&hl=en">Lu Qi</a> at WHU.</div>
  </div>
</div>

<div class="internship-item">
  <div class="logo-container">
    <img src="images/hkust-gz-logo.png" alt="HKUST-GZ Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">The Hong Kong University of Science and Technology (Guangzhou)</div>
    <div class="subtitle">Research Assistant at AI Thrust</div>
    <div class="date">2023.02 - 2024.05</div>
    <div class="description">Supervised by Prof. <a href="https://scholar.google.com/citations?user=bMedjfUAAAAJ&hl=en">Junwei Liang</a>. </div>
  </div>
</div>

# Academic Service

{: #academic-service .section-title .section-title-service}

* **2026:** Reviewer for *International Journal of Computer Vision (IJCV)*
* **2025:** Reviewer for *Transactions on Machine Learning Research (TMLR)* and *International Journal of Computer Vision (IJCV)*
* **2024:** Reviewer for *IEEE Transactions on Neural Networks and Learning Systems (TNNLS)*

# Teaching

{: #teaching .section-title .section-title-teaching}

* **Winter 2026:** Head Teaching Assistant for Principles of Machine Learning, `<strong><a href="https://home.dartmouth.edu">`Dartmouth College`</a></strong>`
* **Fall 2025:** Teaching Assistant for Video Understanding, `<strong><a href="https://home.dartmouth.edu">`Dartmouth College`</a></strong>`
* **Spring 2023:** Teaching Assistant for AIAA 5032: Foundations of Artificial Intelligence (for master students), `<strong><a href="https://www.hkust-gz.edu.cn/">`The Hong Kong University of Science and Technology (Guangzhou)`</a></strong>`

# Resources for Researchers

{: #resources-for-cv-researchers .section-title .section-title-resources}

**Researchers I Admire:** [Yejin Choi-Stanford](https://yejinc.github.io/), [Yu Su-OSU](https://ysu1989.github.io/), [Shunyu Yao-OpenAI](https://ysymyth.github.io/)

[Ming-Hsuan Yang-UCM](https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=en): How to Get Your CVPR Paper Rejected? [Link](https://vision.sjtu.edu.cn/files/How-to-get-your-CVPR-paper-rejected.pdf)

[Bill Freeman-MIT](https://scholar.google.com/citations?user=0zZnyMEAAAAJ&hl=zh-CN): How to Write Papers [Link](https://faculty.cc.gatech.edu/~parikh/citizenofcvpr/static/slides/freeman_how_to_write_papers.pdf) Advice for Graduate Student  [Link](https://people.csail.mit.edu/billf/talks/10minFreeman2013.pdf)

# More About Me

{: #more-about-me .section-title .section-title-about}

- The boundaries of language are the boundaries of thought. I am a lifelong learner with a growth mindset and a writing enthusiast.
- In academia, I embrace productivity ambiguity and dance with uncertainty.
- I am from Dazhou, Sichuan Province, and I am skilled at cooking delicious Sichuan cuisine.

<div class="life-gallery">
  <div class="gallery-item">
    <img src="images/life-1.jpg" alt="Life photo 1" loading="lazy">
    <div class="caption">Caption 1</div>
  </div>
  <div class="gallery-item">
    <img src="images/life-2.jpg" alt="Life photo 2" loading="lazy">
    <div class="caption">Caption 2</div>
  </div>
  <div class="gallery-item">
    <img src="images/life-3.jpg" alt="Life photo 3" loading="lazy">
    <div class="caption">Caption 3</div>
  </div>
  <div class="gallery-item">
    <img src="images/life-4.jpg" alt="Life photo 4" loading="lazy">
    <div class="caption">Caption 4</div>
  </div>
</div>

<script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?d=DpZkNL3LsLmeQRxUKn0lTTI5TvgkpddDlnJpErWoftQ&cl=ffffff&w=a"></script>
