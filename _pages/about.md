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

分别于2012年、2018年于**大连理工大学获学士和博士学位（保送、硕博连读）**，2018年至2020年于**香港理工大学展开博士后研究**，2020年加入**大连理工大学软件学院任副教授（特评会）**。**已发表及录用中国计算机学会推荐的CCF A、B类等高水平学术论文40余篇，包括TKDE（CCF A）、KDD（CCF A）、AAAI（CCF A）、IJCAI（CCF A）、SIGIR（CCF A）、WWW（CCF A）、CVPR（CCF A）、ACL（CCF A）等人工智能、机器学习和数据挖掘领域一系列国际顶级期刊和会议**。**主持国家自然科学基金项目1项，JW创新特区项目1项，大连理工大学星海骨干项目1项，引进人才科研专题项目1项**，参与其他**国家级纵向项目或GF项目5项**（含科技部“脑科学与类脑研究”重大项目（青年科学家）1项）。    
  
主要从事**人工智能、深度学习、数据挖掘**等相关领域的算法研究工作，致力于把提出的算法应用于**自然语言处理、计算机视觉、智能决策、机器人**等各个领域。重点聚焦人工智能研究中的**数据瓶颈、安全瓶颈、可解释性瓶颈**，针对下述方向展开深入探索：**小/零样本学习, 预训练/自监督学习, 对抗攻击与防御, 对抗攻击与防御, 图神经网络**。    

**热烈欢迎有志于投身人工智能、机器学习、数据挖掘前沿领域科学研究的优秀研究生、本科生加盟，有意者请发送简历至hanliu@dlut.edu.cn，期待你的加入！**


# 🔥 News
- *2023.04*: &nbsp;🎉 one paper is accepted by **IJCAI 2023**. 
- *2022.11*: &nbsp;🎉 two paper is accepted by **AAAI 2023**. 
- *2022.01*: &nbsp;🎉 one paper is accepted by **KDD 2022**. 
- *2022.01*: &nbsp;🎉 one paper is accepted by **SIGIR 2022**. 
- *2021.01*: &nbsp;🎉 one paper is accepted by **EMNLP 2021**. 
- *2021.01*: &nbsp;🎉 one paper is accepted by **KDD 2021**. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SSPAttack: A Simple and Sweet Paradigm for Black-Box Hard-Label Textual Adversarial Attack](https://hanliu.github.io)

**Han Liu**, Zhi Xu, Xiaotong Zhang, Xiaoming Xu, Feng Zhang, Fenglong Ma, Hongyang Chen, Hong Yu, Xianchao Zhang

[**PDF**](https://hanliu.github.io) \| [**Code**](https://github.com/hanliu)  
  
A Simple and Sweet Paradigm for Black-Box Hard-Label Textual Adversarial Attack
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Boosting Few-Shot Text Classification via Distribution Estimation](https://hanliu.github.io)

**Han Liu**, Feng Zhang, Xiaotong Zhang, Siyang Zhao, Fenglong Ma, Xiao-Ming Wu, Hongyang Chen, Hong Yu, Xianchao Zhang

[**PDF**](https://hanliu.github.io) \| [**Code**](https://github.com/hanliu)  
  
Distribution estimation has been demonstrated as one of the most effective approaches in dealing with few-shot image classification, as the low-level patterns and underlying representations can be easily transferred across different tasks in computer vision domain. However, directly applying this approach to few-shot text classification is challenging, since leveraging the statistics of known classes with sufficient samples to calibrate the distributions of novel classes may cause negative effects due to serious category difference in text domain. To alleviate this issue, we propose two simple yet effective strategies to estimate the distributions of the novel classes by utilizing unlabeled query samples, thus avoiding the potential negative transfer issue. Specifically, we first assume a class or sample follows the Gaussian distribution, and use the original support set and the nearest few query samples to estimate the corresponding mean and covariance. Then, we augment the labeled samples by sampling from the estimated distribution, which can provide sufficient supervision for training the classification model. Extensive experiments on eight few-shot text classification datasets show that the proposed method outperforms state-of-the-art baselines significantly.
</div>
</div>

## Few/Zero-shot Learning
- **AAAI 2023** [Boosting Few-Shot Text Classification via Distribution Estimation](https://hanliu.github.io), **Han Liu**, Feng Zhang, Xiaotong Zhang, Siyang Zhao, Fenglong Ma, Xiao-Ming Wu, Hongyang Chen, Hong Yu, Xianchao Zhang. [**PDF**](https://hanliu.github.io) \| [**Code**](https://github.com/hanliu)   

## Adversarial Attack and Defense
- **AAAI 2023** [SSPAttack: A Simple and Sweet Paradigm for Black-Box Hard-Label Textual Adversarial Attack](https://hanliu.github.io), **Han Liu**, Zhi Xu, Xiaotong Zhang, Xiaoming Xu, Feng Zhang, Fenglong Ma, Hongyang Chen, Hong Yu, Xianchao Zhang. [**PDF**](https://hanliu.github.io) \| [**Code**](https://github.com/hanliu)

# 🎖 Honors and Awards
- *2022.11* 华为昇腾AI创新大赛（初创创新赛道）— 赛区金奖（唯一）—全国铜奖
- *2022.11* 华为昇腾AI创新大赛（初创创新赛道）— 赛区金奖（唯一）—全国铜奖  
- *2021* 大连理工大学星海人才培育计划
- *2020* 大连市新引进高层次人才
- *2019* 香港创新及科技基金博士专才库计划

# 📖 Educations
- *2012.09 - 2028.07*, Ph.D., School of Software, Dalian University of Technology.
- *2008.09 - 2012.06*, Undergraduate, School of Software, Dalian University of Technology.  

# 💬 Professional Services
- *Procedural Commissioner*  **KDD、AAAI、IJCAI、ACL、EMNLP、CVPR、ICCV、ECCV**
- *Reviewer*  **TPAMI、AI、TNNLS、TOIT、TITS、PR、INS、KBS**
- *Guest Editor*  **WCMC、IJDSN、Applied Science**
- *Committees/Chairmen*  **CAAI智能服务专业委员会委员、CAAI青年工作委员会委员、中文信息学会情感计算专委会委员、中国图学学会可视化与认知计算专委会委员、MLNLP会议宣传主席**
