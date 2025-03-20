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
* Ph.D. in Applied Mathematics, KAIST, 1993
* M.S. in Applied Mathematics, KAIST, 1989
* B.S. in Mathematics, Yonsei Univ., 1987

Work experience
======
* Visiting Professor, School of Multimedia Design, SUES, China ('15 ~ '16)
* Post-doctoral, Prof. Tom Lyche, Dept. of Informatics, Univ. of Oslo, Norway ('99 ~ '00)
* Professor, Department of Computer Engineering, Dongseo University ('95 ~ )
* Senior Engineer, Division II Open Systems Lab. DACOM Corp. R&D Center ('93 ~ '95)
* Researcher, Computer Center, Korea Research Institute of Standards and Science ('92 ~ '93)

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

  
