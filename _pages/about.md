---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am Jiaming Xu (许珈铭), a third year Ph.D student supervised by [Prof. Guohao Dai (戴国浩)](https://dai.sjtu.edu.cn/pepledetail.html?id=218) in School of Computer Science, Shanghai Jiao Tong University ([上海交通大学计算机学院](https://www.cs.sjtu.edu.cn/)) and Shanghai Innovation Institute ([上海创智学院](https://www.sii.edu.cn/)). Previously, I obtained my Bachelor's degree in 2023 from School of Computer Science and Technology, Xidian University ([西安电子科技大学计算机科学与技术学院](https://cs.xidian.edu.cn/)) supervised by [Prof. Nannan Wang (王楠楠)](https://web.xidian.edu.cn/nnwang/). I was once an intern in Infinigence AI ([无问芯穹](https://cloud.infini-ai.com/platform/ai)) and now still collaborate closely with Xiuhong Li ([李秀红](https://www.zhihu.com/people/hong_pku)) in Infinigence AI.

My research focuses on efficient machine learning systems (MLSys), primarily the effcient AI (e.g., LLM, sparse computing, embodied AI, multimodal model) inference through algorithm (e.g., quantization, pruning, speculative decoding) and system (kernel design, memory management, dataflow design, heterogeneous computing) co-deisgn. I have published 10+ papers <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international conferences and journals such as IEEE TCAD, ISCA, MLSys, DAC.


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 We release [SpecDiff](https://www.arxiv.org/abs/2509.13848) and [SpecPrune-VLA](https://arxiv.org/abs/2509.05614) for diffusion and VLA model acceleration.
- *2025.09*: &nbsp;🎉🎉 Two papers were accepted by ASP-DAC 2026. Look forward to meeting you next January in Hong Kong!
- *2025.08*: &nbsp;🎤🎤 A invited talk (大模型推理软硬件协同优化) was given in Ordos, China. Thanks for the invitation of CCF-HPC 2025. 
- *2025.06*: &nbsp;🎤🎤 Oral presentation in ISCA 2025 in Tokyo, Japan.
- *2025.03*: &nbsp;🎉🎉 A paper were accpeted by ISCA 2025. Look forward to meeting you in June in Tokyo!


# 👥 Team
Now I lead the system team (DAI-Sys) in our lab. Our team currently consists of 9 students, including 4 Ph.D. students, 1 master student, and 4 undergraduates. I am very happpy to cooperate with them. <span style="color: red;">I am looking for students, who are excited to tackle efficiency problems in AI from an algorithm, modeling, system/hardare perspectives, to join us</span> ([DAI-Sys小组招生](https://dai.sjtu.edu.cn/join.html)).

**Now**
- Jiaming Xu (许珈铭): third year Ph.D student in Shanghai Jiao Tong University and Shanghai Innovation Institude
- Yaoxiu Lian (廉瑶秀): fourth year Ph.D student in Shanghai Jiao Tong University
- Yongkang Zhou (周永康): first year Ph.D student in Shanghai Jiao Tong University and Shanghai Innovation Institude
- Kele Shao (邵可乐): first year Ph.D student in Westlake University and Shanghai Innovation Institude
- Jiayi Pan (潘佳一): second year master student in Shanghai Jiao Tong University
- Tianlang Zhao (赵天朗): fourth year undergraduate in Shanghai Jiao Tong University
- Hanzhen Wang (王翰楨): third year undergraduate in Shanghai Jiao Tong University
- Haotian Fang (方皓天): second year undergraduate in Shanghai Jiao Tong University
- Qiming Cheng (程淇铭): second year undergraduate in East China Normal University

**Previous**
- Siming Chen (陈思铭, 2024.10~2025.6): fourth year undergraduate in Lanzhou University
- Junyi Wu (吴俊逸, 2024.1~2025.3): third year undergraduate in Shanghai Jiao Tong University



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCA 2025</div><img src='images/ISCA25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpecEE: Accelerating Large Language Model Inference with Speculative Early Exiting](https://dai.sjtu.edu.cn/my_file/pdf/7e067065-0e58-4e87-a373-feea0bebde1b.pdf)

**Jiaming Xu**, Jiayi Pan, Yongkang Zhou, Siming Chen, Jinhao Li, Yaoxiu Lian, Junyi Wu, Guohao Dai

ISCA 2025 (CCF-A)

[**Paper**](https://dai.sjtu.edu.cn/my_file/pdf/7e067065-0e58-4e87-a373-feea0bebde1b.pdf) &nbsp; | &nbsp; [**Code**](https://github.com/infinigence/SpecEE) ![](https://img.shields.io/github/stars/infinigence/SpecEE) &nbsp; | &nbsp;  [**机器之心**](https://mp.weixin.qq.com/s/vecJX1J8sFoRK8ZudFfzaA) <strong><span class='show_paper_citations' data='ovQFaicAAAAJ:WF5omc3nYNoC'></span></strong> 
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TCAD 2025</div><img src='images/TCAD25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enabling Efficient Sparse Multiplications on GPUs with Heuristic Adaptability](https://ieeexplore.ieee.org/document/10802949)

**Jiaming Xu\***, Shan Huang\*, Jinhao Li, Guyue Huang, Yuan Xie, Yu Wang, Guohao Dai

IEEE TCAD 2025 (CCF-A)

[**Paper**](https://ieeexplore.ieee.org/document/10802949) &nbsp; | &nbsp; [**Project**](https://dgsparse.github.io/) &nbsp; | &nbsp; [**Code**](https://github.com/dgSPARSE) ![](https://img.shields.io/github/stars/dgSPARSE/dgSPARSE-Lib) <strong><span class='show_paper_citations' data='ovQFaicAAAAJ:Tyk-4Ss8FVUC'></span></strong> 
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSys 2024</div><img src='images/MLSys24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FlashDecoding++: Faster Large Language Model Inference with Asynchronization, Flat GEMM Optimization, and Heuristics](https://proceedings.mlsys.org/paper_files/paper/2024/file/5321b1dabcd2be188d796c21b733e8c7-Paper-Conference.pdf)

Ke Hong\*, Guohao Dai\*, **Jiaming Xu\***, Qiuli Mao, Xiuhong Li, Jun Liu, Kangdi Chen, Yuhan Dong and Yu Wang,

MLSys 2024 (non-CCF)

[**Paper**](https://proceedings.mlsys.org/paper_files/paper/2024/file/5321b1dabcd2be188d796c21b733e8c7-Paper-Conference.pdf) &nbsp; | &nbsp; [**Arxiv**](https://arxiv.org/abs/2311.01282) &nbsp; | &nbsp; [**机器之心**](https://mp.weixin.qq.com/s/e9OHATqk88Q9zM3Y5czFQA)  <strong><span class='show_paper_citations' data='ovQFaicAAAAJ:qjMakFHDy7sC'></span></strong> 
</div>
</div>





<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2023.06* Outstanding Graduates, Shaanxi.
- *2023.06* Outstanding Graduates, Xidian University.
- *2023.06* Graduate Star (1/10), Xidian University.
- *2022.12* Thanks for the Modern Scientist Scholarship (感恩近现代科学家奖学金) (1/12), Xidian University.
- *2022.12* Principal’s Scholarship (校长奖学金) (1/5), Xidian University.
- *2022.12* <span style="color: red;">National Scholarship<\span> (Top 1%), Ministry of Education of The People’s Republic of China.
- *2022.10* Top 1.3% of World, IEEEXtreme Programming Competition.
- *2022.10* Huawei Intelligent Base Scholarship (华为智能基座奖学金) (1/10), Xidian University.
- *2021.12* <span style="color: red;">National Scholarship<\span> (Top 1%), Ministry of Education of The People’s Republic of China.
- *2021.11* Silver Medal, The ICPC International Collegiate Programming Contest of Shaanxi Province.
- *2021.10* Huawei Intelligent Base Scholarship (华为智能基座奖学金) (1/10), Xidian University.
- *2020.12* <span style="color: red;">National Scholarship<\span> (Top 1%), Ministry of Education of The People’s Republic of China.
- *2020.11* Bronze Medal, The ICPC International Collegiate Programming Contest of Shaanxi Province.


# 📖 Educations
- *2023.06 - 2028.06 (expected)*, School of Computer Science, Shanghai Jiao Tong University 
- *2019.09 - 2023.06*, School of Computer Science and Technology, Xidian University

# 💬 Presentation
- *2025.08*, \[Invited Talk\] Efficient LLM inference via hardware-software codesign, CCF-HPC 2025 @Ordos, China
- *2025.06*, \[Oral Presentation\] Accelerating Large Language Model Inference with Speculative Early Exiting, ISCA 2025 @Tokyo, Japan
- *2024.12*, \[Oral Presentation\] Efficient LLM Inference on GPUs with Operator Optimization and Compilation, Chinasys 2024 @Tianjin, China
- *2024.11*, \[Oral Presentation\] MARCA: Mamba Accelerator with Reconfigurable Architecture, ICCAD 2024 @New York, USA
- *2024.11*, \[Oral Presentation\] Fast and Efficient 2-bit LLM Inference on GPU: 2/4/16-bit in a Weight Matrix with Asynchronous Dequantization, ICCAD 2024 @New York, USA
- *2024.11*, \[Oral Presentation\] Towards Floating Point-Based Attention-Free LLM: Hybrid PIM with Non-Uniform Data Format and Reduced Multiolications, ICCAD 2024 @New York, USA
- *2024.09*, \[Invited Talk\] Efficient GPU computation in Large Language Models, CCF-HPC 2024 @Wuhan, China
- *2024.05*, \[Oral Presentation\] FlashDecoding++: Faster Large Language Model Inference with Asynchronization, Flat GEMM Optimization, and Heuristics, MLSys 2024 @California, USA
- *2024.03*, \[Invited Talk\] NVIDIA GPU and LLM Exploration, Flat GEMM Optimization, SJTU @Shanghai, USA

# 💻 Service
- *2025.09 - Now*, Teaching Assistant, Thinking and Methodology in Programming (C++) (UG-CS1501-08) by [Prof. Weiguo Gu](https://me.sjtu.edu.cn/teacher_directory1/guweiguo.html)
- *2025.02 - 2025.06*, Teaching Assistant, Algorithms and Complexity (UG-CS2308-01) by [Prof. Qingshen Ren](https://www.cs.sjtu.edu.cn/PeopleDetail.aspx?id=85)
- *2025.02 - 2025.06*, Teaching Assistant, Algorithm Design and Analysis (PG-CS7310H-033-M01) by [Prof. Guohao Dai](https://dai.sjtu.edu.cn/pepledetail.html?id=218)
- *2024.09 - 2025.01*, Teaching Assistant, Thinking and Methodology in Programming (C++) (UG-CS1501-04) by [Prof. Weiguo Gu](https://me.sjtu.edu.cn/teacher_directory1/guweiguo.html)
- *2024.05 - Now*, IT Administrator of DAI-Lab, Shanghai Jiao Tong University
- *2025.02 - 2025.06*, Teaching Assistant, Algorithm Design and Analysis (PG-CS7310H-033-M01) by [Prof. Guohao Dai](https://dai.sjtu.edu.cn/pepledetail.html?id=218)
- *2022.09 - 2023.06*, Huawei Campus Ambassador, Xidian University
- *2021.09 - 2022.09*, Chairman of Huawei Innovation Club and Huawei Intelligent Base Club
