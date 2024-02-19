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

# 👋 About Me
I am a second-year Ph.D. student in the ML program of Geogia Tech advised by [Prof. Pan Li](https://sites.google.com/view/panli-purdue/home?authuser=0). Prior to that, I received my B.S. degree (Stat, Math and Computer Science) and my M.S. degree (Computer Science) both from Purdue University. 

My research mainly focuses on the trustworthy graph/geometric learning (domain adaptation/out-of-distribution generalization) with applications in scientific problems.  


# 🔥 News
- *2023.04*: &nbsp;🎉🎉 Our paper [StruRW](https://proceedings.mlr.press/v202/liu23u.html) gets accepted by ICML'23! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/StruRW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Structural Re-weighting Improves Graph Domain Adaptation](https://arxiv.org/abs/2306.03221) \\
**Shikun Liu**, Tianchun Li, Yongbin Feng, Nhan Tran, Han Zhao, Qiu Qiang, Pan Li. **ICML 2023**\\
<a href="https://arxiv.org/abs/2306.03221"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/StruRW"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>

<!-- <a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> -->
<!-- <a href="https://proceedings.mlr.press/v162/miao22a.html"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2722&color=blue"> </a> -->

</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
