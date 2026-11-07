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
* **Ph.D in Computer Science** (2024 - Present), Hong Kong University of Science and Technology (HKUST NLP Group). Advisor: Professor Junxian He
* **B.Eng. in Computer Science** (2020 - 2024), Shanghai Jiao Tong University (SJTU). Awarded the Zhiyuan Honor Scholarship

Work experience
======
* **Research Intern at MINIMAX** (February 2025 - Present)
* **Research Intern at Tencent WXG** (June 2024 - September 2024). Advisor: Zifei Shan
* **Research Intern at Shanghai AI Lab** (June 2023 - December 2023). Advisor: Prof. Yu Cheng

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models
* LLM Truthfulness and Interpretability

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