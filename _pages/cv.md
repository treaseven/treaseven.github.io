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
* Ph.D in Changsha Hunan, National University of Defense Technology, 2023-
* B.S. in Beijing, Capital Normal University, 2019

Skills
======
* C/C++、python、verilog
* Django、linux、web

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
