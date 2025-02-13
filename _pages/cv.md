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
* Ph.D in [The University of Texas at Austin]()
* M.S. in [National Taiwan University]()
* B.S. in [National Taiwan University]()

Work experience
======
* Software Engineer
  * Mediatek
* Research Assistant
  * Academia Sinica
  
# Skills
# ======
# * Skill 1
# * Skill 2
#   * Sub-skill 2.1
#   * Sub-skill 2.2
#   * Sub-skill 2.3
# * Skill 3

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
