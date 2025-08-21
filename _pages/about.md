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

Welcome to my personal website! I am Tinghong Ye (Chinese: 叶庭宏), a highly motivated and passionate undergraduate student majoring in Artificial Intelligence at Huazhong University of Science and Technology (HUST). I am currently a junior (Class of 2022) with a strong academic record and a deep interest in **Embodied AI**, particularly in **Robotics control and perception algorithms**.

I am passionate about Embodied AI, focusing on building autonomous systems that can intelligently perceive, navigate, and interact with the physical world. My research integrates state-of-the-art techniques in **multi-modal perception, real-time motion planning, and model predictive control (MPC)**. I apply these principles to challenging platforms like quadruped robots, aiming to enhance their autonomy and adaptability in complex, unstructured environments.

- **3D Vision & Scene Understanding🧠**: Construct the SpatialReason benchmark containing multi-hop QA pairs that require complex **spatial perception**, effectively enhance the interpretability of 3D-VQA reasoning paths.

- **Vision-Language Model Application👀**: Built a tactical analysis system based on Vision-Language Models, employing CoT prompting to reason and predict complex sequential actions.

- **Multi-Agent Formation Control🦵**: Designing the experiments of **CLF-CBF-based algorithms** for distributed quadruped robot swarms, optimizing obstacle traversal through hierarchical conflict resolution and dynamic path planning.

- **Sensor-Driven Autonomy🔍**: Enhancing environmental perception via **LiDAR and depth camera fusion**, leveraging LCCP segmentation and RANSAC plane fitting to improve localization accuracy in unstructured scenarios.

- **Real-Time Optimization⚡**: Implementing **MPC controllers for 12-DOF quadruped robots**, balancing computational efficiency and motion precision through C++-based matrix operations and ROS integration.

These innovations have been validated in national robotics competitions and contribute to the development of a more capable and adaptable robotic system capable of navigating complex environments.  Pursuing further research in these areas will bridge theoretical advancements with real-world deployability, fostering intelligent robotics that adapt to evolving challenges.

# 🔥 News
- *2025.04*: &nbsp;🤗 Started Research Intern at [National Engineering Laboratory for Video Technology – Shenzhen Division](https://web.pkusz.edu.cn/ldm/), PKU, focusing on 3D Understanding based on MLLM and CoT. 
- *2024.05*: &nbsp;🤗 Started Research Intern at [Intelligence Manufacturing and Data Science Laboratory](http://imds.aia.hust.edu.cn/index.htm), Hust, focusing on Robotics Path-Planning and Control Algorithm. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/CLFCBF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Distributed Quadratic Programming (QP)-based Safe Formation Control Scheme for Multiple Quadruped Robots (Under submission)

Danfu Liu\*, Peixuan Song\*, **Tinghong Ye**, Qichen Liang, Jinhui Du, Lijun Zhu and Han Ding

- Introduced a **hierarchical** control strategy: an upper-layer distributed planner for trajectory generation and a lower-layer MPC-based locomotion controller for trajectory tracking.
- Demonstrated effectiveness through **simulations and real-world** experiments with Unitree A1 robots, achieving formation control in complex obstacle environments while meeting safety constraints.
- The project code will be released after acceptance of the paper.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INDIN 2025</div><img src='images/bone.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Bone Age Prediction using a Convolutional Neural Network-based Regression Algorithm employing Attention-Directing and Cluster

Tao Ma\*, **Tinghong Ye**\*, Lixin Deng\*, Yizhu Tang, TakMan LO, Kaip Tse, Yuzhi Huang, Zhihao Li, Renzhi Lu

- Proposed a dual-driven deep learning framework (ACNNet) for bone age assessment, combining cluster analysis and attention-guided CNN regression to hierarchically enhance age-sensitive anatomical features in hand radiographs.
- Introduced an adaptive spatial attention module (ASAM) for ROI detection and a Bayesian-optimized ensemble strategy to fuse predictions from age-specific subsets, improving interpretability and accuracy.
</div>
</div>

# 🎖 Honors and Awards

- *2024.11* Third prize in the Global Campus AI Algorithm Elite Competition **National** Finals
- *2024.10* Science and technology innovation scholarship
- *2024.07* First prize **(Runner-up)** in the **National** College Student Robot Competition
- *2024.07* First prize **(Third place)** in the racing track of **National** College Student Robot Competition
- *2024.07* First prize **(Fourth place)** in the obstacle track of **National** College Student Robot Competition
- *2024.07* Third prize in the cross-country track of **National** College Student Robot Competition
- *2024.05* Third prize of Chinese College Student Computer Design Competition provincial competition
- *2024.05* Second prize in Huazhong Cup college students mathematical modeling contest
- *2024.02* Honorable Mention in Mathematical Contest In Modeling(MCM/ICM)
- *2023.10* School merit student **(top 5%)**
- *2023.09* Second prize in National College students Mathematical Modeling Contest provincial competition
- *2023.08* Second prize in Wasu Cup National college students mathematical Modeling Contest
- *2023.07* First prize in the National College Student Robot Competition
- *2023.05* Outstanding Winner in School robot contest **(rk4)**
- *2023.02* Freshmen study for merit scholarships

# 📖 Educations

- *2022.09 - Present*, Huazhong University of Science and Technology, Bachelor of Artificial Intelligence

# 💻 Internships
- *2025.04 - Present*, Research Intern, National Engineering Laboratory for Video Technology, Peking University (collaborated with Prof. [Ge Li](https://www.ece.pku.edu.cn/info/1046/2658.htm))
- *2024.05 - 2025.03*, Research Intern, Intelligence Manufacturing and Data Science Laboratory, Huazhong University of Science and Technology (Advised by Prof. [Lijun Zhu](http://faculty.hust.edu.cn/ZHULIJUN/en/more/2288717/jsjjgd/index.htm))
