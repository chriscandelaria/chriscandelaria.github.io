---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

What follows is an abridged version of my CV. You may also download a PDF version of my <a style='color: darkblue;' href="https://chriscandelaria.github.io/files/Candelaria-CV.pdf">full-length CV</a>.

{% include base_path %}

# Education
* B.A. in Economics, Stanford University, 2006
* M.A. in Economics, Stanford University, 2014
* Ph.D in Economics of Education and Education Policy, Stanford University, 2016

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

