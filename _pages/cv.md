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
* Ph.D. in Computer Science (2024-Present), Hong Kong University of Science and Technology (HKUST), advised by Professor Junxian He
* B.Eng. in Computer Science (2020-2024), Shanghai Jiao Tong University (SJTU)

Work experience
======
* February 2025 - Present: Research Intern
  * MINIMAX
* June 2024 - September 2024: Research Intern
  * Tencent WXG
* June 2023 - December 2023: Research Intern
  * Shanghai AI Lab

Skills
======
* Natural Language Processing
* Machine Learning

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
