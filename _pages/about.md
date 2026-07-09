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
I am a fourth-year Ph.D. student in the ML program of Geogia Tech advised by [Prof. Pan Li](https://sites.google.com/view/panli-purdue/home?authuser=0). Prior to that, I received my B.S. degree (Stat, Math and Computer Science) and my M.S. degree (Computer Science) both from Purdue University. 

My research focuses on large language models, AI agents, and trustworthy machine learning, with a particular focus on structured information, including graph- and network-structured data, time series, etc.

Specifically, my work spans topics in two main directions:

- **LLMs and AI Agents:** multi-agent system, KV-cache manipulation, post-training, context management, and agentic data analysis.
- **Trustworthy ML:** domain adaptation, out-of-distribution generalization, test-time adaptation and robust fine-tuning of foundation models, for reliable graph/geometric learning.

Also, I am currently open to full-time and internship opportunities. Please feel free to reach out about any relevant opportunities!


# 🔥 News
- *2026.07*: &nbsp;🎉🎉 Our paper [Struc-EMB](https://arxiv.org/abs/2510.08774) is accepted by COLM'26! Thanks to all my collaborators.
- *2026.06*: &nbsp; Our paper [Parallel-Synthesis](https://arxiv.org/abs/2606.14672) and [KVEraser](https://arxiv.org/abs/2606.17034) (lead by [Mufei](https://mufeili.github.io/)) are now available on arXiv. Feel free to check them out!
- *2026.05*: I’m starting as a Research Scientist Intern at Meta Central Applied Science team, based in Menlo Park, CA. Would love to connect if you are around:)
- *2026.01*: &nbsp;🎉🎉 Our paper [TSA](https://arxiv.org/abs/2502.18334) (lead by [Hans](https://hans66hsu.github.io/)) gets accepted by AISTATS'26!
- *2025.09*: &nbsp;🎉🎉 Our paper [Roft-Mol](https://arxiv.org/abs/2509.00614) and the [Graph-KV](https://arxiv.org/abs/2506.07334) lead by Haoyu gets accepted by NeurIPS'25, thanks to all my collaborators and congratulations to Haoyu and all co-authors! See you in San Diego:)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv </div><img src='images/Parallel-Synthesis.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Direct Latent-Space Synthesis for Parallel Branches in LLM-Agent Workflows](https://arxiv.org/abs/2606.14672) \\
Shikun Liu, Mufei Li, Dongqi Fu, Haoyu Wang, Yinglong Xia, Hong Li, Hong Yan, Pan Li\\
<a href="https://arxiv.org/abs/2606.14672"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv </div><img src='images/KVEraser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KVEraser: Learning to Steer KV Cache for Efficient Localized Context Erasings](https://arxiv.org/abs/2606.17034) \\
Mufei Li, Shikun Liu, Dongqi Fu, Haoyu Wang, Yinglong Xia, Hong Li, Hong Yan, Pan Li\\
<a href="https://arxiv.org/abs/2606.17034"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLM 2026 </div><img src='images/Struc-Emb.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Struc-EMB: The Potential of Structure-Aware Encoding in Language Embeddings](https://arxiv.org/abs/2510.08774) \\
**Shikun Liu**, Haoyu Wang, Mufei Li, Pan Li. \\
<a href="https://arxiv.org/abs/2510.08774"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/Struc-Emb"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 D&B </div><img src='images/Roft-Mol.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[RoFt-Mol: Benchmarking Robust Fine-Tuning with Molecular Graph Foundation Models](https://arxiv.org/abs/2509.00614) \\
**Shikun Liu\***, Deyu Zou\*, Nima Shoghi, Victor Fung, Kai Liu, Pan Li. **NeurIPS 2025 D&B (spotlight)**\\
<a href="https://arxiv.org/abs/2509.00614"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/RoFt-Mol"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 </div><img src='images/graphkv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Graph-KV: Breaking Sequence via Injecting Structural Biases into Large Language Models](https://arxiv.org/abs/2506.07334) \\
Haoyu Wang, Peihao Wang, Mufei Li, **Shikun Liu**, Siqi Miao, Zhangyang Wang, Pan Li. **NeurIPS 2025**\\
<a href="https://arxiv.org/abs/2506.07334"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/GraphKV"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AISTATS 2026 </div><img src='images/TSA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Structural Alignment Improves Graph Test-Time Adaptation](https://arxiv.org/abs/2502.18334) \\
Hans Hao-Hsun Hsu\*, **Shikun Liu\***, Han Zhao, Pan Li. \\
<a href="https://arxiv.org/abs/2502.18334"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/TSA"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025 </div><img src='images/LLM-BP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Model generalization on text attribute graphs: Principles with large language models](https://arxiv.org/abs/2502.11836) \\
Haoyu Wang, **Shikun Liu**, Rongzhe Wei, Pan Li. **ICML 2025**\\
<a href="https://arxiv.org/abs/2502.11836"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/LLM_BP"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024 </div><img src='images/Pair-Align.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pairwise Alignment Improves Graph Domain Adaptation](https://arxiv.org/abs/2403.01092) \\
**Shikun Liu**, Deyu Zou, Han Zhao, Pan Li. **ICML 2024 (spotlight)** \\
<a href="https://arxiv.org/abs/2403.01092"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/Pair-Align"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 D&B</div><img src='images/gdlds.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GeSS: Benchmarking Geometric Deep Learning under Scientific Applications with Distribution Shifts]([https://arxiv.org/abs/2310.08677](https://proceedings.neurips.cc/paper_files/paper/2024/hash/a8063075b00168dc39bc81683619f1a8-Abstract-Datasets_and_Benchmarks_Track.html)) \\
Deyu Zou\*, **Shikun Liu\***, Siqi Miao, Victor Fung, Shiyu Chang, Pan Li. **NeurIPS 2024 Dataset and Benchmark**\\
<a href="https://arxiv.org/abs/2310.08677"><img src="https://img.shields.io/badge/-arXiv-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/Graph-COM/GDL_DS"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/StruRW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Structural Re-weighting Improves Graph Domain Adaptation](https://arxiv.org/abs/2306.03221) \\
**Shikun Liu**, Tianchun Li, Yongbin Feng, Nhan Tran, Han Zhao, Qiu Qiang, Pan Li. **ICML 2023**\\
<a href="https://proceedings.mlr.press/v202/liu23u.html"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2723&color=blue"></a>
<a href="https://github.com/Graph-COM/StruRW"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>

</div>
</div>


[Semi-supervised graph neural networks for pileup noise removal](https://link.springer.com/article/10.1140/epjc/s10052-022-11083-5) \\
Tianchun Li\*, **Shikun Liu\***, Yongbin Feng\*, Garyfallia Paspalaki, Nhan V. Tran, Miaoyuan Liu, Pan Li **The European Physical Journal C** and **NeurIPS 2021 AI4Science**
<a href="https://link.springer.com/article/10.1140/epjc/s10052-022-11083-5"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=EPJC&color=blue"></a>
<a href="https://openreview.net/forum?id=kTIngiqLU-X"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=NeurIPS%2721&color=blue"></a>


<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
