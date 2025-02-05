---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


* Xue Xu, Wenhao He, Fei Yin and Cheng-Lin Liu. Page Segmentation for Historical Handwritten Documents Using Fully
Convolutional Networks. International Conference on Document Analysis and Recognition(ICDAR), 2017.
* Yue Xu, Fei Yin, Zhaoxiang Zhang and Cheng-Lin Liu. Multi-task Layout Analysis for Historical Handwritten Documents
Using Fully Convolutional Networks. International Joint Conference on ArtificialIntelligence(IJCAI), 2018.
* Yue Xu, Fei Yin, Da-Han Wang, Xu-Yao Zhang, Zhaoxiang Zhang and Cheng-Lin Liu, CASIA-AHCDB: A Large-scale Chinese
Ancient Handwritten Characters Database. International Conference on Document Analysis and Recognition(ICDAR), 2019.
* Yue Xu, Xu-Yao Zhang, Zhaoxiang Zhang, Cheng-Lin Liu. Large-scale continual learning for ancient Chinese character recognition. Pattern Recognition. 2024.
