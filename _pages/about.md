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

<span class='anchor' id='about-me'></span>

I am now a Visiting Student working with Prof. [Ming-Husan Yang](https://scholar.google.com/citations?user=p9-ohHsAAAAJ&hl=zh-CN) at [UC Merced](https://www.ucmerced.edu/). I was previously a Research Assistant at AI Thrust, [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), supervised by Prof. [Junwei Liang](https://scholar.google.com/citations?user=bMedjfUAAAAJ&hl=en). I got my master degree from [The Chinese University of Hongkong, Shenzhen](https://www.cuhk.edu.cn/en), advised by Prof. [Xiaoguang Han](https://scholar.google.com/citations?user=z-rqsR4AAAAJ&hl=zh-CN). Before that, I received my bachelor degree from [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/).

My previous research experience included Time Series Forecasting(1D), Medical Image Analysis and Face Recognition(2D), Video Prediction(3D).

My Long-Term Research Interests lie in:

* Next Generation Vision Backbone Design
* Video Large Language Models (VLLM)

Hope we can have better Video Understanding and Prediction ability with LLM and accelerate the coming of Video's GPT4 moment, when machines can do reasoning with video and chain-of-thought with video.

I'm actively applying for CS Ph.D. positions in 2025 Fall. Feel free to email me for academic cooperations or potential interviews.

# 📖 Educations

- *2021.09 - 2023.07*, MSc, **The Chinese University of Hongkong, Shenzhen**, Data Science
- *2017.09 - 2021.06*, Bachelor, **Shanghai Jiao Tong University**, Biomedical Engineering

# 💻 Internships

- *2024.06 - now,* Remote Visiting Student @ UC Merced and Onsite Visiting Student @ Shanghai Jiao Tong University
- *2023.02 - 2024.05,* Research Assistant, The Hong Kong University of Science and Technology (Guangzhou), Guangzhou
- *2022.09 - 2023.01,* Quant Researcher Intern, Kunshan Technology / Kunteng Investment, Shenzhen
- *2022.06 - 2023.08*, Algorithm Engineer Intern, Hikvision Research Institute, Hangzhou
- *2021.07 - 2022.02*, Reseach Assistant, Shenzhen Research Institute of Big Data, Shenzhen

# 🔥 News

- *2024.06*:&nbsp;Yujin created Awesome-VideoLLM-Papers repository and keep updating it. [Link](https://github.com/yyyujintang/Awesome-VideoLLM-Papers) ![Stars](https://img.shields.io/github/stars/yyyujintang/Awesome-VideoLLM-Papers)
- *2024.06*: &nbsp;🎉🎉 PatchMixer was accepted by [IJCAI24 DSO Workshop](https://sites.google.com/view/ijcai-2024-dso-workshop)!
- *2024.04*: &nbsp;🎉🎉 VMRNN was accepted by [CVPR24 Precognition Workshop](https://sites.google.com/view/ieeecvf-cvpr2024-precognition)! See you in Seattle(Virtually)!
- *2024.03*: &nbsp;Yujin was invited to give a talk in CUHKSZ in Data Science College. Congratulations to the 10th anniversary of CUHKSZ! 🎉🎉 [Slides](https://docs.google.com/presentation/d/1JyFRflVfvXNLgOVdD7ZGX0llscv4voW8k5qLfsbRSpg/edit?usp=sharing)
- *2024.03*: &nbsp;🎉🎉 PostRainBench was accepted by [ICLR24 Workshop: Tackling Climate Change with Machine Learning](https://www.climatechange.ai/events/iclr2024)! See you in Vienna!
- *2024.01*: &nbsp;Yujin created Awesome-Mamba-Papers repository and keep updating it. [Link](https://github.com/yyyujintang/Awesome-Mamba-Papers) ![Stars](https://img.shields.io/github/stars/yyyujintang/Awesome-Mamba-Papers)
- *2023.07*: &nbsp;🎉🎉 Yujin won Excellence Award in Jinan, Shandong in 0-24 hours Precipitation Nowcasting Challenge! [Slides](https://docs.google.com/presentation/d/1NTxQQr-b-zcBdQkIx42IhUKVZgKbo5U7QDIxCo0q-Qw/edit?usp=sharing)
- *2023.01*: &nbsp;Yujin served as TA for AIAA 5032 Foundations of Artificial Intelligence in HKUSTGZ, Spring 2023, Instructors: Junwei Liang.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR Precognition Workshop, 2024</div><img src='images/VMRNN_Cell.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

VMRNN: Integrating Vision Mamba and LSTM for Efficient and Accurate Spatiotemporal Forecasting

**Yujin Tang**, Peijie Dong, Zhenheng Tang, Xiaowen Chu, Junwei Liang

[ **Paper**](https://arxiv.org/abs/2403.16536) [ **Code**](https://github.com/yyyujintang/VMRNN-PyTorch) ![Stars](https://img.shields.io/github/stars/yyyujintang/VMRNN-PyTorch)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR Workshop, 2024</div><img src='images/PostRainBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

PostRainBench: A comprehensive benchmark and a new model for precipitation forecasting

**Yujin Tang**, Jiaming Zhou, Xiang Pan, Zeying Gong, Junwei Liang

[ **Paper**](https://arxiv.org/abs/2310.02676) [ **Code**](https://github.com/yyyujintang/PostRainBench) ![Stars](https://img.shields.io/github/stars/yyyujintang/PostRainBench)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI DSO Workshop, 2024</div><img src='images/PatchMixer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

PatchMixer: A Patch-Mixing Architecture for Long-Term Time Series Forecasting

Zeying Gong, **Yujin Tang**, Junwei Liang

[ **Paper**](https://arxiv.org/abs/2310.00655) [ **Code**](https://github.com/Zeying-Gong/PatchMixer) ![Stars](https://img.shields.io/github/stars/Zeying-Gong/PatchMixer)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI, 2020</div><img src='images/MICCAI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Ovarian Cancer Prediction in Proteomic Data Using Stacked Asymmetric Convolution

Yuan Cheng, **Yujin Tang**, Dahong Qian

[ **Paper**](https://www.researchgate.net/profile/Cheng_Yuan23/publication/345259179_Ovarian_Cancer_Prediction_in_Proteomic_Data_Using_Stacked_Asymmetric_Convolution/links/6076b0d192851cb4a9dc6f77/Ovarian-Cancer-Prediction-in-Proteomic-Data-Using-Stacked-Asymmetric-Convolution.pd)

</div>
</div>


# 📕 Notes

Diffusion Model Seminar: A Review on Diffusion Models and It's Application in Spatiotemporal Forecasting [Slides](https://drive.google.com/file/d/1_go7vLO6bUg0nBfXFSJkkq_vZOUYHwI6/view?usp=sharing)

AI4Weather Seminar: A Review on FourCastNet/Pangu/GraphCast/Climax/Fenwu [Slides](https://drive.google.com/file/d/1qTaQVBjNFOygmlyk_bBZGUzmoqLv4Iiz/view?usp=sharing)

Course Project for MDS6004 Computer Vision: Deep Rectangling in Irregular Panoramas [Slides](https://drive.google.com/file/d/14nIvXl9K_6RVN7hyPrUhap0ncVW73XHR/view?usp=sharing)

Computer Vision PhD Survival Guide Series(1) CV Paper Tracking and Writing [Link](https://zhuanlan.zhihu.com/p/610774199)

Computer Vision PhD Survival Guide Series(2) Code Release Process and Tools  [Link](https://zhuanlan.zhihu.com/p/611491695)

Computer Vision PhD Survival Guide Series(3) SSH Configuration and Common Linux Command  [Link](https://zhuanlan.zhihu.com/p/676491841)

# 🔗 Resources  for CV Researchers

[Ming-Hsuan Yang-UCM](https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=en): How to Get Your CVPR Paper Rejected? [Link](https://vision.sjtu.edu.cn/files/How-to-get-your-CVPR-paper-rejected.pdf)

[Chao Ma-SJTU](https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=en): Research and Writing Tips for Computer Vision Researchers [Link](https://vision.sjtu.edu.cn/writing.html)

[Sida Peng-ZJU](https://scholar.google.com/citations?hl=zh-CN&user=l9NCksYAAAAJ): The Process of Finishing a Research Project [Link](https://github.com/pengsida/learning_research)

[Bolei Zhou-UCLA](https://scholar.google.com/citations?hl=zh-CN&user=9D4aG8AAAAAJ): How to Make Posters for Top Conference Paper [Link](https://github.com/zhoubolei/bolei_awesome_posters)

[Yana Hasson-Inria](https://scholar.google.com/citations?hl=zh-CN&user=yhz7sFoAAAAJ): Useful Computer Vision PhD Resources [Link](https://github.com/hassony2/useful-computer-vision-phd-resources)

[Bill Freeman-MIT](https://scholar.google.com/citations?user=0zZnyMEAAAAJ&hl=zh-CN): How to Write Papers [Link](https://faculty.cc.gatech.edu/~parikh/citizenofcvpr/static/slides/freeman_how_to_write_papers.pdf) Advice for Graduate Student  [Link](https://people.csail.mit.edu/billf/talks/10minFreeman2013.pdf)

**Thanks a lot to these generous people for sharing their valuable research experience!**

'She is a first-generation college student born in a small city in western China. She constantly overcomes environmental resistance, builds a strong spiritual core, and pushes herself to grow and progress with self-drive and self-discipline. Thinking before practice, iterating quickly in action, she aims to make beneficial changes to the world with artificial intelligence and promote social equity.'

<script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?d=DpZkNL3LsLmeQRxUKn0lTTI5TvgkpddDlnJpErWoftQ&cl=ffffff&w=a"></script>
