---
permalink: /
title: "Yahao Fan"
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

I am currently a Master student at the VDI Center, ShanghaiTech University, under the supervision of [Prof. Ye Shi](https://shiye21.github.io), who is an expert in the field of Optimization, Generative Models, Reinforcement Learning, and Embodied AI. I received my B.E. degree from Zhengzhou University.

My Research interest include Embodied AI, Legged Robots and Simulation infrastructure. I am looking for internship and full-time opportunities in these areas. If you are interested in my research or want to collaborate with me, please feel free to contact me! You can find my Curriculum Vitae **[here](/assets/pdf/curriculum_vitae.pdf)**.

Email: fanyahao AT shanghaitech DOT edu DOT cn


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='papers/DreamPolicy/DreamPolicy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**DreamPolicy: A Unified World-model Policy for Scalable Humanoid Locomotion, ArXiv.** 

**Yahao Fan\#**, Tianxiang Gui\#, Kaiyang Ji\#, Shutong Ding, Chixuan Zhang, Yifeng Xu, Ke Yang, Jiayuan Gu, Jingyi Yu, Jingya Wang, Ye Shi\*

[[**paper**]](https://arxiv.org/abs/2505.18780)
<!-- [[**project**]](https://dreampolicy.github.io/)   -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025 Workshop</div><img src='papers/Sisyphus/Sisyphus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Sisyphus: An attention-driven humanoid object interaction policy, IROS 2025 Workshop: Augmentative Human–Robot Interaction.** 

Tianxiang Gui, Ke Yang, **Yahao Fan**, Chixuan Zhang, Jingya Wang\*, Ye Shi\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='papers/Humanoid-lla/humanoidlla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Commanding humanoid by free-form language: A large language action model with unified motion vocabulary, ArXiv.** 

Zhirui Liu\#, Kaiyang Ji\#, Ke Yang, **Yahao Fan**, Jingyi Yu, Ye Shi, Jingya Wang\*

[[**paper**]](https://arxiv.org/abs/2511.22963)
[[**project**]](https://humanoidlla.github.io/)
</div>
</div>

# 📖 Educations
- *2024.09 - now*, ShanghaiTech University, School of Information Science and Technology, major in **Computer Technology**
- *2020.09 - 2024.06*, Zhengzhou University, major in **Computer Science and Technology**


# 💻 Internships

<div class='exp-box'>
<div class='exp-box-logo'><img src='images/logos/agibot.png' alt="AgiBot logo"></div>
<div class='exp-box-text' markdown="1">
**Reinforcement Learning Motion Control Intern** · [AgiBot](https://www.agibot.com) (智元创新)<br>
*2026.07 - Present · Central R&D Department*

- Led the Lingxi X2 REACT framework pre-research and embodiment adaptation, migrating the diffusion generator and tracker from PARC to the Lingxi series.
- Reproduced [DreamPolicy](https://arxiv.org/abs/2505.18780) on Lingxi X2, closing the training - generation - deployment loop of a unified multi-terrain locomotion policy with over 95% success rate on complex terrain.
</div>
</div>

<div class='exp-box'>
<div class='exp-box-logo'><img src='images/logos/gigaai.png' alt="GigaAI logo"></div>
<div class='exp-box-text' markdown="1">
**Embodied AI RL Motion Control Algorithm Intern** · [GigaAI](https://www.gigaai.cc) (极佳视界)<br>
*2026.03 - 2026.07 · Large Model Architecture Department*

- Led the GigaBrain-PingPong project: multi-embodiment humanoid training framework, unified task modeling, and ball-trajectory prediction with hit-recovery control, reaching over 99% simulated hit success.
- Deployed on Unitree G1 and GigaAI Maker L01 with 132 consecutive human-robot rallies, a record for humanoid table tennis, featured in GigaAI's [official announcement](https://mp.weixin.qq.com/s/BgtrRQ80jUhw9zLC9pGxQg) and shown at WRC 2026.
</div>
</div>

- *2024.03 - 2024.09*, Visiting Student, ShanghaiTech University, VDI Center, YesAI Lab


# 🛠 Skills

<table class="skills-table">
  <tr><td><strong>Programming</strong></td><td>Python, C++, Git, Bash, Markdown</td></tr>
  <tr><td><strong>Algorithms &amp; Frameworks</strong></td><td>Reinforcement Learning (PPO, AMP, PULSE), DAgger, Imitation Learning, ROS / ROS2</td></tr>
  <tr><td><strong>Robotics</strong></td><td>Rigid-body kinematics and dynamics, FK / IK solving, Pinocchio</td></tr>
  <tr><td><strong>Simulation</strong></td><td>Isaac Lab, Isaac Gym, MuJoCo, Genesis, Domain Randomization</td></tr>
  <tr><td><strong>Robot Platforms</strong></td><td>AgiBot Lingxi X2, Unitree G1, Unitree H1 / H1-2, Booster T1, Unitree Go2</td></tr>
</table>


# 🏆 Honors and Awards
- *2022*, Second Prize, RoboCup China (FIRA Small-Size League, Soccer Robot), Zhengzhou University
- *2022*, Second Prize, RoboCup China (Simulation 2D League, Soccer Robot), Zhengzhou University


# 🌍 Community
- *2026*, **WRC 2026** — demonstrated the GigaBrain-PingPong humanoid table tennis system on site.
- *2025*, **ICCV 2025 Challenge Organizer** — built the multi-terrain locomotion benchmark platform, evaluation environments, and rules.
- *2025*, **GDPS 2025 Robotics Showcase** — invited to demonstrate reinforcement-learning-driven humanoid dance.
- Contributor to the **InstinctLab**, **GenesisLab**, and **Newton Physics Engine** open-source communities.
