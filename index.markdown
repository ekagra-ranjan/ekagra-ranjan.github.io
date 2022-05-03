---
layout: resume
title: About
---

<!-- Bio -->
I am interested in Machine Learning, especially in the field of Deep Learning. I have experience in Graph Machine Learning, Computer Vision (CV), and Natural Language Processing (NLP).

• During my undergrad days, I published at top-tier conferences of machine learning like AAAI that have garnered over 100 citations <br>
• Open source contributor to famous projects like Pytorch Geometric and TorchVision (Pytorch) <br>
• Recipient of various prestigious academic fellowships as well as Microsoft AI for Earth grant <br>
• Been part of teams that have won multiple national and international competitions <br>

I completed my Bachelors from <a href="https://www.iitg.ac.in/"><span class="highlight"> Indian Institute of Technology (IIT) Guwahati. </span></a> Download <a href="https://drive.google.com/file/d/1HSDI4UDIxaVdJWPgYLgBoui_no298DgO/view?usp=sharing"><span class="highlight"> Resume. </span></a>

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
