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

My research focuses on the [transferability](https://en.wikipedia.org/wiki/Transfer_learning) of learned representations, particularly in [self-supervised learning (SSL)](https://en.wikipedia.org/wiki/Self-supervised_learning). I am interested in understanding how SSL models learn representations that generalize across diverse downstream tasks, and how such representations can be learned efficiently.

Prior to this, I received my MS and BS in Computing Science from [Simon Fraser University (SFU)](https://www.sfu.ca/), and a BS in Materials Science & Engineering from [Korea University](https://www.korea.edu/sites/en/index.do). I also did an internship at [KAIST](https://www.kaist.ac.kr/en/), which ignited my journey in AI.

# [CV](https://drive.google.com/file/d/1m_peQoGdHjLE8ZRAdHklRb6JqteGw9U6/view?usp=sharing) (Jan. 2026)
<hr> <!-- Soft line after Curriculum Vitae -->

# 🎉 News
- *2026.01*: Our work on self-supervised learning (details to come) was accepted to [ICLR 2026](https://iclr.cc/)! See you in Rio 🇧🇷
- *2026.01*: I will continue my internship with the [GeoAI group](https://www.ornl.gov/group/geoai) at ORNL this Spring.

<details>
  <summary>&nbsp;Click to expand (2025)</summary>
  
  <article markdown="1" class="post-content">
  - *2025.12*: My undergrad intern at UMN, [Nathan Stangler](https://nathanstangler.github.io/), presented our work <em>SolarCLIP (a CLIP model for the Sun)</em> at [URS](https://ugresearch.umn.edu/presentation-opportunities/fall-symposium/presenters/nathan-stangler).
  - *2025.12*: My undergrad intern at UMN, [Shilong Xiang](https://shilongxiang.github.io/), received the [UROP Award](https://evcaa.d.umn.edu/undergraduate-research-opportunities-program-urop). Congrats!
  - *2025.08*: I will continue my internship with the [GeoAI group](https://www.ornl.gov/group/geoai) at ORNL this Fall.
  - *2025.08*: Our paper, <em>Transit for All: Mapping Equitable Bike2Subway Connection using Region Representation Learning</em>, was accepted to [SIGSPATIAL 2025](https://sigspatial2025.sigspatial.org/)!
  - *2025.05*: I will be interning with the [GeoAI group](https://www.ornl.gov/group/geoai) at ORNL this Summer.
  - *2025.02*: My undergrad intern at UMN, [Shilong Xiang](https://shilongxiang.github.io/), received the [MURAJ In-Action Grant Award](https://pubs.lib.umn.edu/index.php/muraj/MURAJInAction). Congrats!
  - *2025.01*: Our paper, <em>DiminishAR: Diminishing Visual Distractions via Holographic AR Displays</em>, was accepted to [CHI 2025](https://chi2025.acm.org/)! See you in Yokohama 🌸
  - *2025.01*: I am fortunate to receive the [CSE Data Science Initiative (DSI) Fellowship](https://cse.umn.edu/dsi/DSI-support). We will be taking Spatial AI to the Sun!
  </article>
</details>

<details>
  <summary>&nbsp;Click to expand (2024)</summary>
  
  <article markdown="1" class="post-content">
  - *2024.10*: I made it into the top 10 teams of the [HuMob competition](https://wp.nyu.edu/humobchallenge2024/)! See you in Atlanta.
  - *2024.03*: I won the [SFU CS Diversity Award](https://www.sfu.ca/computing/diversity-in-computing-science/activities/cs-diversity-project-presentations-2024.html)!
  </article>
</details>

<details>
  <summary>&nbsp;Click to expand (2023)</summary>
  
  <article markdown="1" class="post-content">
  - *2023.06*: I won the [SFU CS Innovation Prize](https://www.linkedin.com/posts/sfupcs_is-seeing-still-not-necessarily-believing-activity-7074869783812296705-u1BJ)!
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

## [CrossBag: A Bag of Tricks for Cross-City Mobility Prediction](https://dl.acm.org/doi/10.1145/3681771.3699935)
**JangHyeon Lee**, Yao-Yi Chiang

<span style="color:grey">ACM SIGSPATIAL Human Mobility Prediction Challenge 2024<br>[Top 10 out of 100+ teams]</span>
