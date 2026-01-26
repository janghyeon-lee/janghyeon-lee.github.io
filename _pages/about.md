---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  body {
    color: #000000; /* Ensures all text is pure black */
  }

  /* Remove any border or shadow under headers */
  h1, h2, h3, h4, h5, h6 {
    border-bottom: none !important; /* Removes any border below the header */
    box-shadow: none !important; /* Removes any shadow that might create a line */
    margin-bottom: 0 !important; /* Optional: Reduce any bottom margin that adds space */
  }

  /* Style for soft line between sections using border */
  hr {
    display: block;
    margin: 1em 0; /* Adds space around the line */
    border: 0; /* Removes default border */
    border-top: 1px solid #ddd; /* Soft grey line with border on top */
  }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About 
I am a PhD student in Computer Science at [University of Minnesota (UMN)](https://twin-cities.umn.edu/), advised by [Yao-Yi Chiang](https://knowledge-computing.github.io/) and [Dalton Lunga](https://www.ornl.gov/staff-profile/dalton-d-lunga).

My research focuses on [self-supervised learning (SSL)](https://en.wikipedia.org/wiki/Self-supervised_learning), with an emphasis on transferability and efficiency. I am interested in understanding how SSL models learn representations that generalize across diverse downstream tasks, and how these representations can be made more efficient.

Prior to this, I received my MS and BS in Computing Science from [Simon Fraser University (SFU)](https://www.sfu.ca/), and a BS in Materials Science & Engineering from [Korea University](https://www.korea.edu/sites/en/index.do). I also did an internship at [KAIST](https://www.kaist.ac.kr/en/), which ignited my journey in AI.

# [Curriculum Vitae](https://drive.google.com/file/d/1m_peQoGdHjLE8ZRAdHklRb6JqteGw9U6/view?usp=sharing) (updated Jan. 2026)
<hr> <!-- Soft line after Curriculum Vitae -->

# 🎉 News
- *2026.01*: I will continue my internship with the [GeoAI group](https://www.ornl.gov/group/geoai) at Oak Ridge National Laboratory (ORNL 🌿) this Spring!

<details>
  <summary>&nbsp;Click to expand (2025)</summary>
  
  <article markdown="1" class="post-content">
  - *2025.12*: My undergraduate intern at UMN, [Nathan Stangler](https://nathanstangler.github.io/), presented our ongoing work: SolarCLIP (a CLIP model for the 🌞) at [URS](https://ugresearch.umn.edu/presentation-opportunities/fall-symposium/presenters/nathan-stangler).
  - *2025.12*: My undergraduate intern at UMN, [Shilong Xiang](https://shilongxiang.github.io/), received the [UROP Award](https://evcaa.d.umn.edu/undergraduate-research-opportunities-program-urop). Congrats!
  - *2025.08*: I will continue my internship with the [GeoAI group](https://www.ornl.gov/group/geoai) at Oak Ridge National Laboratory (ORNL 🌿) this Fall!
  - *2025.08*: Our paper, <em>Transit for All: Mapping Equitable Bike2Subway Connection using Region Representation Learning</em>, was accepted to [SIGSPATIAL 2025](https://sigspatial2025.sigspatial.org/)! 🌎
  - *2025.05*: I will be interning with the [GeoAI group](https://www.ornl.gov/group/geoai) at Oak Ridge National Laboratory (ORNL 🌿) this Summer!
  - *2025.02*: My undergraduate intern at UMN, [Shilong Xiang](https://shilongxiang.github.io/), received the [MURAJ In-Action Grant Award](https://pubs.lib.umn.edu/index.php/muraj/MURAJInAction). Congrats!
  - *2025.01*: Our paper, <em>DiminishAR: Diminishing Visual Distractions via Holographic AR Displays</em>, was accepted to [CHI 2025](https://chi2025.acm.org/)! See you in Yokohama 🌸
  - *2025.01*: I am fortunate to receive the CSE Data Science Initiative (DSI) Fellowship. We will be taking Spatial AI to the Sun! 🌞
  </article>
</details>

<details>
  <summary>&nbsp;Click to expand (2024)</summary>
  
  <article markdown="1" class="post-content">
  - *2024.10*: I made it into the top 10 teams of the [HuMob'24 competition](https://wp.nyu.edu/humobchallenge2024/) out of 100+ participating teams! See you in Atlanta.
  - *2024.09*: Our paper, <em>Context-Aware Trajectory Anomaly Detection</em>, was accepted to [GeoAnomalies'24](https://onspatial.github.io/GeoAnomalies24/)!
  - *2024.08*: I officially started my Ph.D. journey at UMN :)
  - *2024.03*: I won the [SFU CS Diversity Award](https://www.sfu.ca/computing/diversity-in-computing-science/activities/cs-diversity-project-presentations-2024.html)!
  </article>
</details>

<details>
  <summary>&nbsp;Click to expand (2023)</summary>
  
  <article markdown="1" class="post-content">
  - *2023.12*: I completed my master's degree in CS at [SFU](https://www.sfu.ca/).
  - *2023.06*: I won the [SFU CS Innovation Prize](https://www.sfu.ca/computing/current-students/graduate-students/academic-programs/professional-master-of-science-in-computer-science/project-showcase/is-seeing-still-not-necessarily-believing-.html)!
  </article>
</details>
<hr> <!-- Soft line after "Click to expand" -->

# ✒️ Publications (selected)
<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='images/diminishar.gif' alt="sym" width="90%">
  </div>
  <div class='paper-box-text' markdown="1">

## [DiminishAR: Diminishing Visual Distractions via Holographic AR Displays](https://dl.acm.org/doi/10.1145/3706598.3713415)
**JangHyeon Lee**, Lawrence Kim

<span style="color:grey">ACM CHI 2025<br>[Acceptance rate = 24.9% (1249/5020)]</span>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='images/humob24.png' alt="sym" width="90%">
  </div>
  <div class='paper-box-text' markdown="1">

## [CrossBag: A Bag of Tricks for Cross-City Mobility Prediction](https://dl.acm.org/doi/abs/10.1145/3681771.3699935)
**JangHyeon Lee**, Yao-Yi Chiang

<span style="color:grey">ACM SIGSPATIAL HuMob 2024<br>[Top 10 out of 100+ teams]</span>
