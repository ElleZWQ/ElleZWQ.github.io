---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  h1 { font-size: 28px !important; }
  h2 { font-size: 24px !important; }
  h3 { font-size: 20px !important; }
  p, li { font-size: 18px !important; }
  .paper-box-text { font-size: 14px !important; }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a 4th-year Ph.D. student of artificial intelligence at [Xi'an Jiaotong University](http://www.aiar.xjtu.edu.cn/), advised by Prof. [Badong Chen](https://gr.xjtu.edu.cn/web/chenbd), and I am part of the National Key Laboratory of Human-Machine Hybrid Augmented Intelligenceled by [Nanning Zheng](https://scholar.google.com.hk/citations?user=iqMe3p8AAAAJ&hl=zh-CN) (IEEE Fellow, Membership of Chinese Academy of Engineering). 
During the period from 2023.11.01 to 2024.10.31, I worked in Advanced Intelligence Project ([AIP](https://www.riken.jp/en/research/labs/aip/)) of RIKEN center for joint IPA project, advised by Prof. [Qibin Zhao](https://www.riken.jp/en/research/labs/aip/generic_tech/tensor_learn/index.html). Prior to this, I completed a three-month internship in the same team.
I was also very glad to have the opportunity to work with [Danilo P. Mandic](https://scholar.google.co.uk/citations?user=hcxWZkcAAAAJ&hl=en).
Previously, I obtained my bachelor’s degree from Shandong University in 2019. 
<!-- I am currently serving as a visiting student at the [MiLab](https://milab.westlake.edu.cn/index.html) at Westlake University, advised by Prof. [Donglin Wang](https://scholar.google.com/citations?user=-fo6wdwAAAAJ&hl=zh-CN).  -->

🔭 My research interests lie in reliable machine learning, such as causal discovery, generalization in computer vision, adversarial learning.

✉️ Welcome to contact me for any discussion and cooperation!

💻 I am currently seeking a Job position to further advance my research. If you happen to be aware of any relevant opportunities, I would be very grateful if you could let me know.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=xhd94DIAAAAJ&hl=zh-CN'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=xhd94DIAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- \[2025/03\]: One [paper](https://www.sciencedirect.com/science/article/pii/S0893608025002965) on causal discovery got accepted by Neural Networks 2025.
- \[2024/12\]: One paper ([PromptTA](https://arxiv.org/abs/2409.14163)) on source-free domain generalization got accepted by ICASSP 2025.
- \[2024/07\]: One paper ([SPG](https://arxiv.org/abs/2404.19286)) on VLM-based domain generalization got accepted by ECCV 2024.
- \[2024/05\]: One paper ([JRNGC](https://arxiv.org/abs/2405.08779)) on causal discovery got accepted by ICML 2024.
- \[2023/12\]: One paper ([PDA](https://arxiv.org/abs/2312.09553)) on VLM-based unsupervised domain adaptation got accepted by AAAI 2024, and one [Paper](https://arxiv.org/abs/2312.09589) on cross-domain few-shot classification got accepted by ICASSP 2024.




# 📝 Publications 
<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/nn-2025-mee.jpg" alt="MEE" style="width: 200px; height: 100px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">An Information-Theoretic Approach for Heterogeneous Differentiable Causal Discovery</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Wanqi Zhou</u></strong>, Shuanghao Bai, Yuqing Xie, Yicong He, Qibin Zhao, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">Neural Networks 2025</p>
    <p style="margin: 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0893608025002965">Paper</a> |
      <a href="https://github.com/ElleZWQ/MHCD">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/arxiv-2025-bcib.gif" alt="BCIB" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Rethinking Latent Representations in Behavior Cloning: An Information Bottleneck Approach for Robot Manipulation</h3>
    <p style="margin: 0 0 10px 0;">Shuanghao Bai, <strong><u>Wanqi Zhou</u></strong>, Pengxiang Ding, Wei Zhao, Donglin Wang, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">arXiv 2025</p>
    <p style="margin: 0;">
      <a href="https://arxiv.org/abs/2502.02853">arXiv</a> | 
      <a href="https://baishuanghao.github.io/BC-IB.github.io/">Project</a> | 
      <a href="https://github.com/BaiShuanghao/BC-IB">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/icassp-2025-promptta.jpg" alt="PromptTA" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">PromptTA: Prompt-driven Text Adapter for Source-free Domain Generalization</h3>
    <p style="margin: 0 0 10px 0;">Haoran Zhang*, Shuanghao Bai*, <strong><u>Wanqi Zhou</u></strong>, Jingwen Fu, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">ICASSP 2025</p>
    <p style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/abstract/document/10888057">Paper</a> |
      <a href="https://arxiv.org/abs/2409.14163">arXiv</a> | 
      <a href="https://github.com/zhanghr2001/PromptTA">Code</a></p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/arxiv-2024-mmcoa.jpg" alt="MMCoA" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Revisiting the Adversarial Robustness of Vision Language Models: a Multimodal Perspective</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Wanqi Zhou*</u></strong>, Shuanghao Bai*, Danilo P. Mandic, Qibin Zhao, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">arXiv 2024</p>
    <p style="margin: 0;">
      <a href="https://arxiv.org/abs/2404.19287">arXiv</a> | 
      <a href="https://github.com/ElleZWQ/MMCoA">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/eccv-2024-spg.jpg" alt="SPG" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Soft Prompt Generation for Domain Generalization</h3>
    <p style="margin: 0 0 10px 0;">Shuanghao Bai*, Yuedi Zhang*, <strong><u>Wanqi Zhou</u></strong>, Yicong He, Zhirong Luan, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">ECCV 2024</p>
    <p style="margin: 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-72646-0_25">Paper</a> | 
      <a href="https://arxiv.org/abs/2404.19286">arXiv</a> | 
      <a href="https://github.com/renytek13/Soft-Prompt-Generation">Code</a> | 
      <a href="https://zhuanlan.zhihu.com/p/719329220">Chinese Intro</a></p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/icml-2024-jrngc.jpg" alt="JRNGC" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Jacobian Regularizer-based Neural Granger Causality</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Wanqi Zhou</u></strong>, Shuanghao Bai, Shujian Yu, Qibin Zhao, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">ICML 2024</p>
    <p style="margin: 0;">
      <a href="https://proceedings.mlr.press/v235/zhou24a.html">Paper</a> | 
      <a href="https://arxiv.org/abs/2405.08779">arXiv</a> |
      <a href="https://github.com/ElleZWQ/JRNGC">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/aaai-2024-pda.jpg" alt="PDA" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Prompt-based Distribution Alignment for Unsupervised Domain Adaptation</h3>
    <p style="margin: 0 0 10px 0;">Shuanghao Bai, Min Zhang, <strong><u>Wanqi Zhou</u></strong>, Siteng Huang, Zhirong Luan, Donglin Wang, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">AAAI 2024</p>
    <p style="margin: 0;">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/27830">Paper</a> |
      <a href="https://arxiv.org/abs/2312.09553">arXiv</a> | 
      <a href="https://github.com/BaiShuanghao/Prompt-based-Distribution-Alignment">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/icassp-2024-mlp.jpg" alt="MLP" style="width: 200px; height: 80px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Improving Cross-domain Few-shot Classification with Multilayer Perceptron</h3>
    <p style="margin: 0 0 10px 0;">Shuanghao Bai, <strong><u>Wanqi Zhou</u></strong>, Zhirong Luan, Donglin Wang, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">ICASSP 2024</p>
    <p style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/abstract/document/10447065/">Paper</a> |
      <a href="https://arxiv.org/abs/2312.09589">arXiv</a> |
      <a href="https://github.com/BaiShuanghao/CDFSC-MLP">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/ins-2022-te.jpg" alt="TE" style="width: 200px; height: 80px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Causality Detection with Matrix-based Transfer Entropy</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Wanqi Zhou</u></strong>, Shujian Yu, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">INS 2022</p>
    <p style="margin: 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0020025522010830">Paper</a> | 
      <a href="https://github.com/zwq2/MTE_causal">Code</a>
      </p>
  </div>
</div>


<!-- - <img src="https://img.shields.io/badge/CVPR-2020-blue?style=flat-square"> <u>A</u>, B, C, <strong>Paper Name</strong>, <em>In CVPR 2020</em>. -->

_* denotes equal contribution._

# 🏅 Honors and Awards
* Outstanding Graduate Student, Xi'an Jiaotong University, 2023, 2022
* National First Prize in the BCI Brain-Controlled Robot Competition at the 2021 World Robot Competition, 2021
* Outstanding Graduate Student Cadres, Xi’an Jiaotong University, 2020
* Outstanding Undergraduate Graduates, Shandong University, 2019
* National Scholarship, 2018
* Provincial First Prize in the National Undergraduate Mathematical Modeling Competition
* National Scholarship,2016

# 📖 Professional services
## Conference Reviewer
* CVPR 2025, AAAI 2025, ACML 2024, ICDM 2024, ACM MM 2024

## Journal Reviewer
* TNNLS

<!-- 
# 📖 Work experience
* March 2021 - Now: Research Assistant
  * Microsoft Research Asia, Beijing, China.
  * Duties included: 1. Design more powerful and simple object detection architecture based on the Transformer. 2. Understand NLP tasks such as NLI and exploit new paradigms to solve them more efficiently.
  * Advisor: Prof. [Jingdong Wang](https://jingdongwang2017.github.io/)

* August 2020 - Now: Research Assistant
  * University of Chinese Academy of Sciences, Beijing, China.
  * Duties included: 1. learning deep generative model for pedestrian generation. 2. cross-domain Re-ID from a causal view. 3. designing an efficient method to tackle problems in object detection and partial pedestrian re-identification.
  * Advisor: Prof. [Tieniu Tan](http://people.ucas.ac.cn/~tantieniu)
  * Co-Advisors: Prof. [Zhang Zhang](https://scholar.google.com/citations?user=rnRNwEMAAAAJ&hl=en) and Prof. [Liang Wang](https://scholar.google.com/citations?user=8kzzUboAAAAJ&hl=zh-CN)

* April 2018 – July 2020: Research Assistant
  * South China University of Technology, Guangzhou, China.
  * Duties included: Incentive mechanism design for crowdsourcing platforms, edge computing
platforms, and federal learning platforms.
  * Advisor: Prof. Xinglin Zhang
 -->


<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
 -->


<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=V1s6bHv5YoOUdWy_xe51WDGQ7ssAbRpDmruXR6D4I9Q&cl=ffffff&w=a"></script> -->

<!-- <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=V1s6bHv5YoOUdWy_xe51WDGQ7ssAbRpDmruXR6D4I9Q&w=150&h=150&t=light&cmo=#FF5588&cmn=#88FF55"></script> -->

<div style="display: flex; justify-content: center; align-items: center; height: 200px;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=1pTG0F_YNqjOwWHVuzu9bdtg51FIdqFqyj-hriK-W2E&w=150&h=150&t=light&cmo=#FF5588&cmn=#88FF55"></script>
</div>