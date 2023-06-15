---
layout: archive
permalink: /
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Information Science and Technology, Penn State University, 2023 (expected)
* M.S. in Software Engineering, Tsinghua University, 2019
* B.S. in Software Engineering, Beijing Jiaotong University, 2016

Research experience
======
* Pennsylvania State University
  * Designed a reinforcement learning based algorithm to generate adversarial malware samples against graph based malware detection
  * Generate malicious packets (and sessions) that can simultaneously compromise the target machine and evade the DL based network attack detection model
  * Derived condition-action rules from the MCU manuals using NLP techniques to build emulation models of the peripherals for automated firmware testing
  * Advisor: Dr. Peng Liu

* Tsinghua University
  * Provided a distance-preserving encoding mechanism for potential privacy leakage and a clustering method adapted for the encoding mechanism
  * Encoded numerical values into hamming space based on differential privacy and pufferfish privacy to achieve high privacy guarantees while preserving record-linking utilities
  * Deep learning based malware detection using API call sequence
  * Advisor: Dr. Xiaojun Ye
  
Publications
======

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
