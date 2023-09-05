---
layout: archive
title: "科研成果"
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



# 代表性科研项目

  * 主持，宁波市甬江人才工程青年创新人才项目，基于虚拟现实的港口自动驾驶环境下行人-车辆交互行为与风险研究，2024-2028
  * 主持，宁波大学人才引进启动项目，自动驾驶条件下港口道路区域人车交互安全研究，2023-2026
  * 联合主持，华为2012实验室技术课题，城市交叉口全息感知布局与控制策略研究，2022-2023
  * 联合主持，华为2012实验室技术课题，电动公交智慧排班优化算法研究，2021-2023
  * 参与，香港特别行政区政府研究资助局面上项目，17203017，Risks to Pedestrians of Crossing in a Traffic System with Different Driving Rules, 2018-2020
  * 参与，U21大学联盟项目，Multi-user voice-driven BIM-based navigation system for fire emergency response, 2018-2019
  * 参与，国家自然科学基金青年科学基金项目，51508505，面向城市交通通道仿真的交通流建模与组织优化，2016-2018
  * 参与，浙江省智能交通工程技术研究中心开放课题，杭州市主城区道路网中观交通仿真及综合管控优化策略研究，2015-2016
