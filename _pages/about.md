---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a PhD student in *Software Engineering* at the [University of Technology Sydney (UTS)](https://www.uts.edu.au/), supervised by Prof. [Yulei Sui](https://yuleisui.github.io/). **I expect to graduate in mid-2027 and am looking for research positions in AI safety.**

I was a Research Assistant (Mentor: [Ting Su](https://tingsu.github.io/)) at East China Normal University (2022-2023) and a Visiting Scholar at Ant Group, Hangzhou, China (2022-2023). I got my M.S. in *Software Engineering* from [East China Normal University (ECNU)](https://english.ecnu.edu.cn/), Shanghai, China (2018-2021).


<!-- <p align="center" > <b> <i> <big> "To err is human, but to really foul things up you need a computer." </big> </i></b></p>
<p align="right"> - Paul R. Ehrlich </p> -->

### News
- **Oct 2026**: Our paper on synthesizing CodeQL queries from seed patches was accepted to **ICSE 2027**. The generated queries found 49 previously unknown bugs in the Linux kernel.

My research interests are in: 
- **AI safety through the lens of program analysis.** Many safety mechanisms, such as guardrails, prompt-injection detectors, AI-control monitors and reward verifiers, are judges that make false positives and false negatives. I want to understand why they fail, building on my work on finding and understanding defects in static analyzers.
- **Static analysis**: LLM-assisted static analysis that turns bug-fix patches into reusable CodeQL queries for the Linux kernel (ICSE'27), and alias specification generation for library APIs (TOSEM'25).
- **Fuzzing and software testing**: fuzzing compilers and program analyzers to find their false positives and false negatives (FSE'24), diagnosing automated GUI testing tools (FSE'23), and test generation via dynamic symbolic execution (APSEC'21, SCP'21).

### Research Programs
#### Testing Static Analysis Tools. (Mar.2022 – Aug.2023)
Aims to design an effective fuzzing test scheme to automatically find false negatives, false positives and tool crash defects of the static analysis tools within Ant group and Alibaba.

#### [Aiding Diagnosing Automated GUI Testing Tools for Android.](https://github.com/the-themis-benchmarks/home/tree/industrial_tools_evaluation) (Jul.2021 – Aug.2022)
Design and implementation of a tool to automatically instrument benchmarking apps and measure the
testing effects of automated testing tool on the benchmark.

#### [Automated Test Case Generation for PLC Programs.](https://github.com/Geoffrey1014/ST_DSE) (Jul.2019 – Jun.2021)
Design and implementation of algorithms to generate high-coverage unit test cases of PLC program for control flow and data flow coverage criteria based on dynamic symbolic execution.

<!-- #### Translation from the Simulink Model to the NuSVM Model. (Feb.2020 – Oct.2020)
Implementation of a tool to automatically translate airborne Simulink models to the NuSVM models to verify specifications.

#### Formal Analysis and Verification of Airborne Software Based on DO-333. (Nov.2018 – May.2019)
Utilizing the Air Data Computer software as the research object and applying different formal methods to verify software life-cycle artifacts to illustrate the formal methods and tools available in the verification process of airborne software. -->


### Publications
1. Seed Patches to CodeQL Queries: Compositional Synthesis with Proof-of-Concept Validation. <br>
**Weigang He**, Xiao Cheng, Shuangxiang Kan, Wei Li, Xingrui Yu, Ivor Tsang, Yulei Sui <br>
IEEE/ACM International Conference on Software Engineering (ICSE), 2027. *To appear.*

2. [Spectre: Automated Aliasing Specification Generation for Library APIs with Fuzzing.](https://doi.org/10.1145/3725811) <br>
Shuangxiang Kan, Yuekang Li, **Weigang He**, Zhenchang Xing, Liming Zhu, Yulei Sui. <br>
ACM Transactions on Software Engineering and Methodology (TOSEM), 2025.

3. [Finding and Understanding Defects in Static Analyzers by Constructing Automated Oracles.](https://tingsu.github.io/files/fse24-sa-find-bugs.pdf)  <br>
**Weigang He**, Peng Di, Mengli Ming, Chengyu Zhang, Ting Su*, Shijie Li, Yulei Sui  <br>
ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE), 2024.

4. [Automata-based Trace Analysis for Aiding Diagnosing GUI Testing Tools for Android.](https://tingsu.github.io/files/fse23-DDroid.pdf)  <br>
Enze Ma, Shan Huang, **Weigang He**, Ting Su*, Jue Wang, Huiyu Liu, Geguang Pu, Zhendong Su  <br>
ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE), 2023.

5. [Data flow testing for PLC programs via dynamic symbolic execution.](https://ieeexplore.ieee.org/document/9712019)  <br>
**Weigang He**, Xia Mao, Ting Su, Yanhong Huang, and Jianqi Shi. <br>
28th Asia-Pacific Software Engineering Conference, APSEC 2021, Taipei, Taiwan, December 6-9, 2021, pages 152–160. IEEE, 2021.

6. [Automated test generation for iec 61131-3 st programs via dynamic symbolic execution.](https://www.sciencedirect.com/science/article/pii/S0167642321000010)<br>
   **Weigang He**, Jianqi Shi, Ting Su, Zeyu Lu, Li Hao, and Yanhong Huang. <br>
   Science of Computer Programming, 206:102608, 2021.

7. [Safety verification of iec 61131-3 structured text programs.](https://ieeexplore.ieee.org/document/9107345) <br>
   Jiawen Xiong, Xiangxing Bu, Yanhong Huang, Jianqi Shi, and **Weigang He**. <br>
   IEEE Transactions on Industrial Informatics, 17(4):2632–2640, 2020.

#### Workshop
1. QLM: CodeQL Query Synthesis with Compositional PoC Validation. <br>
**Weigang He**, Xiao Cheng, Shuangxiang Kan, Wei Li, Xingrui Yu, Ivor Tsang, Yulei Sui <br>
Journal Ahead Workshop (JAWs), co-located with ICSE 2026. *Presentation; an earlier version of the ICSE'27 paper.*


### Services
I serve as a reviewer for IEEE Transactions on Software Engineering (TSE), ACM Transactions on Embedded Computing Systems (TECS) and IEEE Transactions on Reliability (TR).

### Teaching Experience
Tutor, [41128 Software Analysis Studio](https://coursehandbook.uts.edu.au/subject/2026/41128), UTS, 2024-2025.
Tutor and lab demonstrator, [41184 Secure Programming and Penetration Testing](https://coursehandbook.uts.edu.au/subject/2025/41184?year=2025), UTS, 2025

<p align="right"> [Last updated on Oct 2026] </p>



