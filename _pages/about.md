---
permalink: /
title: "Shilong Mu's Personal Profile"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- Custom styles to increase font size -->
<style>
  body {
    font-size: 17px; /* Adjust the font size as needed */
    line-height: 1.6; /* Optional: adjust line height for better readability */
  }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 📖 Personal Profile
Shilong Mu received his B.S. degree in Electronic Information Engineering from [China University of Mining and Technology](https://www.cumt.edu.cn/) in 2022. He is currently pursuing his M.S. degree in Data Science and Information Technology at the Smart Sensing and Robotics group [(SSR Group)](https://ssr-group.net/index.html) at [Tsinghua University](https://www.tsinghua.edu.cn/en/). His research focuses on robotic sensing and embodied AI, under the guidance of [Professor Wenbo Ding](https://scholar.google.com/citations?user=xo2FkgIAAAAJ&hl=zh-CN) in the SSR Group.

During his studies, Shilong received **national scholarships** for both graduate students (THU) and undergraduates (CUMT).

# 📝 Research Interests
Shilong Mu's academic and research endeavors are centered around the cutting-edge domains of:
- **Tactile sensing**
- **Human-machine interfaces**
- **Embodied AI**

Feel free to reach out for collaboration or discussions about research ideas.

Email: msl22 [AT] mails.tsinghua.edu.cn

<span class='anchor' id='-News'></span>
# 🔥 News

<!-- News container -->
<div class="news-container">
    <ul class="news-list" id="newsList">
        <!-- Add news items -->
        <li class="news-item">[2024/10] Shilong was awarded the <strong>National Scholarship</strong> for graduate students at Tsinghua University!</li>
        <li class="news-item">[2024/08] Our work, "HandySense," has been accepted by MobiCom PICASSO 2024.</li>
        <li class="news-item">[2024/07] Shilong and team won the first prize at TBSI RETREAT 2024 with **Robocare**.</li>
        <li class="news-item">[2024/06] The SSR Group 2021 Graduation Party was held in Shenzhen!</li>
        <li class="news-item">[2024/05] Shilong attended ICRA 2025 in Yokohama, Japan!</li>
        <li class="news-item">[2024/04] Shilong received the third prize at the National Outstanding Graduate Students Workshop.</li>
        <li class="news-item">[2023/09] Shilong participated in the 2023 Guangdong Graduate Forum and delivered a presentation.</li>
    </ul>
</div>

<style>
    .news-container {
        width: 100%;
        max-width: 600px;
        height: 150px; /* Display 3 news items (each 50px high) */
        overflow: hidden;
        position: relative;
        margin: 0 auto;
        background: #fff;
        border: 1px solid #ddd;
        border-radius: 8px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .news-list {
        list-style: none;
        margin: 0;
        padding: 0;
        position: absolute;
        animation: scroll-news 10s linear infinite;
    }

    .news-item {
        height: 50px; /* Ensure each item has consistent height */
        padding: 10px;
        line-height: 30px;
        background: #fff;
        border-bottom: 1px solid #ddd;
    }

    .news-item:last-child {
        border-bottom: none;
    }

    .news-item a {
        text-decoration: none;
        color: #007BFF;
    }

    .news-item a:hover {
        text-decoration: underline;
    }

    /* Scroll animation */
    @keyframes scroll-news {
        0% {
            transform: translateY(0);
        }
        100% {
            transform: translateY(-100%); /* Adjust for the number of visible items */
        }
    }

    /* Pause animation on hover */
    .news-list:hover {
        animation-play-state: paused;
    }
</style>


<span class='anchor' id='-Publications'></span>

# 📝 Publications

<!-- Publication 1: Nano-Energy 2023 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Nano-Energy 2023</div>
      <img src='images/EM_FINGER.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>A Platypus-inspired Electro-mechanosensory Finger for Remote Control and Tactile Sensing</li>
      <li><strong>Shilong Mu*</strong>, Shoujie Li*, Hongfa Zhao*, Zihan Wang, Xiao Xiao, Zenan Lin, Ziwu Song, Huaze Tang, Qinghao Xu, Dongkai Wang, Wang Wei Lee†, Changsheng Wu†, Wenbo Ding†.</li>
      <li><i>Nano Energy</i>, 2023, 116: 108790. (JCR:Q1; IF:17.6)</li>
      <li><a href="https://www.sciencedirect.com/science/article/pii/S2211285523006274?via%3Dihub">Link</a> | <a href="/assets/PDF/NanoEnergy-EM-Finger.pdf" target="_blank">PDF</a></li>
    </ul>
  </div>
</div>

<!-- Publication 2: ICRA 2024 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICRA 2024</div>
      <img src='images/ICRA 2024.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>Dual-modal Tactile E-skin: Enabling Bidirectional Human-Robot Interaction via Integrated Tactile Perception and Feedback</li>
      <li><strong>Shilong Mu*</strong>, Runze Zhao*, Zenan Lin, Yan Huang, Shoujie Li, Chenchang Li, Xiao-Ping Zhang, Wenbo Ding†.</li>
      <li><i>ICRA</i> 2024, Yokohama, Japan</li>
      <li><a href="https://arxiv.org/abs/2402.05725">Link</a> | <a href="/assets/PDF/Dual-modal%20Tactile%20E-skin.pdf" target="_blank">PDF</a> | <a href="https://sitesgoogle.com/view/touch-e-skin/" target="_blank">Project page</a></li>
    </ul>
  </div>
</div>

<!-- Publication 3: MobiCom Picasso 2024 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">MobiCom Picasso 2024</div>
      <img src='images/HandySense.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>HandySense: A Multimodal Collection System for Human Two-Handed Dexterous Manipulation</li>
      <li><strong>Shilong Mu*</strong>, Jingyang Wang*, Xinyue Chai, Xingting Li, Tong Wu, Wenbo Ding†.</li>
      <li><i>MobiCom Picasso</i> 2024, Washington D.C., USA</li>
      <li><a href="/assets/PDF/HandySense.pdf" target="_blank">PDF</a></li>
    </ul>
  </div>
</div>

<!-- Publication 4: ICRA 2024 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICRA 2024</div>
      <img src='images/SATac.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>SATac: A Thermoluminescence Enabled Tactile Sensor for Concurrent Perception of Temperature, Pressure, and Shear</li>
      <li>Ziwu Song*, Ran Yu*, Xuan Zhang, Kit Wa Sou, <strong>Shilong Mu</strong>, Wenbo Ding†.</li>
      <li><i>ICRA</i> 2024, Yokohama, Japan</li>
      <li><a href="[https://arxiv.org/abs/2403.09855">Link</a> | <a href="/assets/PDF/SATac-ICRA2024.pdf" target="_blank">PDF</a></li>
    </ul>
  </div>
</div>

<!-- Publication 5: IEEE Sensors Journal 2024 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">IEEE Sensors Journal 2024</div>
      <img src='images/TacTID.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>TacTID: High-performance Visuo-Tactile Sensor-based Terrain Identification for Legged Robots</li>
      <li>Ziwu Song∗, Chenchang Li∗, Zhentan Quan, <strong>Shilong Mu</strong>, Xiaosa Li, Ziyi Zhao, Wanxin Jin, Chenye Wu, Wenbo Ding, Xiao-Ping Zhang, Fellow, IEEE.</li>
      <li><i>IEEE Sensors Journal</i> 2024</li>
      <li><a href="https://ieeexplore.ieee.org/document/10576071">Link</a> | <a href="/assets/PDF/TacTID.pdf" target="_blank">PDF</a></li>
    </ul>
  </div>
</div>

<!-- Publication 6: UbiComp 2023 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">UbiComp 2023</div>
      <img src='images/UbiComp2.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>Multimodal Surface Sensing based on Hybrid Flexible Triboelectric and Piezoresistive Sensor</li>
      <li>Zenan Lin*, Kai Chong Lei*, <strong>Shilong Mu</strong>, Ziwu Song, Yuan Dai, Wenbo Ding†, Xiao-Ping Zhang.</li>
      <li><i>UbiComp</i> 2023, [Location]</li>
      <li><a href="https://dl.acm.org/doi/10.1145/3544793.3560404">Link</a> | <a href="/assets/PDF/UbiComp2.pdf" target="_blank">PDF</a></li>
    </ul>
  </div>
</div>

<span class='anchor' id='-Pics'></span>

# 📸 Pics

<style>
  /* Contain the entire image gallery in a container */
  .image-carousel {
    display: flex;
    overflow: hidden; /* Hide the extra images outside the container */
    width: 100%; /* Make it responsive */
    justify-content: space-around; /* Ensure images are spaced evenly */
  }

  /* Create the scroll effect with animation */
  .image-carousel .carousel-items {
    display: flex;
    animation: scroll-images 15s linear infinite; /* Animation name, duration, timing function, and repeat */
  }

  /* Define the scrolling animation */
  @keyframes scroll-images {
    0% {
      transform: translateX(0);
    }
    100% {
      transform: translateX(-100%); /* Move the container to the left, fully scrolling the images */
    }
  }

  /* Style the images */
  .image-carousel img {
    width: 500px;
    height: 300px; /* Set consistent height for all images */
    object-fit: cover;
    margin-right: 20px; /* Add space between images */
  }
</style>

<!-- Image carousel wrapper -->
<div class="image-carousel">
  <div class="carousel-items">
    <!-- Add images inside this wrapper -->
    <img src="images/Lover1.png" alt="With my lover in 2023, Shenzhen">
    <img src="images/ziji.png" alt="Relaxation time, Shenzhen">
    <img src="images/qiusai.png" alt="China vs. South Korea football match, Shenzhen">
    <img src="images/RoboticX.png" alt="Robotics X Lab">
    <img src="images/SSR2023.PNG" alt="SSR Group 2023 annual summary meeting, Macau">
    <img src="images/SSR2022.PNG" alt="SSR Group 2022 annual summary meeting, Shenzhen">
  </div>
</div>

<span class='anchor' id='-VisitMap'></span>

# 🗺️ Visit Map

<a href="https://clustrmaps.com/site/1byil"><img src="https://clustrmaps.com/map_v2.png?cl=ffffff&w=800&t=m&d=X3J61-hp75joVFvuLSJlgpbB6riHUwJsEuuJ_A-gLmM&co=2d78ad&ct=ffffff" /></a>

