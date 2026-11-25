---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD candidate in Electrical and Computer Engineering at Purdue University, advised by [Prof. Xiaoqian Wang](https://engineering.purdue.edu/~joywang/).

Prior to Purdue, I worked with [Prof. Andrew Owens](https://andrewowens.com/) and [Prof. Qiaozhu Mei](http://www-personal.umich.edu/~qmei/) during my master's studies. I also conducted research with [Yutong Xie](https://yutxie.com/). During my undergraduate studies, I was advised by [Prof. Kun Fu](https://scholar.google.com/citations?hl=en&user=9ROSSEMAAAAJ) and [Prof. Xian Sun](https://scholar.google.com/citations?hl=en&user=xWKPHDYAAAAJ).
<!-- Throughout my research journey, I have been fortunate to learn from and work with wonderful mentors and collaborators, including [Ying Yang](https://yingyangum.github.io/), [Yutong Xie](https://yutxie.com/), [Jinge Ma](https://jingema99.github.io/jingema.github.io/), [Daniel Geng](https://dangeng.github.io/), and [Zhiqiang Yuan](https://github.com/xiaoyuan1996). -->

My research focuses on understanding and improving the reliability of machine learning models, particularly their ability to learn from and reason under conflicting or misleading evidence. I develop theoretical foundations and practical methods for building reliable multimodal foundation models. More recently, my work has expanded to address the reliability of large language models (LLMs) and the safety of autonomous AI agents. I am open to new research areas and potential collaborations.

I am always open to research collaborations and new opportunities. Feel free to reach out if you are interested in working together!

<span style="color: red;">I am actively seeking internship opportunities for Spring/Summer 2027!</span>

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
<div class="home-teaching-list">
{% for post in teaching_by_date %}
  {% include archive-single.html %}
{% endfor %}
</div>

Service
=======

{% assign service_page = site.pages | where: "url", "/service/" | first %}
<div class="home-service">
{{ service_page.content | markdownify }}
</div>
