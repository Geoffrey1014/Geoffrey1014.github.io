---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
### Conference
1. Seed Patches to CodeQL Queries: Compositional Synthesis with Proof-of-Concept Validation. <br>
**Weigang He**, Xiao Cheng, Shuangxiang Kan, Wei Li, Xingrui Yu, Ivor Tsang, Yulei Sui <br>
IEEE/ACM International Conference on Software Engineering (ICSE), 2027. *To appear.*

1. [Finding and Understanding Defects in Static Analyzers by Constructing Automated Oracles.](https://tingsu.github.io/files/fse24-sa-find-bugs.pdf)  <br>
**Weigang He**, Peng Di, Mengli Ming, Chengyu Zhang, Ting Su*, Shijie Li, Yulei Sui  <br>
ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE), 2024.

1. [Automata-based Trace Analysis for Aiding Diagnosing GUI Testing Tools for Android.](https://tingsu.github.io/files/fse23-DDroid.pdf)  <br>
Enze Ma, Shan Huang, **Weigang He**, Ting Su*, Jue Wang, Huiyu Liu, Geguang Pu, Zhendong Su  <br>
ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE), 2023.

2. [Data flow testing for PLC programs via dynamic symbolic execution.](https://ieeexplore.ieee.org/document/9712019)  <br>
**Weigang He**, Xia Mao, Ting Su, Yanhong Huang, and Jianqi Shi. <br>
28th Asia-Pacific Software Engineering Conference, APSEC 2021, Taipei, Taiwan, December 6-9, 2021, pages 152–160. IEEE, 2021.

3. [Automated test generation for iec 61131-3 st programs via dynamic symbolic execution.](https://www.sciencedirect.com/science/article/pii/S0167642321000010)<br>
   **Weigang He**, Jianqi Shi, Ting Su, Zeyu Lu, Li Hao, and Yanhong Huang. <br>
   Science of Computer Programming, 206:102608, 2021.




### Journal
1. [Spectre: Automated Aliasing Specification Generation for Library APIs with Fuzzing.](https://doi.org/10.1145/3725811) <br>
Shuangxiang Kan, Yuekang Li, **Weigang He**, Zhenchang Xing, Liming Zhu, Yulei Sui. <br>
ACM Transactions on Software Engineering and Methodology (TOSEM), 2025.
   
1. [Safety verification of iec 61131-3 structured text programs.](https://ieeexplore.ieee.org/document/9107345) <br>
Jiawen Xiong, Xiangxing Bu, Yanhong Huang, Jianqi Shi, and **Weigang He**. <br>
IEEE Transactions on Industrial Informatics, 17(4):2632–2640, 2020.


### Workshop
1. QLM: CodeQL Query Synthesis with Compositional PoC Validation. <br>
**Weigang He**, Xiao Cheng, Shuangxiang Kan, Wei Li, Xingrui Yu, Ivor Tsang, Yulei Sui <br>
Journal Ahead Workshop (JAWs), co-located with ICSE 2026. *Presentation; an earlier version of the ICSE'27 paper.*

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
