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
* BEng in Landscape Architecture, Southeast University, 2022

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

Academic service
======
* Journal referees: Humanities and Social Sciences Communications, Computational Urban Science
