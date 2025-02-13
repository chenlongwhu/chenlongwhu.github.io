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

I am a frist-year PhD student in the [LIESMARS](https://liesmars.whu.edu.cn/), [Wuhan University](https://www.whu.edu.cn/). My advisors are Prof. [Zhen Dong](https://dongzhenwhu.github.io/index.html) and Prof. [Bisheng Yang](https://3s.whu.edu.cn/info/1025/1415.htm).  Previously, I obtained my B.Eng degree at [SGG](http://main.sgg.whu.edu.cn/) of Wuhan University.

My research interest lies in the field of 3D Computer Vision, particularly including point cloud enhancement (upsampling, denoising, completion , etc), 3D shape restoration. Besides, I am conducting some researches related to urban sustainable development. If you are interested in my research, feel free to contact me at <chenlong107@whu.edu.cn>!

I am a member of [WHU-USI3DV](https://github.com/WHU-USI3DV), please check advancements on point cloud processing including enhancement, registration, localization, segmentation, detection, etc.

# 🔥 News
- *2025.02*: &nbsp;🎉🎉 Co-first author paper [WHU-Synthetic: A Synthetic Perception Dataset for 3D Multi-task Model Research](https://doi.org/10.1109/TGRS.2025.3541072) is accepted by TGRS.
- *2024.11*: &nbsp;🎉🎉 Co-author paper [INF-PCA: Implicit Neural Field-Based Interactive Point Cloud Semantic Annotation](https://doi.org/10.1109/TITS.2024.3496938) is accepted by TITS.
- *2024.07*: &nbsp;🎉🎉 Co-first author paper [EGIINet: Explicitly Guided Information Interaction Network for Cross-modal Point Cloud Completion](https://arxiv.org/pdf/2407.02887) is accepted by ECCV 2024!
- *2024.05*: &nbsp;🎉🎉 Our paper [SparseDC: Depth Completion From Sparse and Non-uniform Inputs](https://doi.org/10.1016/j.inffus.2024.102470) is accepted by Informarion Fusion!

# 📝 Publications
\* denotes equal contributions and † denotes the corresponding author.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2025</div><img src='images/WHU_Synthetic.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

WHU-Synthetic: A Synthetic Perception Dataset for 3D Multi-task Model Research

Jiahao zhou<sup>*</sup>, **Chen Long<sup>*</sup>**, Yue Xie, Jialiang Wang, Conglang Zhang, Boheng Li, Haiping Wang, Zhen Chen<sup>&dagger;</sup>, Zhen Dong

<span style="color:red">**TGRS 2025 (IF:7.5)**</span>

[[Paper]](https://doi.org/10.1109/TGRS.2025.3541072)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2024</div><img src='https://liuchong-911.github.io/images/INF-PCA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

INF-PCA: Implicit Neural Field-Based Interactive Point Cloud Semantic Annotation

Chong Liu<sup>*</sup>, Xu Han<sup>*</sup>, Weihong Huang, **Chen Long**, Wang Wang, Zhen Dong<sup>&dagger;</sup>, Bisheng Yang

<span style="color:red">**TITS 2024 (IF:7.9)**</span>

[[Paper]](https://doi.org/10.1109/TITS.2024.3496938)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='https://dongzhenwhu.github.io/publications/teasers/Explicitly_Guided.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Explicitly Guided Information Interaction Network for Cross-modal Point Cloud Completion

Hang Xu<sup>*</sup>, **Chen Long<sup>*</sup>**, Wenxiao Zhang<sup>&dagger;</sup>, Yuan Liu, Zhen Cao, Zhen Dong, Bisheng Yang

<span style="color:red">**ECCV 2024 (CCF-B)**</span>

[[Paper]](https://arxiv.org/pdf/2407.02887), [[Code]](https://github.com/WHU-USI3DV/EGIInet)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Information Fusion</div><img src='https://dongzhenwhu.github.io/publications/teasers/sparseDC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SparseDC: Depth Completion From Sparse and Non-uniform Inputs

**Chen Long**, Wenxiao Zhang, Zhe Chen, Haiping Wang, Yuan Liu, Peiling Tong, Zhen Cao, Zhen Dong<sup>&dagger;</sup>, Bisheng Yang

<span style="color:red">**Information Fusion (IF: 18.6)**</span>

[[Paper]](https://doi.org/10.1016/j.inffus.2024.102470), [[Code]](https://github.com/WHU-USI3DV/SparseDC)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='https://dongzhenwhu.github.io/publications/teasers/PC2-PU.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

PC²-PU: Patch Correlation and Point Correlation for Effective Point Cloud Upsampling

**Chen Long<sup>*</sup>**, WenXiao Zhang<sup>*</sup>, Ruihui Li<sup>&dagger;</sup>, Hao Wang, Zhen Dong, Bisheng Yang

<span style="color:red">**ACM MM 2022 (CCF-A)**</span>

[[Paper]](https://doi.org/10.1145/3503161.3547777), [[Code]](https://github.com/chenlongwhu/PC2-PU)
</div>
</div>

# 🎖 Honors and Awards
- *2024.10*, 获得武汉大学优秀研究生称号
- *2024.05*, 中国第一届空间信息技术及产业发展大会 "优秀学生报告(硕博生)"。

# 💬 Conference oral presentation
- *2024.05*, 中国第一届空间信息技术及产业发展大会
- *2022.08*, 中国第七届计算机图形学与混合现实前沿研讨会
