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

I am an incoming phd student in Columbia University, advised by [Prof. Fred Jiang](http://fredjiang.com/). I obtained my master degree from Control Science and Engineering College, Zhejiang University in 2024, advised by [Prof. Chaojie Gu](https://chaojiegu.github.io/) and [Prof. Shibo He](https://person.zju.edu.cn/en/shibohe). I also work with [Prof. Rui Tan](https://personal.ntu.edu.sg/tanrui/), Nanyang Technological University.
I received my B.E. degree from Control Science and Engineering College, Zhejiang University in 2021.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->
<!-- &nbsp; -->

<!-- My research interest is **mobile sensing and AIoT (AI + Internet of Things)**, with a primary focus on related fields of developing artificial intelligence sensing systems for human's daily lives.
My current research focuses on wireless-based sensing and wearable-based sensing, including human activity recognition, authentication, etc. -->

<!-- My research insterests are centered around **mobile sensing and AIoT** (AI + Internet of Things), with a primary focus on developing artificial intelligence sensing systems for practical applications, including human activity recognition, gesture interaction, etc. -->

My research insterests are centered around **mobile sensing and IoT**, with a primary focus on developing sensing systems for practical applications, including human activity recognition, gesture interaction, etc.

<!-- [[CV](Lilin_CV_2310.pdf)] -->

# News
- [2024.04] &nbsp; One paper \[**GesturePrint**\] is accepted by ICDCS 2024.
- [2023.10] &nbsp; I have been selected for SenSys'23 SIG Travel Grant.
- [2023.10] &nbsp; One workshop paper is accepted to SenSys 2023.
- [2023.09] &nbsp; One paper \[**MESEN**\] is conditionally accepted by SenSys 2023.
- [2023.06] &nbsp; One paper \[**NARQ2T**\] is accpected by IEEE Transactions on Circuits and Systems for Video Technology. 

# Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SenSys 2023</div><img src='images/MESEN.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

MESEN: Exploit Multimodal Data to Design Unimodal Human Activity Recognition with Few Labels

**<u>Lilin Xu</u>**, Chaojie Gu, Rui Tan, Shibo He, Jiming Chen

The 21th ACM Conference on Embedded Networked Sensor Systems (**SenSys 2023**).

(Acceptance ratio: 34/179=19%)

[[**Paper**](https://drive.google.com/file/d/1z3DZaSQvA-oUVUvesE5iM2RwUgTo0zAQ/view?usp=sharing)]
[[**Slides**](https://docs.google.com/presentation/d/1_NbLg2o-9lMAXxzXM5yYzomzu6LxZIQf/edit#slide=id.p24)]
</div>
</div>

<!-- &nbsp; -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">mmWaveSys 2023</div><img src='images/GesturePrint.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[Work in Progress: Enabling User Identification for mmWave-based Gesture Recognition Systems (Short paper)](https://dl.acm.org/doi/10.1145/3628357.3629711)

**<u>Lilin Xu</u>**, Keyi Wang, Chaojie Gu, Shibo He, Jiming Chen

The first ACM workshop on mmWave sensing systems and applications (**SenSys Workshop mmWaveSys 2023**)

[[**Paper**](https://drive.google.com/file/d/1m3BrvqYERVlSR_E8-ENc6vfz94C7qlUa/view)]

</div>
</div>


<!-- &nbsp; -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TCSVT</div><img src='images/NARQ2T.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[Latency-aware Neural Architecture Performance Predictor with Query-to-Tier Technique](https://ieeexplore.ieee.org/document/10155437)

Bicheng Guo\*, **<u>Lilin Xu</u>**\* (*equal contribution), Tao Chen, Peng Ye, Shibo He, Haoyu Liu, Jiming Chen

IEEE Transactions on Circuits and Systems for Video Technology (**TCSVT**, 2023)

[[**Paper**](https://drive.google.com/file/d/1my_zXp_wpNwXOfPox-A2T4YoeUsGF8h-/view?usp=drive_link)]
</div>
</div>


<!-- 
&nbsp; -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='images/NAR.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized Global Ranking-Aware Neural Architecture Ranker for Efficient Image Classifier Search](https://dl.acm.org/doi/abs/10.1145/3503161.3548149)

Bicheng Guo, Tao Chen, Shibo He, Haoyu Liu, **<u>Lilin Xu</u>**, Peng Ye, Jiming Chen

The 30th ACM International Conference on Multimedia (**ACM MM**, 2022)

[[**Paper**](https://drive.google.com/file/d/1Ns9GyJbPe8egdb5EfwczCnfLWlSSTONJ/view?usp=drive_link)]
</div>
</div>




# Selected Awards
- Columbia University Presidential Fellowship, 2024.
- Zhejiang University Sun Youxian Scholarship (**Top 1%**), 2024.
- Zhejiang University Outstanding Graduate Student, 2024.
<!-- - Zhejiang University Wen Chixiang Scholarship, 2023. -->
- SenSys'23 SIG Travel Grant, 2023.
- Zhejiang University Award of Honor for Graduate, 2022 and 2023.
<!-- - AI Studio 2022 CVPR Track2: Performance Estimation Track, Top 10 Award (8/190), 2022.  -->
- Academic Excellence First-prize Scholarship, 2022 and 2023. 
- Zhejiang University First-prize Scholarship (**Top 3%**), 2019.
- Zhejiang University Second-prize Scholarship, 2018 and 2020. 

# Educations
- *2021.09 - 2024.03*, Master, advised by [Prof. Chaojie Gu](https://chaojiegu.github.io/) and [Prof. Shibo He](https://person.zju.edu.cn/en/shibohe), [Group of Networked Sensing and Control (NeSC)](http://nesc.zju.edu.cn/#/), Zhejiang University, Hangzhou. (GPA: 3.91/4.0)
- *2017.09 - 2021.06*, Undergraduate, Control Science and Engineering College, Zhejiang Univeristy, Hangzhou. (GPA: 3.95/4.0, Rank: 5/120)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# Visiting Experience
- *2023.04 - 2023.10*, Visiting Research Student, advised by [Prof. Rui Tan](https://personal.ntu.edu.sg/tanrui/), [NTU IoT Research Group](https://ntuiot.xyz/), Nangyang Technological University, Singapore.

# Professional Services
- Web Chair of ACM SenSys 2024