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

Hello! I am Zhongmou He (何忠谋). You can call me Morris. Welcome to my personal website!😊

I am currently a junior student in Data Science at the [University of Michigan](https://umich.edu/), fortunately advised by Prof. [Danai Koutra](https://web.eecs.umich.edu/~dkoutra/). Before transferring to UM, I spent two years at [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/) studying Electrical and Computer Engineering, where I was advised by Prof. [Xinbing Wang](https://www.cs.sjtu.edu.cn/%7Ewang-xb/).

I am interested in natural language processing (NLP) and machine learning for graphs. My research focuses on utilizing LLMs for various downstream tasks. Please feel free to check out my CV!

[CV (short ver.)](https://drive.google.com/file/d/1e0x5442Lncpj734IZqLdVrZs9EQvtrm0/view?usp=drive_link) \| [CV (full ver.)](https://drive.google.com/file/d/1B308eWmx4EjlIEjYnw2lIM4ruXB_3WaS/view?usp=drive_link)



# 🔥 News
- **[Dec. 2023]**: &nbsp;🎉🎉 Our paper [GeoGalactica: A Scientific Large Language Model in Geoscience](https://arxiv.org/abs/2401.00434) is accepted by WSDM 2024.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WSDM 2024</div><img src='images/K2_img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[K2: A Foundation Language Model for Geoscience Knowledge Understanding and Utilization](https://arxiv.org/abs/2306.05064)

Cheng Deng, Tianhang Zhang, **Zhongmou He**, Yi Xu, Qiyuan Chen, Yuanyuan Shi, Luoyi Fu, Weinan Zhang, Xinbing Wang, Chenghu Zhou, Zhouhan Lin, Junxian He


[**Citation: 15**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=fzM8jcwAAAAJ&citation_for_view=fzM8jcwAAAAJ:u-x6o8ySG0sC) \| [![](https://img.shields.io/github/stars/davendw49/k2?style=social&label=Code+Stars)](https://github.com/davendw49/k2)
</div>
</div>

- ![](https://img.shields.io/badge/Tech%20Report-8A2BE2) [GeoGalactica: A Scientific Large Language Model in Geoscience](https://arxiv.org/abs/2401.00434), Zhouhan Lin, Cheng Deng, Le Zhou, Tianhang Zhang, Yi Xu, Yutong Xu, **Zhongmou He**, Yuanyuan Shi, Beiya Dai, Yunchong Song, Boyi Zeng, Qiyuan Chen, Tao Shi, Tianyu Huang, Yiwei Xu, Shu Wang, Luoyi Fu, Weinan Zhang, Junxian He, Chao Ma, Yunqiang Zhu, Xinbing Wang, Chenghu Zhou

# 📝 Research Experences
**Leveraging LLMs for Link Prediction on Text-Attributed Graphs**

- **Advisor:** Prof. Danai Koutra
- Oct. 2023 - present;  University of Michigan
- Proposed a method that enables LLMs to efficiently understand the semantic, neighborhood, and pairwise structural information of nodes through multimodal instruction tuning. Designed an algorithm that leverages LLMs to rapidly filter out a large number of obvious negative target candidates, followed by quantitative evaluation of the remaining target candidates, which boosts the inference speed with minimal accuracy loss.
- Preliminary experiments indicated that the proposed model significantly outperformed the baselines across multiple datasets and demonstrated commendable cross-category and cross-task generalization capabilities. Moreover, the training and testing methods are both highly scalable.

**Development of the First LLM in Geoscience by Large-Scale Training**

- **Advisor:** Prof. Xinbing Wang
- Mar. 2022 - Sep. 2023; Shanghai Jiao Tong University
- Participated in the large-scale further training of LLaMA-7B, with data totaling 5.5B tokens. Collected 22M records from 6 data sources through techniques including PDF parsing and web crawling, and then restructured them into SFT data for 8 tasks, e.g., NER and text summarization. Performed efficient instruction tuning on the pretrained model using LoRA.
- Designed the first benchmark in geoscience. Led the evaluation of the model, exploring the impact of different evaluation methods, such as cloze prompts with various normalizations, on the model’s inference efficiency and accuracy.


# 📖 Educations
**University of Michigan, Ann Arbor (UM)** 

- **Major:** Data Science (CSE) (dual degree); **Minor: Math**
- **GPA:** 4.0/4.0
- Sept. 2023 - May. 2025 (expected); Ann Arbor, MI
- **Selected coursework:** Natural Language Processing (grad), Advanced AI (PhD-level), Machine Learning, Computer Vision, Stochastic Processes (grad), Computer Organization, Database Management Systems, Numerical Analysis


**Shanghai Jiao Tong University (SJTU)** 

- **Major:** Electrical and Computer Engineering (dual degree)
- **GPA:** 3.81, **Rank:** top 5%
- Sept. 2021 - Aug. 2025 (expected); Shanghai, China



# 🎖 Honors and Awards
- **[Jan. 2024] Dean's List of University of Michigan, Ann Arbor**
- **[Jan. 2023] 🥇Gold Award of The University Physics Competition** <br> four hundred teams take part in the competition every year. The most outstanding **approximately 2%** of the teams will be ranked as gold medal winners.
- **[Dec. 2022] 💯Excellent Freshman Scholarship of JI, SJTU (recertification)** <br> Full scholarship of JI, SJTU (10,000 USD/year) for outstanding academic performance. Only **3 out of 250** students can be granted with this scholarship.
- **[Nov. 2022] Undergraduate Excellent Scholarship of SJTU**
- **[Apr. 2022] 🔍Chuntsung Scholarship** <br> Founded by Tsung-dao Lee, winner of a Nobel Prize in Physics, for outstanding scientific research of undergraduate students.
- **[Dec. 2021] 💯Excellent Freshman Scholarship of JI, SJTU**
- **[Dec. 2021] Puyuan Future Talent Scholarship**
- **[Dec. 2020] 🥈National Olympiad in Informatics in Provinces (NOIP) Second Place**




# 💬 Activities
- **[Apr. 2023 - Aug. 2023] Student Advisor @ Advising Center of SJTU** <br> Assist students in course selection, learning, and career planning. Regularly organize workshops to share relevant experiences.
- **[Aug. 2022] Team Leader @ Zhufei Project** <br> Zhufei Project aims helping freshmen with financial difficulties by organizing senior students to visit them at home, explaining the financial aid policy of the college, and describing the campus life.
- **[Dec. 2021] Participant @ Puyuan Future Talent Selection Camp**




# 💻 Internships
