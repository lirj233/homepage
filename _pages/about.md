---
permalink: /
title: "Renjie Li"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi, I am Renjie Li (李仁杰), a second-year PhD student in the [College of Computer Science and Technology](http://www.cs.zju.edu.cn/) at Zhejiang University (ZJU), expected to receive my PhD degree in 2029. I am co-advised by Prof. Wei Dong (董玮) and Prof. Yi Gao (高艺), and I work closely with Prof. Tong Sun (孙桐) and Prof. Jiamei Lv (吕嘉美).

Before joining ZJU, I received my B.E. degree from the School of Computer and Communication Engineering at Northeastern University at Qinhuangdao (NEUQ) in 2024, advised by Prof. Xi Cai (才溪).

I work on systems and security for AIoT, with a focus on confidential computing and secure DNN inference for IoT and edge environments. I am a member of the [EmNets research group](https://www.emnets.cn/zh/).

Research Interests
======

- AIoT systems and security
- Confidential computing
- Secure DNN inference
- Edge GPU systems
- Real-time AI systems
- IoT stream computing

Selected Publications
======

{% for post in site.publications reversed limit:3 %}
{% include archive-single.html %}
{% endfor %}
