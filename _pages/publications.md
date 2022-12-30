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

# Projects
  * Urban Intersection Holographic Perception Layout and Control Strategy (Co-PI, Huawei Techonologies Co., Ltd., 2022-2023)
  * Smart scheduling algorithm for electric buses (Co-PI, Huawei Techonologies Co., Ltd., 2021-2023)
  * Risks to pedestrians of crossing in a traffic system with different driving rules (GRA, General Research Fund, Research Grants Council, Hong Kong SAR Government, Project No. 17203017, 2018-2020)
  * Multi-user voice-driven BIM-based navigation system for fire emergency response (GRA, U21 Graduate Collaborative Research Awards, Universitas 21, 2018-2019)
  * Traffic Flow Modeling and Operational Strategies Optimization for Urban Transportation Corridor Simulations (GRA, National Natural Science Foundation of China, China, Project No. 51508505, 2016-2018)
