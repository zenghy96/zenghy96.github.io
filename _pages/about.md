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
I am currently a Ph.D. candidate in the Biomedical Ultrasound Lab at the ShanghaiTech University, advised by [Prof. Rui Zheng](https://sist.shanghaitech.edu.cn/zhengrui_en/main.htm).

I received a B.Eng. degree in the School of Information Science and Technology at Dalian Maritime University in 2018.

I was a visiting student (2023-2024) at Institute of High Performance Computing (IHPC), A*STAR, Singapore, advised by [Dr. Huazhu Fu](https://hzfu.github.io/).

My research interest lies in the interdisciplinary fields of **medical data analysis** and **computer vision**, aiming to create intelligent systems that improve clinical decision-making.

Recently, I am dedicated to multi-modal learning with vision and text in ultrasound images, domain adaptation between different imaging systems and diffusion model for medical data.

Previously, I focused on developing deep learning solutions for 3D ultrasound spine images, including seme-supervised learning, domain adaptation, and multi-modal modeling imaging, to achieve intelligent diagnosis and accurate imaging of the spine.
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 
## 3D Ultrasound Spine Images
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TUFFC, 2021</div><img src='images/GVF.png' alt="sym" width='100%'></div></div>
<div class='paper-box-text' markdown="1">

[Automatic detection and measurement of spinous process curve on clinical ultrasound spine images](https://ieeexplore.ieee.org/abstract/document/9309263)

**Hongye Zeng**, Edmond Lou, Songhan Ge, Zhichao Liu, Rui Zheng
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE JBHI, 2024</div><img src='images/vertmatch_.png' alt="sym" width='100%'></div></div>
<div class='paper-box-text' markdown="1">

[Anatomical Prior and Inter-slice Consistency for Semi-supervised Vertebral Structure Detection in 3D Ultrasound Volume](https://ieeexplore.ieee.org/abstract/document/10416650)

**Hongye Zeng**, Kang Zhou, Songhan Ge, Yuchong Gao, Jianhao Zhao, Shenghua Gao, Rui Zheng
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IUS 2022</div><img src='images/modeling.png' alt="sym" width='100%'></div></div>
<div class='paper-box-text' markdown="1">

[3D Ultrasound Parametric Modeling Imaging for Spine Deformity – A Preliminary Study](https://ieeexplore.ieee.org/abstract/document/9958051)

Yuchong Gao, **Hongye Zeng**, Jianhao Zhao, Mingbo Zhang, Rui Zheng
</div>
</div>

<ul>
<li><code class="language-plaintext highlighter-rouge">IUS 2021</code><a href="https://ieeexplore.ieee.org/abstract/document/9593791/"> Measurement of Spinous Process Angles on Ultrasound Spine Images using HR-Net Method</a>, Wenjie Shao,<strong>Hongye Zeng</strong>,Yuchong Gao,Kang Zhang,Rui Zheng</li>
<li><code class="language-plaintext highlighter-rouge">IUS 2021</code><a href="https://ieeexplore.ieee.org/abstract/document/9593869"> Indicating Lung Maturity of Preterm Births on LUS Images using the GLCM Statistical Properties---A Pilot Study</a>, Duo Xu,<strong>Hongye Zeng</strong>,Jiangqin Liu,Shanshan Wang,Rui Zheng</li>
<li><code class="language-plaintext highlighter-rouge">IEEE TUFFC</code> <a href="https://ieeexplore.ieee.org/abstract/document/9449836"> Improvement of 3-D ultrasound spine imaging technique using fast reconstruction algorithm</a>, Hongbo Chen,Rui Zheng,Liyue Qian,Fengyu Liu,Sheng Song,<strong>Hongye Zeng</strong></li>
<li><code class="language-plaintext highlighter-rouge">EMBC 2020</code> <a href="https://ieeexplore.ieee.org/abstract/document/9176211"> Measuring spinous process angle on ultrasound spine images using the GVF segmentation method</a>, Songhan Ge,<strong>Hongye Zeng</strong>,Rui Zheng</li>
<li><code class="language-plaintext highlighter-rouge">IUS 2019</code> <a href="https://ieeexplore.ieee.org/abstract/document/8925710"> Measuring spinous process angle on ultrasound spine images using the GVF segmentation method</a>, <strong>Hongye Zeng</strong>,Rui Zheng,Lawrence H Le,Dean Ta</li>
</ul>



## Domain adaptation
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/tisa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Training-free image style alignment for self-adapting domain shift on handheld ultrasound devices](https://arxiv.org/abs/2402.11211)

**Hongye Zeng**, Ke Zou, Zhihao Chen, Yuchong Gao, Hongbo Chen, Haibin Zhang, Kang Zhou, Meng Wang, Rick Siow Mong Goh, Yong Liu, Chang Jiang, Rui Zheng, Huazhu Fu
</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 🗣 Activities
## Reviewers
- IEEE Journal of Biomedical and Health Informatics
- Scientific Reports
- ICIP 2023

## Presentations
- 2019.10, International Ultrasonics Symposium, Glasgow, UK

## Teaching
- CS270 Digital Image Processing, Spring 2019, Fall 2019, TA
- EE101 Fundamentals of Medical Imaging, Spring 2020, TA

# 📖 Educations
- *2018.09 - 2024.06 (now)*, Ph.D, ShanghaiTech University, Shanghai.
- *2014.09 - 2018.06*, B.E, Dalian Maritime University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experiences
- *2023.02 - 2024.02*, Visiting student, Institute of High Performance Computing (IHPC), A*STAR, Singapore, advised by [Dr. Huazhu Fu](https://hzfu.github.io/).
