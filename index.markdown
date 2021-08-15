---
layout: resume
title: About
---

<!-- Bio -->
I am interested in Machine Learning, especially in the field of Deep Learning. I have experience in Computer Vision and Graph domain. Previously, I was into Data Science and have a good track record in national level competitions.

As a part of my undergrad internships, I have published at top-tier conferences of machine learning. I have been a part of teams that have won multiple hackathons, both international and national. I am also a recipient of various prestigious fellowships and Microsoft AI for Earth grant. 

I completed my Bachelors from <a href="https://www.iitg.ac.in/"><span class="highlight"> Indian Institute of Technology (IIT) Guwahati. </span></a>

{%- include component/social.html -%}

<hr class="hr-divider">

<!-- Publications -->
{%- if site.data.resume.config.publications -%}
{%- include resume/publications.html -%}
{%- endif -%}

<hr class="hr-divider">

<!-- Work Experience -->
{%- if site.data.resume.config.workexs -%}
{%- include resume/workexs.html -%}
{%- endif -%}

<hr class="hr-divider">

<!-- Achievements -->
{%- if site.data.resume.config.achievements -%}
{%- include resume/achievements.html -%}
{%- endif -%}

<!-- CSS -->
<link rel="stylesheet" href="{{ "/assets/css/resume/resume.css" | relative_url }}">