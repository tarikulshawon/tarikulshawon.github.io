---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
Engineer and researcher with experience delivering data-driven solutions, speaking at community events, and supporting collaborative academic projects.

Experience
======
* Software and data projects that support research collaborations and applied machine learning efforts
* Workshops and talks focused on reproducible analytics and engineering best practices
* Mentoring students and early-career engineers on open-source practices

Education
======
* Details coming soon — full academic history will be published here after the next update

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
