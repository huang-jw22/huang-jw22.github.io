---
permalink: /
title: ""
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
I'm a first-year M.S. student in [Electrical Engineering](https://ee.stanford.edu/) at **Stanford University**. I received my B.Eng. from [Weixian College](https://www.wxc.tsinghua.edu.cn/) and [School of Biomedical Engineering, Tsinghua University](https://www.med.tsinghua.edu.cn/en/) in 2026.

During my undergraduate years, I was a research assistant at [BIRTH Lab](https://birthlab.github.io/), Tsinghua University, where I was fortunate to be advised by [Prof. Qiyuan Tian](https://www.med.tsinghua.edu.cn/info/1143/2126.htm) and explored the frontiers of Medical AI. I also have great memories working at [The Multi-Scale Robotics Lab, ETH Zurich](https://msrl.ethz.ch/), advised by [Prof. Bradley Nelson](https://msrl.ethz.ch/the-lab/team/Brad_Nelson.html). 

I've also gained industry experience as a machine learning engineer intern. Most recently in Summer 2026, I worked at [SigmaStar Technology](https://www.sigmastarsemi.com/), building compact VLMs for on-device deployment. Before that, I joined [Subtle Medical Inc.](https://subtlemedical.com/) in Summer 2025, developing human-in-the-loop deep learning algorithms for medical imaging.

My current research interests include **Multimodal Learning, Agentic Systems, and Trustworthy AI for Medicine**. I am always passionate about interdisciplinary collaboration, so please feel free to reach out!

# 🔥 News
**2026.09.22:** 🌲 A new chapter begins! Started my M.S. journey in Electrical Engineering at **Stanford University**.

**2026.06.27:** 🎓 Honored to be named a **Beijing Outstanding Graduate** (*Top 5%*). Farewell, Tsinghua!

**2026.05.14:** ⛰️ Attended [ISMRM 2026](https://www.ismrm.org/) in Cape Town, South Africa. Incredible city!

**2026.05.08:** 🎉 Our work [FetalAgents](https://github.com/huang-jw22/FetalAgents) was **Early Accepted** (*Top 9%*) by MICCAI 2026 !

**2026.02.04:** 🎉 Four abstracts accepted by [ISMRM 2026](https://www.ismrm.org/26m/), with an Educational Stipend awarded!

**2025.10.27:** 🎉 Received the **Outstanding Poster Award** at the Tsinghua University Initiative Scientific Research Program Symposium.

**2025.10.17:** 🎖 Awarded the **National Scholarship** (*Top 0.2%*) for the second consecutive year!

**2025.09.27:** 🏆 Our team won the **1st Place** in the [MICCAI 2025 autoPET IV Challenge](https://autopet-iv.grand-challenge.org/autopet-iv/) (Task I)! 🎉🎉 Thrilled to receive this award and present our method on the workshop!

<p align="center">
  <img src="../images/autopet_award.jpg" alt="autoPET Award" width="48%">
</p>

**2025.07.22:** 🎉🎉 Our team won [the 1st prize](https://img.erpweb.eu.org/imgs/2025/07/126d96158b08e1d8.jpg) at the 10th National Biomedical Engineering Innovation Design Competition for College Students (Top 5%).

**2025.07.20:** Attended the [Medical Imaging Computing Seminar (MICS) 2025](http://mics2025.com/) in Cixi, Zhejiang. [Photo](https://drive.google.com/file/d/1MvW5ANSwRB1bYXC676vW0CCNSEsbHuGD/view?usp=sharing)

**2025.06.23:** Began my summer internship at [Subtle Medical Inc.](https://subtlemedical.com/).

**2025.02.17:** Delighted to join the [Lab for Brain Imaging Research at Tsinghua, BIRTH](https://birthlab.github.io/).

**2024.09.16:** Honored to join the [Multi-Scale Robotics Lab](https://msrl.ethz.ch/) at ETH Zurich to develop biomedical micro-robots.

**2024.09.11:** Arrived at Zurich! Excited to begin my exchange study journey in 🇨🇭.

# 📝 Publications 
<span style="color:#b02418; font-weight:bold;">*</span> equal contribution | <span style="color:#b02418; font-weight:bold;">&dagger;</span> corresponding author <br> 

<h2 id="CONFERENCE PAPERS" style="color: #2c4a88; padding-top: 60px; margin-top: -60px; margin-bottom: 8px;">CONFERENCE PAPERS</h2>

<ol reversed>
  <li id="MA-Pub2"> 
    <span style="color:#000000; font-weight:bold;">FetalAgents: A Multi-Agent System for Fetal Ultrasound Image and Video Analysis</span> <br> 
    <a href="https://arxiv.org/pdf/2603.09733">[arXiv]</a> <a href="https://github.com/huang-jw22/FetalAgents/tree/main">[Code]</a><br> 
    Xiaotian Hu<b><sup>*</sup></b>, <span style="color:#b02418; font-weight:bold;">Junwei Huang<sup>*</sup></span>, Mingxuan Liu<b><sup>*</sup></b>, Kasidit Anmahapong, Yifei Chen, Yitong Luo, Yiming Huang, Xuguang Bai, Zihan Li, Yi Liao, Haibo Qu, Qiyuan Tian<b><sup>&dagger;</sup></b><br> 
    <i> International Conference on Medical Image Computing and Computer Assisted Intervention <strong>(MICCAI)</strong></i>, 2026. (Early Accept, Top 9%)
  </li>

  <li id="MA-Pub1"> 
    <span style="color:#000000; font-weight:bold;">Multi-Organ Volumetric Growth Trajectories in Fetuses with Hydronephrosis</span> <br> 
    <span style="color:#b02418; font-weight:bold;">Junwei Huang</span>, Kasidit Anmahapong, Haoxiang Li, Mingxuan Liu, Juncheng Zhu, Hongjia Yang, Yijin Li, Yingqi Hao, Fenglin Jia, Yi Liao, Haibo Qu, Qiyuan Tian<sup>&dagger;</sup><br> 
    <i> ISMRM & ISMRT Annual Meeting & Exhibition <strong>(ISMRM)</strong></i>, 2026. (Digital Poster)
  </li>

  <li id="MA-Pub0"> 
    <span style="color:#000000; font-weight:bold;">autoPET IV challenge: Incorporating organ supervision and human guidance for lesion segmentation in PET/CT</span> <br>
    <a href="https://arxiv.org/pdf/2509.02402">[Paper]</a> <a href="https://github.com/huang-jw22/autoPET-4-submission/tree/master">[Code]</a><br> 
    <span style="color:#b02418; font-weight:bold;">Junwei Huang</span>, Yingqi Hao, Yitong Luo, Ziyu Wang, Mingxuan Liu, Yifei Chen, Yuanhan Wang, Lei Xiang, Qiyuan Tian<sup>&dagger;</sup><br> 
    <i> MICCAI autoPET IV challenge <strong>(MICCAI)</strong></i>, 2025. (Task I Winner Solution)
  </li>
</ol>


# 🎖 Honors and Awards
- *2025, 2024* **National Scholarship** (Twice) <br /> &nbsp; &nbsp; &nbsp; *Top scholarship in China. 0.2% nationwide*.
- *2025, 2024, 2023* **Tsinghua University Comprehensive Excellence Scholarship (Top 10%)**
- *2025* **MICCAI autoPET IV Challenge 1st Place Winner (Task I)**
- *2025* **First Prize** at the 10th National Biomedical Engineering Innovation Design Competition for College Students **(Top 5%)**
- *2025* **Outstanding Poster Award** at the Tsinghua University Initiative Scientific Research Program Symposium
- *2024* **First Prize** at the 7th National College Student Art Exhibition (Instrumental Music Category)
- *2024* **Outstanding Scholarship**, Fujian Province Youth Talent Development Program
- *2024* **College Contribution Scholarship**, Weixian College, Tsinghua University

# 📖 Education
- *2026.09 - 2028.04 (Expected)*, Master's student: **Department of Electrical Engineering**, Stanford University, USA.
- *2024.09 - 2025.02*, Exchange student: **Department of Information Technology and Electrical Engineering**, ETH Zurich, Switzerland. 
- *2022.09 – 2026.06*, Undergraduate student: **Weixian College** and **School of Biomedical Engineering**, Tsinghua University, China.

# 🎬 Hobbies
When I’m not immersed in coursework and research, I love diving into arts, literature, and sports. 

- Classical Music: I have a keen interest in classical music, both as a listener and a player. I have been playing the piano and saxophone since 6. At 12 I joined our junior high school orchestra, and have been playing Bassoon ever since. Entering University, I joined the **Tsinghua University Symphonic Orchestra**, where I’ve had the pleasure of performing in several concerts and competitions.
  
<p align="center">
  <img src="../images/orchestra.PNG" alt="Orchestra" width="50%">
</p>

- Sports: I have a diverse passion for sports, including but not limited to soccer, tennis, badminton, and snooker. I am part of the College Soccer & Badminton team, as well as a member of the University Soccer Referee Association. Beyond competitive sports, I also enjoy hiking — being in the mountains always makes me feel closer to the world and to my soul.

<div style="display:flex; gap:12px; justify-content:center; align-items:center; flex-wrap:wrap;">
  <img src="../images/soccer.png" alt="soccer" style="width:40%; height:auto;" loading="lazy">
  <img src="../images/badminton.png" alt="badminton" style="width:40%; height:auto;" loading="lazy">
</div>

- Films & Literature: In one of my favorite film *[Yi Yi](https://letterboxd.com/film/yi-yi/)*, there is a line: *"We live three times as long since man invented movies."* That's exactly why I love them: Through the screens and book pages, we get to experience lives that we would never be able to experience in reality. 

<p align="center">
  <img src="../images/Film.jpg" alt="Film" width="50%">
</p>


# 🔗 LINKS
BIRTH Lab: [The lab for Brain Imaging Research at Tsinghua](https://birthlab.github.io/)<br>Mingxuan Liu: [School of Biomedical Engineering, Tsinghua University](https://arktis2022.github.io/)<br>Haoxiang Li: [School of Biomedical Engineering, Tsinghua University](https://lihaoxiang-20.github.io/)<br>Yingqi Hao: [School of Biomedical Engineering, Tsinghua University](https://yingqihao2022.github.io/)
