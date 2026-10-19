---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A full CV will be posted here. Only details I can state directly are included below.

Education
======
* Master's background in Electrical and Computer Engineering

Affiliation
======
* [UbiComp Lab](https://ubicomplab.cs.washington.edu/), University of Washington

Research interests
======
* Wearable and Ubiquitous Computing
* On-device Machine Learning
* Ultra-low-power and Battery-free Sensing

Publications
======
{% assign publication_count = site.publications | size %}
{% if publication_count == 0 %}
Selected publications will be listed here. See also the [Publications](/publications/) page.
{% else %}
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
{% endif %}

Experience, talks, teaching, and service
======
These sections will be added with the full CV.
