---
layout: single
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

**Computational Mechanics · Scientific Computing · Engineering**

I am a Ph.D. student at Yokohama National University, with a background in automotive engineering and professional experience in computer-aided engineering (CAE).

My current research focuses on computational mechanics, numerical methods, and efficient computational approaches for engineering applications.

Expected graduation: September 2027

[View Curriculum Vitae →]({{ '/cv/' | relative_url }})

## Research Interests

<div>
  Computational Mechanics<br>
  Topology Optimization<br>
  Reduced-Order Modeling<br>
  Machine Learning for Engineering
</div>

[Explore my research →]({{ '/research/' | relative_url }})

## Technical Skills

<ul style="list-style: none; padding-left: 0;">
  {% for skill in site.data.skills %}
  <li>
    <i class="fas fa-chevron-right icon-pad-right" aria-hidden="true"></i>
    <a href="{{ skill.url | relative_url }}">{{ skill.title | escape }}</a>
  </li>
  {% endfor %}
</ul>

[View all technical skills →]({{ '/skills/' | relative_url }})

## Education

<ul style="list-style: none; padding-left: 0;">
  <li>
    <i class="fas fa-graduation-cap icon-pad-right" aria-hidden="true"></i>
    <strong>Ph.D.</strong><br>
    Yokohama National University<br>
    Expected September 2027
  </li>
  <li>
    <i class="fas fa-graduation-cap icon-pad-right" aria-hidden="true"></i>
    <strong>M.Sc.</strong><br>
    University · Year
  </li>
  <li>
    <i class="fas fa-graduation-cap icon-pad-right" aria-hidden="true"></i>
    <strong>B.Sc.</strong><br>
    University · Year
  </li>
</ul>

## Work Experience

<div class="experience-list">
  <div class="experience-item">
    <span><strong>Company Name</strong><br>CAE Engineer</span>
    <span class="experience-date">Start – End</span>
  </div>
</div>

[View professional experience →]({{ '/work-experience/' | relative_url }})
