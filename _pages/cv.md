---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /about
---

{% include base_path %}

Education
======
* M.S. in Durham, Duke University (expected 2027)
* B.A. in Seattle, University of Washington, 2025

Research experience
======
* Spring 2025: Undergraduate Student Researcher
  * University of Washington, Department of Mathematics
  * Supervisor: Tvertko Tadic

  
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
