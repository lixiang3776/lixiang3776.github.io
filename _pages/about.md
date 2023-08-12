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

Welcome to my homepage! I am a master’s student at National University of Singapore (NUS). Currently, I am working at NLP group of [Shanghai AI Lab](https://www.shlab.org.cn/) as a research intern under the supervision of [Dr. Zhiyong Wu](https://lividwo.github.io/zywu.github.io/), focusing on topics of LLMs. Prior to this, I was advised by [Dr. Xiaoli Li](https://www.a-star.edu.sg/i2r/about-i2r/i2r-management/li-xiaoli) at Institute for Infocomm Research ([I<sup>2</sup>R](https://www.a-star.edu.sg/i2r)), A*STAR, Singapore for NLP research. Before that, I completed my B.Eng in the School of Data Science and Engineering ([DaSE](http://dase.ecnu.edu.cn/)) with distinction at East China Normal University, where I felt very privileged to be instructed by [Prof. Weining Qian](http://dase.ecnu.edu.cn/dase-module-gateway/dase/teacher/single_teacher.html?teacherId=27), [Prof. Xuesong Lu](http://dase.ecnu.edu.cn/dase-module-gateway/dase/teacher/single_teacher.html?teacherId=40) and [Prof. Xiang Li](https://lixiang3776.github.io/) for research/engineering projects.
My research interests cover neural code intelligence, efficient methods for NLP, representation learning and broad deep learning topics in general.

<!-- Download my [Resumé](./files/Qiushi_Academic_CV_June_2023.pdf)📄 in PDF. -->
 <!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->
<div  align="right">
<img src='./images/qiushi-seal.jpg' style='width: 2.75em;'>  
</div>
# 🔥 News
- *2023.05*: &nbsp;🚀🚀 *HugNLP* Framework is ready for use! Please check our [Paper](https://arxiv.org/abs/2302.14286), [Repo](https://github.com/HugAILab/HugNLP) and [Blogs](https://zhuanlan.zhihu.com/p/628106578)!
- *2023.05*: &nbsp;👏👏 We release [*SelfAware* (ACL 2023 Findings)](https://arxiv.org/abs/2305.18153) for benchmarking LLMs' self-knowledge [Slides](./files/ACL23_LLMSA-Presentation.pdf).
- *2022.12*: &nbsp;🎉🎉 Our team won second prize (100k RMB) in the [International Algorithm Case Competition](https://iacc.pazhoulab-huangpu.com/): PLM Tuning Track. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2022</div><img src='images/cat-probing-emnlp22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CAT-probing: A Metric-based Approach to Interpret How Pre-trained Models for Programming Language Attend Code Structure](https://arxiv.org/abs/2210.04633)

Nuo Chen<sup>&#42;</sup>, **Qiushi Sun**<sup>&#42;</sup>, Renyu Zhu<sup>&#42;</sup>, [Xiang Li](https://lixiang3776.github.io/), Xuesong Lu and Ming Gao

[Slides](./files/EMNLP22_Presentation.pdf) | [Video](https://youtu.be/lghmmlV62JA) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Revealing the relationship between the structural information of source codes and the attention distribution for CodePTMs, and exploring the impact of structural pre-training on task performance.
</div>
</div>

- `Preprint` [Boosting Language Models Reasoning with Chain-of-Knowledge Prompting](https://arxiv.org/abs/2306.06427), Jianing Wang<sup>&#42;</sup>, **Qiushi Sun**<sup>&#42;</sup>, Nuo Chen, Xiang Li and Ming Gao.
- `Preprint` [TransCoder: Towards Unified Transferable Code Representation Learning Inspired by Human Skills](https://arxiv.org/abs/2306.07285), **Qiushi Sun**, Nuo Chen, Jianing Wang, Xiang Li and Ming Gao.
- `Preprint` [Make Prompt-based Black-Box Tuning Colorful: Boosting Model Generalization from Three Orthogonal Perspectives](https://arxiv.org/abs/2305.08088), **Qiushi Sun**, Chengcheng Han, Nuo Chen, Renyu Zhu, Jingyang Gong, Xiang Li and Ming Gao.
- ``ACL 2023`` [Do Large Language Models Know What They Don't Know?](https://arxiv.org/abs/2305.18153), Zhangyue Yin, **Qiushi Sun**, Qipeng Guo, Jiawen Wu, Xipeng Qiu and Xuanjing Huang. [Slides](./files/ACL23_LLMSA-Presentation.pdf) \| [![](https://img.shields.io/github/stars/yinzhangyue/SelfAware?style=social&label=Code+Stars)](https://github.com/yinzhangyue/SelfAware)
- ``ACL 2023`` [When Gradient Descent Meets Derivative-Free Optimization: A Match Made in Black-Box Scenario](https://arxiv.org/abs/2305.10013), Chengcheng Han, Liqing Cui, Renyu Zhu, Jianing Wang, Nuo Chen, **Qiushi Sun**, Xiang Li and Ming Gao.
- ``EMNLP 2022`` [CAT-probing: A Metric-based Approach to Interpret How Pre-trained Models for Programming Language Attend Code Structure](https://arxiv.org/abs/2210.04633), Nuo Chen<sup>&#42;</sup>, **Qiushi Sun**<sup>&#42;</sup>, Renyu Zhu<sup>&#42;</sup>, Xiang Li, Xuesong Lu and Ming Gao. \| [![](https://img.shields.io/github/stars/QiushiSun/CodeAttention?style=social&label=Code+Stars)](https://github.com/QiushiSun/CodeAttention)
- ``CIKM 2023 (Demo)`` [HugNLP: A Unified and Comprehensive Library for Natural Language Processing](https://api.semanticscholar.org/CorpusID:257232389), Jianing Wang, Nuo Chen, **Qiushi Sun**, Wenkang Huang, Chengyu Wang and Ming Gao. \| <img src='./images/hugnlp-logo.png' style='width: 2.95em;'> [![](https://img.shields.io/github/stars/wjn1996/HugNLP?style=social&label=Code+Stars)](https://github.com/HugAILab/HugNLP)

# 🎖 Honors and Awards
- *2022.12* International Algorithm Case Competition: PLM Tuning, Second Prize, Greater Bay Area 
- *2022.07* Shanghai Outstanding Graduates, Shanghai Municipal Education Commission 
- *2022.05* Excellent Bachelor Thesis Award, East China Normal University
- *2021.11* Outstanding Student, East China Normal University
- *2021.10* First Class Scholarship, East China Normal University
- *2021.05* Finalist (Special Class Prize), Mathematical and Interdisciplinary Contest in Modeling

# 📖 Educations
- *2022.08 - 2024.01 (now)*, Master, National University of Singapore  <img src='./images/svgs/NUS-logo.svg' style='width: 2.1em;'>, Singapore.
- *2018.09 - 2022.07*, Undergraduate, School of Data Science and Engineering, East China Normal University  <img src='./images/svgs/ECNU-logo.svg.png' style='width: 1.5em;'>, Shanghai, China.
- *2011.09 - 2018.07*, Middle School, Pudong Foreign Languages School  <img src='./images/svgs/PFLS-logo.png' style='width: 1.5em;'>, SISU, Shanghai, China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.06 - Present*, NLP Research Intern, [NLP Group, Shanghai AI Laboratory](https://github.com/Shark-NLP)  <img src='./images/svgs/shailab-logo.svg' style='width: 1.90em;'>, Shanghai, China.
- *2023.01 - 2023.06*, NLP Research Intern, [Institute for Infocomm Research, A*STAR](https://www.a-star.edu.sg/i2r) <img src='./images/svgs/astar-i2r.svg' style='width: 1.75em;'>, Singapore.
- *2021.10 - 2022.07*, Research Assistant, [School of Data Science and Engineering](http://dase.ecnu.edu.cn/) <img src='./images/svgs/DaSE.svg' style='width: 1.25em;'>, ECNU, Shanghai, China.

# 🧑‍🏫 Teaching
- (Fall 2021) Teaching Assistant @ Deep Learning for Computer Vision, ECNU, Shanghai, China.

# 🔍 Services
- I serve(d) as a conference reviewer for EMNLP2022/2023, ACL2023, CIKM2023, ACL Rolling Review

> "What's past is prologue." -- William Shakespeare (The Tempest)