---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

- PhD Student, College of Computer Science and Technology, Zhejiang University, 2024-present. Expected 2029.
- B.E., School of Computer and Communication Engineering, Northeastern University at Qinhuangdao, 2024.

Research Interests
======

- AIoT systems and security
- Confidential computing
- Secure DNN inference
- Edge GPU systems
- Real-time AI systems
- IoT stream computing

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
