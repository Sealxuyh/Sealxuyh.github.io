---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MEng in Landscape Architecture, Southeast University, 2025 (expected)
  * Average Score: 90.68/100, Rank: 2/28
  * Advisor: Jun Tang
* BEng in Landscape Architecture, Southeast University, 2022
  * Average Score: 89.29/100, Rank: 4/28
  * Graduation Project: 93/100 (Advisor: Xiaosu Ma)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
    
Conference presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
