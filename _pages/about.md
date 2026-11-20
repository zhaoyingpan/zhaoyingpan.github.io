---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD candidate in Electrical and Computer Engineering at Purdue University, advised by [Prof. Xiaoqian Wang](https://engineering.purdue.edu/~joywang/).

Prior to Purdue, I worked with [Prof. Andrew Owens](https://andrewowens.com/) and [Daniel Geng](https://dangeng.github.io/) during my master's studies. Earlier, I collaborated with [Jinge Ma](https://jingema99.github.io/jingema.github.io/) and [Yutong Xie](https://yutxie.com/) under the guidance of [Prof. Qiaozhu Mei](http://www-personal.umich.edu/~qmei/). I also worked with [Ying Yang](https://yingyangum.github.io/) and [Prof. Daniel Klionsky](https://www.lsi.umich.edu/science/our-labs/klionsky-lab/daniel-klionsky-phd). During my undergraduate studies, I collaborated with [Zhiqiang Yuan](https://github.com/xiaoyuan1996) under the supervision of [Prof. Kun Fu](https://scholar.google.com/citations?hl=en&user=9ROSSEMAAAAJ) and [Prof. Xian Sun](https://scholar.google.com/citations?hl=en&user=xWKPHDYAAAAJ).

My research focuses on understanding and improving the reliability of machine learning models, particularly their ability to learn from and reason under conflicting or misleading evidence. I develop theoretical foundations and practical methods for building reliable multimodal foundation models. More recently, my work has expanded to address the reliability of large language models (LLMs) and the safety of autonomous AI agents. I am open to new research areas and potential collaborations.

<span style="color: red;">I'm actively looking for internship opportunities for 2027 Summer!</span>

Education
=========

**Purdue University** <span style="float: right;">2023–present</span>  
PhD in Electrical and Computer Engineering  
Advisor: [Prof. Xiaoqian Wang](https://engineering.purdue.edu/~joywang/)

**University of Michigan** <span style="float: right;">2021–2023</span>  
MS in Electrical and Computer Engineering, specialization in Computer Vision  
Advisor: [Prof. Andrew Owens](https://andrewowens.com/) and [Prof. Qiaozhu Mei](http://www-personal.umich.edu/~qmei/)

**University of Chinese Academy of Sciences** <span style="float: right;">2017–2021</span>  
BE in Electronic and Information Engineering  
Bachelor's thesis with honors: *Image Caption Generating of High-Resolution Remote Sensing Images*  
Advisors: [Prof. Kun Fu](https://scholar.google.com/citations?hl=en&user=9ROSSEMAAAAJ) and [Prof. Xian Sun](https://scholar.google.com/citations?hl=en&user=xWKPHDYAAAAJ)

Publications
============

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



Projects
========

- **The Evolution of AI and Data Mining.** We analyzed computer science papers spanning half a century and studied how the distribution of research domains changed over time. [Watch the video](https://www.youtube.com/watch?v=J0nB0uRRCo4).

Teaching
========

{% assign teaching_by_date = site.teaching | sort: "date" | reverse %}
{% for post in teaching_by_date %}
  {% include archive-single.html %}
{% endfor %}

Service
=======

{% assign service_page = site.pages | where: "url", "/service/" | first %}
{{ service_page.content | markdownify }}
