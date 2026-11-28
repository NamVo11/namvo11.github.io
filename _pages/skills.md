---
layout: single
title: "Skills"
permalink: /skills/
author_profile: true
---

Technical skills and practical experience. Detailed descriptions will be added here.

<ul style="list-style: none; padding-left: 0;">
  {% for skill in site.data.skills %}
  <li>
    <i class="fas fa-chevron-right icon-pad-right" aria-hidden="true"></i>
    <a href="{{ skill.url | relative_url }}">{{ skill.title | escape }}</a>
  </li>
  {% endfor %}
</ul>
