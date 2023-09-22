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

发表论文
======
* 人机交互：触觉传感器、手势识别
* 压缩感知算法重构：稀疏贝叶斯、扩散模型、深度学习
* 电阻抗成像技术
1. Ma Gang; Chen Haofeng; Wang Peng, and Wang Xiaojie*, Multi-frame constrained block sparse Bayesian learning for flexible tactile sensing using electrical impedance tomography[J]. IEEE Transactions on Computational Imaging, 2022, 8: 438-448.
2. Ma Gang, Hao Zhiliang, Wu Xuan and Wang Xiaojie*, An Optimal Electrical Impedance Tomography Drive Pattern for Human-Computer Interaction Applications[J], IEEE Transactions on Biomedical Circuits and Systems, 2020, 14(3): 402-411.
3. Chen Haofeng, Yang Xuanxuan, Wang Peng, Geng Jialu, Ma Gang* and Wang Xiaojie*, A large-area flexible tactile sensor for multi-touch and force detection using electrical impedance tomography[J]. IEEE Sensors Journal, 2022, 22(7): 7119-7129.
4. Chen Haofeng, Yang Xuanxuan, Geng Jialu, Ma Gang* and Wang Xiaojie*, A skin-like hydrogel for distributed force sensing using an electrical impedance tomograph y-based pseudo-array method[J]. ACS Applied Electronic Materials, 2023.
5. Ma Gang, Hao Zhiliang, Wu Xuan, and Wang Xiaojie*, An Electrical Impedance Tomography Drive Pattern for Fast and Accurate Gesture Recognition With Less Electrodes[C], ASME Smart Materials, Adaptive Structures and Intelligent Systems (SMASIS), American Society of Mechanical Engineers, Louisville, KY, USA 2019, 59131, V001T08A001. 
