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

# About Me

I am a third-year Software Engineering undergraduate at [**Sichuan University (SCU)**](http://www.scu.edu.cn/). Under the supervision of [**Prof. Tao He**](https://ithet1007.github.io/), I previously investigated robust medical image segmentation, with a focus on **Ordinary Differential Equations (ODEs)** and **Test-Time Adaptation (TTA)**. I am currently a remote research intern with [**Prof. Yuzhang Shang**](https://42shawn.github.io/) at [**University of Central Florida (UCF)**](https://www.ucf.edu/), where my interests center on **Vision-Language-Action (VLA)** models, particularly on enhancing their reasoning and generation capabilities.

**I am actively seeking Fall 2027 Ph.D. opportunities to further explore VLA and generalization.**


**Email**: xutianqi@stu.scu.edu.cn / tianqixu692@gmail.com

[**[CV]**](files/CV.pdf)


# 🔥 News
- Jan. 20–27, 2026: Attended **AAAI 2026** in Singapore on behalf of our team to deliver a poster presentation for **CNM-UNet**.
- Nov. 2025: Our work **CNM-UNet** is accepted at **AAAI 2026**. 

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAAI 2026</div>
      <img src='images/CNM-UNet_image.png' alt="CNM-UNet" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

### [CNM-UNet: Continuous Ordinary Differential Equations for Medical Image Segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/38122)
**Tianqi Xu**, Yashi Zhu, Quansong He, Yue Cao, Kaishen Wang, Zhang Yi, Tao He
*Proceedings of the AAAI Conference on Artificial Intelligence (**AAAI**), 2026*

[**Paper**](files/CNM-UNet_paper.pdf) | [**Code**](https://github.com/Tianqi04/CNM-UNet) | [**Poster**](files/CNM-UNet_poster.png)

- Proposed CNM-UNet, which replaces vanilla hierarchical decoders with a single Continuous Neural Memory ODEs Block to reduce computational overhead.
- Leveraged Neural Memory ODEs (nmODEs) for continuous-time feature extraction, achieving precise data distribution modeling.
- Designed a Dual Self-updating (DUSE) strategy based on Test-time Adaptation (TTA) principles to enhance cross-domain generalization.
</div>
</div>

# 🎖 Honors and Awards
- *2023-2025* **Merit Student Award** (Consecutive 2 Years), Sichuan University. 
- *2023--2024* **Second-class Comprehensive Academic Scholarship** (Top 6%), Sichuan University.
- *2024--2025* **Third-class Comprehensive Academic Scholarship** (Top 15%), Sichuan University.

---
> Thanks to [RayeRen](https://github.com/RayeRen/acad-homepage.github.io) for the template.