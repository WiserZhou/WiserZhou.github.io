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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!--Header Name-->
![Emoji](https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430){: width="30" align="left" }*Undergraduate student in software engineering*

<!--Start Intro-->
My name is Yufan Zhou (Chinese: 周雨凡). I am an undergraduate student at Harbin Institute of Technology, advised by Prof. [Weigang Zhang](https://homepage.hit.edu.cn/zhangweigang) and [Shuhui Wang](https://vipl.ict.ac.cn/people/shwang/). I have also done a research internship and visited students in Professor [Huan Wang](https://huanwang.tech/) in WU, [Yan-Pei Cao](https://yanpei.me/) in VAST, [Xihui Liu](https://xh-liu.github.io/) in MMLab@HKU and [Xingang Pan](https://xingangpan.github.io/) in MMLab@NTU before.

<p>I am broadly interested in various software development technologies and diffusion theory, particularly in T2V (Text-to-Video), T2I (Text-to-Image), personalization generation, and projects involving procedural planning (e.g., Video Prediction).</p>

<p>Initially, my interest was in various diffusion works, aspiring to use generative skills to create anything. Currently, I focus more on image generation, such as personalization and data or dataset augmentation. My goal is to generate images in various styles and reduce the cost of data acquisition. I'm eager to connect with anyone who shares this vision for AI or appreciates the same research approach.</p>

<p>Recently, my interest has expanded to 3D generation and world-building, which I believe is the ultimate goal of diffusion and generative subjects. By enabling arbitrary editing styles of images, everyone can access resources and 3D worlds. Additionally, incorporating physical conditions into diffusion can make the generated results appear more realistic and logical. I am optimistic that this can be achieved soon, given that image generation began only a few years ago.</p>

<p>In addressing these issues, my focus is on what I do and aim to achieve. I believe that with logic, mathematics, and the creation of various architectures, one can accomplish anything.</p>

You can find my CV here: [Yufan Zhou's Curriculum Vitae](../assets/English_CV.pdf).

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=WiserZhou&label=Profile%20views&color=yellow&style=for-the-badge&logo=star&base=0&abbreviated=true" alt="Profile views" />
</p>

# 🔥 News
- **2025.08**: &nbsp;🎉 The paper *"OmniPart: Part-Aware 3D Generation with Semantic Decoupling and Structural Cohesion"* has been accepted at SIGGRAPH ASIA 2025.
- **2025.07**：&nbsp;🤗 Started a Research Internship at MMLab@NTU, focusing on 3D generation & Reconstruction.
<!-- - **2025.02**: &nbsp;🤗 The paper *"FreeBlend: Advancing Concept Blending with Staged Feedback-Driven Interpolation Diffusion"* has been published as a preprint on ArXiv. -->
- **2025.03**: &nbsp;🤗 Started a Research Internship at VAST & HKU, focusing on 3D part generation.
- **2025.01**: &nbsp;🎉 The paper *"Masked Temporal Interpolation Diffusion for Procedure Planning in Instructional Videos"* has been accepted as a poster at ICLR 2025.
- **2024.10**: &nbsp;🎉 Awarded the National Scholarship by the Ministry of Education of China.
- **2024.07**: &nbsp;🎉 Received the National Third Prize in the Computer Design Contest with the Virtual Digital Agent project.
- **2024.06**: &nbsp;🤗 Started a Research Internship at ENCODE Lab, Westlake University, focusing on Image Generation with Diffusion Models.
- **2024.05**: &nbsp;🎉 Named a Finalist in the Mathematical Contest in Modeling with MM-LSTM method.
- **2024.04**: &nbsp;🎉 Awarded the Huawei Smart Base Scholarship.
- **2023.12**: &nbsp;🎉 Won the National Third Prize in the Physics Experiment Competition with Unity 3D project.

# 📝 Publications 

<!--  -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">SIGGRAPH ASIA 2025</div>
      <img src='images/OmniPart.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

## [OmniPart: Part-Aware 3D Generation with Semantic Decoupling and Structural Cohesion](https://arxiv.org/pdf/2507.06165)

Yunhan Yang\*, **Yufan Zhou\***, Yuan-Chen Guo, Zi-Xin Zou, Yukun Huang, Ying-Tian Liu, Hao Xu, Ding Liang, Yan-Pei Cao, Xihui Liu
<!-- **Yufan Zhou\***, Haoyu Shen\*, Huan Wang -->

- Proposes a part-aware 3D generation framework using structure planning and spatial flow modeling.
- Achieves top performance with precise control over part granularity and localization.
- Welcome to our **[Webpage](https://omnipart.github.io/)**

</div>
</div>

<!--  -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Preprint 2025</div>
      <img src='images/FreeBlend_pipeline2.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

## [FreeBlend: Advancing Concept Blending with Staged Feedback-Driven Interpolation Diffusion](https://www.arxiv.org/pdf/2502.05606)

**Yufan Zhou\***, Haoyu Shen\*, Huan Wang

- Proposes a novel feedback-driven latent interpolation approach for concept blending in three-stage image generation with unCLIP-based image conditions.
- Demonstrates superior performance on both visual results and multiple benchmarks through extensive experiments.
- Welcome to our **[Webpage](https://petershen-csworld.github.io/FreeBlend/)**

</div>
</div>

<!--  -->

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025 Poster</div>
      <img src='images/MTID_pipeline.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

## [Masked Temporal Interpolation Diffusion for Procedure Planning in Instructional Videos](https://openreview.net/forum?id=HnpDHiItd2)

<!-- **Yufan Zhou**, Zhaobo Qi, Lingshuai Lin, et al. -->
**Yufan Zhou**, Zhaobo Qi, Lingshuai Lin, Junqi Jing, Tingting Chai, Beichen Zhang, Shuhui Wang, Weigang Zhang

- Focuses on goal-directed planning using visual observations and proposes a latent space temporal interpolation module.
- Implements masking strategies and task-adaptive proximity loss achieving SOTA performance.  

</div>
</div>
<!--  -->

# 💼 Internships

- **May 2024 - Nov 2024**: Research Intern, ENCODE LAB, WestLake University (Advised by Prof. [Huan Wang](https://huanwang.tech/))
<!-- - **Sep 2024 - Nov 2024**: Research Intern, EPIC LAB, Shanghai Jiao Tong University (Advised by Prof. [Linfeng Zhang](http://www.zhanglinfeng.tech/)) -->
- **Mar 2025 - Jun 2025**: Research Intern, MMLab@HKU & VAST (Advised by Prof. [Xihui Liu](https://xh-liu.github.io/) and [Yan-Pei Cao](https://yanpei.me/))
- **Jul 2025 - Oct 2025**: Research Intern, MMLab@NTU (Advised by Prof. [Xingang Pan](https://xingangpan.github.io/))

# 🎁 Academic Projects

<p>I have conducted several surveys in my field to provide detailed assistance to those interested in my work.</p>

- **[A Survey of Synthetic Image Methods with Diffusion](https://github.com/WiserZhou/A-Survey-of-Synthetic-Images-Methods-with-Diffusion)**
- **[A Survey of Procedure Planning in Instructional Videos](https://github.com/WiserZhou/A-Survey-of-Procedure-Planning-in-Instructional-Videos)**

# 💻 Software Projects

<p>I enjoy creating software for fun and exploring new technologies, such as Vue, Spring Boot, Android, and other tech stacks. I have completed several projects using these technologies, which have enhanced my technical skills, project management abilities, and experience in requirement analysis. Additionally, I hope my library can assist others in learning and applying code for their needs and research.</p>

- **[MM-LSTM](https://github.com/WiserZhou/MM-LSTM)**
- **[LLM agent + RAG + Virtual Digital Person](https://github.com/yxf203/QA-question)**
- **[Simple Qt Browser Framework](https://github.com/WiserZhou/Simple-Paging-Browser-Framework)**
- **[Android Accessibility Service](https://github.com/WiserZhou/AccessibilityService)**
- **[Wholesale And Retail System (Vue + Springboot)](https://github.com/WiserZhou/WholesaleAndRetailSystem)**
- **[Medicine WeChat Mini Program](https://github.com/WiserZhou/weixinMedicine)**
- **[Teacher Student Mutual Selection System](https://github.com/WiserZhou/VolunteerSelection)**

# 📗 Course Projects

<p>I enjoy acquiring knowledge in computer science and related fields. During my courses, I have built several projects to enhance my learning experience. By writing code and documenting information in markdown, I aim to teach myself and future learners more effectively.</p>

- **[Java Course](https://github.com/WiserZhou/JavaLearn)**
- **[Data Structure Course](https://github.com/WiserZhou/DataStructure)**
- **[Algorithm Course](https://github.com/WiserZhou/AlgorithmProblem.git)**
- **[Software Construction Course](https://github.com/WiserZhou/SoftwareConstruction)**
- **[Python Course](https://github.com/WiserZhou/pythonCourse)**
- **[Web Course](https://github.com/WiserZhou/WebWork)**
- **[Database System Course](https://github.com/WiserZhou/DatabaseSystem)**
- **[Network Course](https://github.com/WiserZhou/network)**
- **[Operation System Course](https://github.com/WiserZhou/OS_Code)**

<!-- # 💼 Academic Service

P.S. Just some volunteering to show that I am happy to contribute to society (QwQ).
Proof of my participation in these volunteer services can be verified on the respective conference websites.

- Journal Reviewer: T-PAMI, TMLR, Frontier of CS
- Conference Reviewer: ICML/ICLR/NeurIPS, AISTATS, CVPR/ECCV/ICCV, ACMMM/ICPR/ICME
- Workshop Reviewer: NeurIPS2023-R0-FoMo, ICLR2024-BGPT, ICLR2024-SeT -->

<!-- ## 🔗 Links

- Advisor: [Zhaobo Qi](https://scholar.google.com.hk/citations?user=QZ8URKAAAAAJ&hl=zh-CN), [Huan Wang](https://huanwang.tech/), [Weigang Zhang](https://homepage.hit.edu.cn/zhangweigang), [Shuhui Wang](https://vipl.ict.ac.cn/people/shwang/) -->

# 🛠 Tech Stack & Latest Blogs

## Current Learning

- Deepening knowledge in Machine Learning and AI.
- Exploring advanced web patterns and software management techniques.
- Improving academic skills in Diffusion and AIGC.

## Latest Blog Posts

- [Python Data Visualization Library Matplotlib Learning (2D)](https://blog.csdn.net/imm_ortal_/article/details/131498785)
- [Development of Qt Simple Paginated Browser Framework](https://blog.csdn.net/imm_ortal_/article/details/131484470)


![Language](https://img.shields.io/badge/language-C++-lightblue)
![Language](https://img.shields.io/badge/language-C-brightgreen)
![Language](https://img.shields.io/badge/language-Java-yellow)
![Language](https://img.shields.io/badge/language-Python-brightgreen)
![Language](https://img.shields.io/badge/language-HTML-brightgreen)
![Language](https://img.shields.io/badge/language-CSS-brightgreen)
![Language](https://img.shields.io/badge/language-JavaScript-brightgreen)
![Language](https://img.shields.io/badge/language-TypeScript-brightgreen)
![Language](https://img.shields.io/badge/language-LaTeX-brightgreen)
![Language](https://img.shields.io/badge/language-Markdown-brightgreen)
