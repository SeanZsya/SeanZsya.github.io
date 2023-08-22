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

<a href="https://seanzsya.github.io/CV_Xuyang_ZHAO.pdf" target="_blank"><b>[ CV ]</b></a>

I'm a second-year master's student in Automation at *[Beijing Institute of Technology (BIT)](https://english.bit.edu.cn/)*, focusing on autonomous exploration systems and its supporting technologies, such as SLAM, motion planning, and multi-robot collaboration. As a member of *State Key Laboratory of Autonomous Intelligent Unmanned Systems*, I'm advised by Prof. [Chengpu Yu](https://ac.bit.edu.cn/szdw/dsmd/sssds/mssbyznxt/69e8a71ad78346fb87e6765e0f2549ab.htm). I received my B.Eng. degree in Measurement & Control Technology from *[China University of Mining & Technology (CUMT), Beijing](https://english.cumtb.edu.cn/)* in 2021.

Currently, I am seeking possible Ph.D. opportunities in the fields of intelligent robotics and autonomous driving. Robots are not just our assistants but can also be companions. I'm excited to continuously enhance their autonomy and intelligence, thus creating a better life.

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

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

  DOTF-SLAM: Real-time Dynamic SLAM Using Object Tracking and Key-point Filtering

  IEEE International Conference on Unmanned Systems (ICUS), Guangzhou, China, 2023 

  Yixuan Liu, **Xuyang Zhao**, Zhengmao Liu, Chengpu Yu

  - Eliminate dynamic feature points while retaining static points of movable objects to improve robustness. The localization accuracy is improved by up to 21.69% compared with ORB-SLAM in the KITTI dataset.
  </div>
</div>


## Patents
- Chengpu Yu, **Xuyang Zhao**, Dajian Zhou, "An Indoor Mapping Method And Device With Autonomous Exploration", Chinese Patent 20211114092.1, 2021. 
- Chengpu Yu, **Xuyang Zhao**, Yixuan Liu, "A Lidar Exploration and Mapping Method Based on Regional Segmentation", Chinese Patent 202321893269.1, 2023.
- Chengpu Yu, Dajian Zhou, **Xuyang Zhao**, "An 3D Inversion Positioning Method Based on Ultra-wideband (UWB).", Chinese Patent 202110893866.X, 2021.

# 🔬 Projects

- *Oct. 2021 - now*, **Indoor Navigation and Detection Based on Air-Ground Platform Collaboration. (Core Member)** 
  
  [National Key R&D Program] 

  In disaster relief scenarios, there is a safety risk for rescuers when they enter damaged buildings, such as those affected by an earthquake. 
  
  To tackle this issue, we have developed a Solid-state LiDAR exploration and mapping system. The proposed system conduct indoor information surveys and return autonomously after completion, helping to inspect the internal environment and find trapped people.
  
  The whole process requires no remote control or pre-specified routes, as the decision is made entirely by the on-board processing unit.

<table><tr>
<td style="width:50%"> <a href="https://youtu.be/BFo1Ke8co4k" title="Exploration with Solid-state Lidar (3 UAVs)"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688958193/video_to_markdown/images/youtube--BFo1Ke8co4k-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Exploration(3 UAVs)"></a></td>
<td> <a href="https://youtu.be/hQJ7u7scb8Y" title="Exploration with Solid-state Lidar (2 UAVs)"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688958424/video_to_markdown/images/youtube--hQJ7u7scb8Y-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Exploration(2 UAVs)"></a></td>
</tr></table>

- *Jul. 2022 - now*, **Collaborative Perception and Environment Modeling of Unmanned Swarms. (Core Member)**
  
  [Industry-Academia Collaborative Innovation Fund]

  Built an unmanned swarm that support any number of intelligent agents for efficient collaborative exploration: (1) built small drones from scratch; (2) established UDP communication to exchange custom compact messages; (3) designed a scalable dynamic task allocation strategy.

- *May 2020 - Sept. 2020*, **Intelligent Car Racing Competition. (Team Leader)** 

  [China's 15th National Collegiate Smart Car Race] 
  
  To achieve higher speed in the racing, besides device adjustment and tuning, we carried out the following tasks: (1) Distortion correction for LiDAR mapping process; (2) Introduction of strong constraints for obstacle avoidance in local planners; (3) Construction of LiDAR-IMU Odometry (LIO). 
  
  Successfully advanced in the simulation competition of the North China division and subsequently won the national second prize in the final race.

<table><tr>
<td style="width:47.5%"> <a href="https://youtu.be/GT1CXNN92-o" title="Racecar"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688913924/video_to_markdown/images/youtube--GT1CXNN92-o-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Smart car race demo (simulation competition part)"></a></td>
<td><img src="images/comp_scene.png" alt="competition scene"></td>
</tr></table>

# 📖 Educations
- *Sept. 2021 - Jul. 2024 (Present)*, Master's student of Control Engineering, Beijing Institute of Technology. **(Grade: 85.26/100.0)**
- *Sept. 2017 - Jul. 2021*, Bachelor of Measurement & Control Technology, China University of Mining & Technology, Beijing. **(Grade: 88.52/100)**

# 💻 Internships
- *2023.04 - 2023.05*, [PhiGent Robotics](https://www.phigent.ai/), Autonomous Driving R&D Intern.

# 🏅 Honors and Awards
- *2022.09* First Class Scholarship of Beijing Institute of Technology. 
- *2021.06* Outstanding Graduates of China University of Mining & Technology, Beijing. (Top 5%)
- *2021.06* First Prize of Excellent Bachelor Thesis of China University of Mining & Technology, Beijing. (Top 1%)
- *2020.09* National Second Prize of Collegiate Smart Car Competition.

# 📚 Skills
> Extensive experience in Mobile Robot/Unmanned Aerial Vehicle(UAV) development, both software and hardware.

- **Robotics Dev.:** ROS, PX4, Gazebo, PCL, Eigen, Ceres, etc. 
- **Programming:** C/C++, Python, LaTeX
- **Dev. Tools:** Git, Linux & Shell, Docker, etc.
- **Language:** English (CET-6: 551, TOEFL: 101), Chinese (Native)