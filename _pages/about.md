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

I’m a second-year master's student in Automation at *[Beijing Institute of Technology (BIT)](https://english.bit.edu.cn/)*. As a member of *State Key Laboratory of Autonomous Intelligent Unmanned Systems*, I'm advised by Prof. [Chengpu Yu](https://ac.bit.edu.cn/szdw/dsmd/sssds/mssbyznxt/69e8a71ad78346fb87e6765e0f2549ab.htm). I received my B.Eng. degree in Measurement & Control Technology from *[China University of Mining & Technology (CUMT), Beijing](https://english.cumtb.edu.cn/)* in 2021.

The goal of my research is to enhance the autonomy of robots. Currently, I'm focusing on autonomous exploration systems and its supporting technologies, such as SLAM, motion planning, and multi-robot collaboration.

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 
## Articles

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CASE 2023</div>
      <a href="https://youtu.be/aPXxOKf1o10" title="TDLE"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1685324236/video_to_markdown/images/youtube--aPXxOKf1o10-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="TDLE: 2D Lidar Exploration with Hierarchical Planning Using Regional Division" width="100%"/></a>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **[TDLE: 2D Lidar Exploration with Hierarchical Planning Using Regional Division](https://arxiv.org/abs/2307.02852)**

  IEEE International Conference on Automation Science and Engineering (CASE), Auckland, New Zealand, 2023 

  **Xuyang Zhao**, Chengpu Yu, Erpei Xu and Yixuan Liu

  - Proposed an exploration system that uses global dynamic regional division and localized metric evaluation to achieve efficient autonomous mapping with low computational requirements. The proposed method can run at high frequencies (>100Hz) on low-power edge platforms like Jetson Nano, while offering up to 57.57% efficiency improvement compared to former methods.

  </div>
</div>

## Patents
- Chengpu Yu, **Xuyang Zhao**, Dajian Zhou, "An Indoor Mapping Method And Device With Autonomous Exploration", Chinese Patent 20211114092.1, 2021. 
- Chengpu Yu, Dajian Zhou, **Xuyang Zhao**, "An 3D Inversion Positioning Method Based on Ultra-wideband (UWB).", Chinese Patent 202110893866.X, 2021.

# 🔬 Projects

- *2021.10 - now*, **Indoor Navigation and Detection Based on Air-Ground Platform Collaboration. (Core Member)** 
  
  [National Key R&D Program] 

  In disaster relief scenarios, there is a safety risk for rescuers when they enter damaged buildings, such as those affected by an earthquake. To tackle this issue, we have developed a LiDAR exploration and mapping system. The proposed system conduct indoor information surveys and return autonomously after completion, helping to inspect the internal environment and find trapped people.
  
  The whole process requires no remote control or pre-specified routes, as the decision is made entirely by the on-board processing unit.

<table><tr>
<td style="width:50%"> <a href="https://youtu.be/BFo1Ke8co4k" title="Exploration with Solid-state Lidar (3 UAVs)"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688958193/video_to_markdown/images/youtube--BFo1Ke8co4k-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Exploration(3 UAVs)"></a></td>
<td> <a href="https://youtu.be/hQJ7u7scb8Y" title="Exploration with Solid-state Lidar (2 UAVs)"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688958424/video_to_markdown/images/youtube--hQJ7u7scb8Y-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Exploration(2 UAVs)"></a></td>
</tr></table>


- *2020.05 - 2020.09*, **ROS Smart Car Racing. (Team Leader)** 

  [China's 15th National Collegiate Smart Car Race] To achieve higher speed in the racing, besides device adjustment and tuning, we carried out the following tasks: (1) Distortion correction for LiDAR mapping process; (2) Introduction of strong constraints for obstacle avoidance in local planners; (3) Construction of LiDAR-IMU Odometry (LIO). These efforts led to a successful advancement in the simulation race of the North China division and then a national second prize in the final competition.

<table><tr>
<td style="width:47.5%"> <a href="https://youtu.be/GT1CXNN92-o" title="Racecar"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688913924/video_to_markdown/images/youtube--GT1CXNN92-o-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Smart car race demo (simulation competition part)"></a></td>
<td><img src="images/comp_scene.png" alt="competition scene"></td>
</tr></table>

# 📖 Educations
- *Sept. 2021 - Jul. 2024 (Present)*, Master's student of Control Engineering, Beijing Institute of Technology. **(Grade: 85.26/100.0)**
- *Sept. 2017 - Jul. 2021*, Bachelor of Measurement & Control Technology, China University of Mining & Technology, Beijing. **(GPA: 3.68/4.0)**

# 💻 Internships
- *2023.04 - 2023.05*, [PhiGent Robotics](https://www.phigent.ai/), Autonomous Driving R&D Intern.

# 🏅 Honors and Awards
- *2022.09* First Class Scholarship of Beijing Institute of Technology. 
- *2021.06* Outstanding Graduates of China University of Mining and Technology, Beijing. (Top 5%)
- *2021.06* First Prize of Excellent Bachelor Thesis of China University of Mining & Technology, Beijing. (Top 1%)
- *2020.09* National Second Prize of Collegiate Smart Car Competition.

# 📚 Skills
- **Robotics Dev.:** ROS, PX4, Gazebo, PCL, Eigen, Ceres, etc. 
- **Programming:** C/C++, Python, LaTeX
- **Dev. Tools:** Git, Linux & Shell, Docker, etc.
- **Language:** English (CET-6: 551, TOEFL: 101), Chinese (Native)