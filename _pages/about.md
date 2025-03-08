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

My research is centered on advancing robotic autonomy through intelligent control and robot visual perception(especially for Legged Robots), addressing critical challenges in complex environment navigation and swarm coordination. Modern robotics systems often struggle with dynamic obstacle traversal and real-time adaptability, particularly in unstructured terrains. I am deeply committed to developing robust algorithmic frameworks that **integrate model predictive control (MPC), sensor fusion, and adaptive path planning** to enable efficient and resilient robotic behaviors. My work directly aligns with this vision, focusing on:

- **Multi-Agent Formation Control**: Designing the experiments of **CLF-CBF-based algorithms** for distributed quadruped robot swarms, optimizing obstacle traversal through hierarchical conflict resolution and dynamic path planning.

- **Sensor-Driven Autonomy**: Enhancing environmental perception via **LiDAR and depth camera fusion**, leveraging LCCP segmentation and RANSAC plane fitting to improve localization accuracy in unstructured scenarios.

- **Real-Time Optimization**: Implementing **MPC controllers for 12-DOF quadruped robots**, balancing computational efficiency and motion precision through C++-based matrix operations and ROS integration.

These innovations have been validated in national robotics competitions and contribute to the development of a more capable and adaptable robotic system capable of navigating complex environments.  Pursuing further research in these areas will bridge theoretical advancements with real-world deployability, fostering intelligent robotics that adapt to evolving challenges.

You can find my CV here: [Tinghong Ye's Curriculum Vitae](../assets/叶庭宏_蓝_V3.pdf).

# 🔥 News
- *2025.03*: &nbsp;🎉 A paper that I have been deeply involved in has been submitted to 2025 IROS Conference. The research direction of the paper focuses on distributed formation and obstacle traversal for quadruped robot swarms. 
- *2024.05*: &nbsp;🤗 Started Research Intern at Intelligence Manufacturing and Data Science Laboratory, focusing on Robotics Control Algorithm. 

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
- *2024.05 - 2025.03*, Research Intern, Intelligence Manufacturing and Data Science Laboratory, Huazhong University of Science and Technology (Advised by Prof. [Lijun Zhu](http://faculty.hust.edu.cn/ZHULIJUN/en/more/2288717/jsjjgd/index.htm))
