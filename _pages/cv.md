---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

[Download my CV (PDF)](/files/CV_zhaoyingpan.pdf){: .btn .btn--primary }

Education
=========

- **Purdue University**, PhD in Electrical and Computer Engineering, 2023–present
- **University of Michigan**, MS in Electrical and Computer Engineering, 2021–2023
- **University of Chinese Academy of Sciences**, BE in Electronic and Information Engineering, 2017–2021

Publications
============

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

Teaching
========

{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
