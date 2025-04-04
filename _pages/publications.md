---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
### Conference
1. [Finding and Understanding Defects in Static Analyzers by Constructing Automated Oracles.](https://tingsu.github.io/files/fse24-sa-find-bugs.pdf)  <br>
**Weigang He**, Peng Di, Mengli Ming, Chengyu Zhang, Ting Su*, Shijie Li, Yulei Sui  <br>
ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE), 2024.

1. [Automata-based Trace Analysis for Aiding Diagnosing GUI Testing Tools for Android.](https://tingsu.github.io/files/fse23-DDroid.pdf)  <br>
Enze Ma, Shan Huang, **Weigang He**, Ting Su*, Jue Wang, Huiyu Liu, Geguang Pu, Zhendong Su  <br>
ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE), 2023.

2. [Data flow testing for PLC programs via dynamic symbolic execution.](https://ieeexplore.ieee.org/document/9712019)  <br>
**Weigang He**, Xia Mao, Ting Su, Yanhong Huang, and Jianqi Shi. <br>
28th Asia-Pacific Software Engin eering Conference, APSEC 2021, Taipei, Taiwan, December 6-9, 2021, pages 152–160. IEEE, 2021.

3. [Automated test generation for iec 61131-3 st programs via dynamic symbolic execution.](https://www.sciencedirect.com/science/article/pii/S0167642321000010)<br>
   **Weigang He**, Jianqi Shi, Ting Su, Zeyu Lu, Li Hao, and Yanhong Huang. <br>
   Science of Computer Programming, 206:102608, 2021.


<!-- 
 * [ESEC/FSE 2022] **Haoxin Tu**, Lingxiao Jiang, Xuhua Ding, and He Jiang, "FastKLEE: Faster Symbolic Execution via Reducing Redundant Bound Checking of Type-Safe Pointers", in *the Tool Demonstrations Track of ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2022)*. [[PDF]](https://haoxintu.github.io/files/fse2022-FastKLEE.pdf) [[Source Code]](https://github.com/haoxintu/FastKLEE) [[Video Demo]](https://youtu.be/iLLlZD384zM) [[Slides]](https://haoxintu.github.io/files/FastKLEE-slides.pdf)
 * [ISSRE 2022] **Haoxin Tu**, He Jiang, Xiaochen Li, Zhilei Ren, Zhide Zhou, and Lingxiao Jiang, "RemGen: Remanufacturing A Random Program Generator for Compiler Testing", in *the 33rd IEEE International Symposium on Software Reliability Engineering (ISSRE 2022)*. [[PDF]](https://haoxintu.github.io/files/issre2022-camera-ready.pdf) [[Source Code]](https://github.com/haoxintu/RemCCG) [[Slides]](https://haoxintu.github.io/files/RemGen-slides.pdf) -->


### Journal
1. [Automated Aliasing Specifications Generation for Library APIs with Fuzzing. ACM Transactions on Software Engineering and Methodology.]()<br>Shuangxiang Kan, Yuekang Li, **Weigang He**, Zhenchang Xing, Liming Zhu, Yulei Sui.<br> Automated Aliasing Specifications Generation for Library APIs with Fuzzing. ACM Transactions on Software Engineering and Methodology (TOSEM).
   
1. [Safety verification of iec 61131-3 structured text programs.](https://ieeexplore.ieee.org/document/9107345) <br>
Jiawen Xiong, Xiangxing Bu, Yanhong Huang, Jianqi Shi, and **Weigang He**. <br>
ßIEEE Transactions on Industrial Informatics, 17(4):2632–2640, 2020.

 <!-- * [TR 2022] **Haoxin Tu**, He Jiang, Zhide Zhou, Yixuan Tang, Zhilei Ren, Lei Qiao, and Lingxiao Jiang, "Detecting C++ Compiler Front-end Bugs via Grammar Mutation and Differential Testing", in *IEEE Transactions on Reliability*, 2022. [[IEEE Early Access]](https://ieeexplore.ieee.org/document/9777893) [[Authors' Draft]](https://haoxintu.github.io/files/tr-2022-draft.pdf) [[Bug Reports]](https://github.com/haoxintu/CCOFT/blob/main/reported-bugs.md) -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
