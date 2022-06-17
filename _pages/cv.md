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
* B.S. in Software Engineering, Beijing Jiaotong University, 2016
* M.S. in Software Engineering, Tsinghua University, 2019
* Ph.D in Information Science and Technology, Penn State University, 2023 (expected)

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

Work experience
======

* R&D intern, Beijing Blue-dot Data Technology Co. 
  * Feb. 2018 - Aug. 2018
  * Classified company relation with attention-based PCNN model and improved the performance recursively using Active Learning
* R&D intern, IBM & Donghua Joint Innovation Laboratory
  * Mar. 2016 - Jun. 2016
  * Applied machine learning algorithms to detect wind turbine fault using Supervisory Control and Data Acquisition (SCADA) data
  * Developed a power flow calculation tool with Newton–Raphson solution method
* R&D intern, Baidu, Inc
  * Jul. 2015 - Jan. 2016
  * Extracted relation of entities from an unstructured corpus using Distant Supervision algorithm
  * Developed an algorithm to calculate confidence scores of the extracted subject-predicate-object (SPO) triples

Skills
======

* Programming skills: Python, C++, C, Matlab, PHP, MySQL
* ML libraries: Tensorflow, Pytorch, Scikit-learn, Scipy, Numpy, Pandas
* Embedded devices analysis: QEMU, Panda, Avatar2
* Reverse engineering: IDA Pro, Angr
