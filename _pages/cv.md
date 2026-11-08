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
* M.S. in Computer Science & Applied Math, Weizmann Institute of Science, 2024
* B.S. in Mathematics, The Open University of Israel, 2018, Academic in High School program (2015–2018), GPA: 88

Work experience
======
* AI Researcher, GE Research
  * Tel Aviv
  * Research in computer vision and machine learning, including vision-language models, explainable object and action classification, part-attribute recognition, and LLM/VLM applications in medical imaging.
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
