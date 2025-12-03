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

Zhengyuan Shi (石正源, Stone) is a Ph.D. Candidate in Dept. of Computer Science and Engineering, The Chinese University of Hong Kong (CUHK), supervised by [Prof. Qiang Xu](https://cure-lab.github.io/). 
Prior to my journey in CUHK, I obtained the B.Eng. degree with presidential scholarship in Shandong University in 2021 and was supervised by [Prof. Gangqiang Yang](https://faculty.sdu.edu.cn/g37yang/en/index.htm). 
I gained valuable experience as an intern at Huawei, Hisilicon and Xilinx, and also worked as a visiting student at CityU and UBC. 

**I'm looking for job opportunities, will graduate in Dec. 2025.**


My research focuses on the following areas: 
- **AI for EDA**: Large Circuit Model, Logic Synthesis and Formal Verification. 
- **AI for Optimization Problem**: SAT/SMT, MaxSAT, ILP. 

I have published more than 20 papers at the top EDA conferences and journals, including DAC, ICCAD, DATE and ASPDAC. I also served as reviewer for DAC, ICCAD, TVLSI, Sci China Inf Sci and etc. 

<!-- **<font color=Red>I'm looking for job opportunity (Faculty and Post-doc) in academia, expected to graduate in Nov. 2025</font>** -->

# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Two papers were accepted by ASPDAC 2026 (I can't wait to the magical visit to HK Disneyland~). 
- *2025.08*: &nbsp;🎉🎉 Our SAT solver Kissat-CURE wins the 3rd prize in SAT Competition Main Track. 
- *2025.06*: &nbsp;🎉🎉 Two papers *DeepCell: Self-Supervised Multiview Fusion for Circuit Representation Learning* and *MMCircuitEval: A Comprehensive Multimodal Circuit-Focused Benchmark for Evaluating LLMs* were accepted by International Conference on Computer-Aided Design (ICCAD). 
- *2025.06*: &nbsp;👉👉 I was selected to attend CP/SAT Doctoral Program and present our work **Circuit Learning for Boolean Satisfiability Problems**. Thanks for the travel support from Association for Constraint Programming (ACP). 
- *2025.05*: &nbsp;🎉🎉 Our paper *DynamicSAT: Dynamic Configuration Tuning for SAT Solving* was accepted by International Conference on Principles and Practice of Constraint Programming (CP). The paper received excellent reviews, including two perfect scores (5/5/4 out of 5). 
- *2025.04* &nbsp;👉👉 My poster of my PhD topic **Large Circuit Model: Towards AI-Native EDA Methodology** was accpeted by Design Automation Conference (DAC) PhD Forum with 1,000$ travel grant support. 
- *2025.02*: &nbsp;🎉🎉 Our paper *Logic Optimization Meets SAT: A Novel Framework for Circuit-SAT Solving* was accepted by Design Automation Conference (DAC).
- *2025.01*: &nbsp;🎉🎉 Our paper *DeepSeq2: Enhanced Sequential Circuit Learning with Disentangled Representations* [Link](https://arxiv.org/abs/2411.00530) was nominated as **Best Paper** in Asia and South Pacific Design Automation Conference (ASPDAC). 
- *2024.11*: &nbsp;👉👉 Our paper about **Large Circuit Model**, an AI-native foundation model for EDA, was published in Science China Information Science [微信公众号](https://mp.weixin.qq.com/s/q-HwkFwaq44yzAZLwDQNCA)

# 📝 Publications 
*Publication Summary: DAC+ICCAD x7, DATE+ASPDAC x5*

**Conference Publication**
- [C21] [DeepCell: Multiview Representation Learning for Post-Mapping Netlists](https://arxiv.org/abs/2502.06816), **Zhengyuan Shi**, Chengyu Ma, Ziyang Zheng, et. al, International Conference on Computer-Aided Design (ICCAD), 2025
- [C20] [MMCircuitEval: A Comprehensive Multimodal Circuit-Focused Benchmark for Evaluating LLMs](https://arxiv.org/abs/2507.19525), Chenchen Zhao, **Zhengyuan Shi**, Xiangyu Wen, et. al, International Conference on Computer-Aided Design (ICCAD), 2025
- [C19] [DynamicSAT: Dynamic Configuration Tuning for SAT Solving](https://drops.dagstuhl.de/storage/00lipics/lipics-vol340-cp2025/LIPIcs.CP.2025.34/LIPIcs.CP.2025.34.pdf), **Zhengyuan Shi**, Wentao Jiang, Xindi Zhang, et. al, International Conference on Principles and Practice of Constraint Programming (CP), 2025
- [C18] [Logic Optimization Meets SAT: A Novel Framework for Circuit-SAT Solving](https://arxiv.org/abs/2403.19446), **Zhengyuan Shi**, Tiebing Tang, et al. Design Automation Conference (DAC), 2025
- [C17] [DeepCircuitX: A Comprehensive Repository-Level Dataset for RTL Code Understanding, Generation, and PPA Analysis](https://arxiv.org/abs/2502.18297), Zeju Liu, Changran Xu, **Zhengyuan Shi**, et al. International Conference on LLM-Aided Design (ICLAD), 2025
- [C16] [DeepRTL2: A Versatile Model for RTL-Related Tasks](https://arxiv.org/abs/2506.15697), Yi Liu, Hongji Zhang, Yunhao Zhou, **Zhengyuan Shi**, et al. Annual Meeting of the Association for Computational Linguistics (ACL), 2025
- [C15] [ForgeEDA: A Comprehensive Multimodal Dataset for Advancing EDA](https://arxiv.org/abs/2505.02016), **Zhengyuan Shi**, Zeju Li, Chengyu Ma, et al. International Symposium of EDA (ISEDA), 2025
- [C14] [WideGate: Beyond Directed Acyclic Graph Learning in Subcircuit Boundary Prediction](https://ieeexplore.ieee.org/document/10992972), Jiawei Liu, Zhiyan Liu, Xun He, Jiangwang Zhai, **Zhengyuan Shi**, et al. Design, Automation & Test in Europe (DATE), 2025
- [C13] [DeepSeq2: Temporal Correlations Aware Sequential Circuit Learning](https://arxiv.org/abs/2411.00530), Sadaf Khan, **Zhengyuan Shi**, Min Li and Qiang Xu, Asia and South Pacific Design Automation Conference (ASPDAC), 2025
- [C12] [DeepGate4: Efficient and Effective Representation Learning for Circuit Design at Scale](https://arxiv.org/html/2502.01681v1), Ziyang Zheng, Shan Huang, Jianyuan Zhong, **Zhengyuan Shi**, et. al, International Conference on Learning Representations (ICLR), 2025
- [C11] [DeepGate3: Towards Scalable Circuit Representation Learning](https://arxiv.org/pdf/2407.11095), **Zhengyuan Shi**, Ziyang Zheng, Jianyuan Zhong, et al. International Conference on Computer-Aided Design (ICCAD), 2024
- [C10] [DeepSeq: Deep Sequential Circuit Learning](https://arxiv.org/abs/2302.13608), Sadaf Khan, **Zhengyuan Shi**, et al. Design, Automation & Test in Europe (DATE), 2023
- [C9] [DeepGate2: Functionality-Aware Circuit Learning](https://ieeexplore.ieee.org/document/10323798/), **Zhengyuan Shi**, Hongyang Pan, et. al, International Conference on Computer-Aided Design (ICCAD), 2023
- [C8] [SATformer: Transformers for UNSAT Solving](https://ieeexplore.ieee.org/document/10323731), **Zhengyuan Shi**, Min Li, et. al, International Conference on Computer-Aided Design (ICCAD), 2023
- [C7] [On EDA-Driven Learning for SAT Solving](https://ieeexplore.ieee.org/document/10248001/), Min Li, **Zhengyuan Shi**, et. al, Design Automation Conference (DAC), 2023
- [C6] [Addressing Variable Dependency in GNN-based SAT Solving](https://arxiv.org/pdf/2304.08738), Zhiyuan Yan, Min Li, **Zhengyuan Shi**, et al. Computer Aided Verification (CAV), 2023
- [C5] [Design Space Exploration of Galois and Fibonacci Configuration based on Espresso Stream Cipher](https://dl.acm.org/doi/10.1145/3567428), **Zhengyuan Shi**, Cheng Chen, Gangqiang Yang, et al. International Conference on Field Programmable Technology (FPT), 2022
- [C4] [DeepTPI: Test Point Insertion with Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/9983950), **Zhengyuan Shi**, Min Li, et al. International Test Conference (ITC), 2022
- [C3] [DeepGate: Learning Neural Representations of Logic Gates](https://dl.acm.org/doi/10.1145/3489517.3530497), Min Li, Sadaf Khan, **Zhengyuan Shi**, et al. Design Automation Conference (DAC), 2022
- [C2] [Towards a Smaller than Grain Stream Cipher: Optimized FPGA Implementations of Fruit-80](https://ieeexplore.ieee.org/document/9933149), **Zhengyuan Shi**, Gangqiang Yang, et al. International Conference on Compilers, Architectures, and Synthesis for Embedded Systems (CASES), 2022
- [C1] [Testability-Aware Low Power Controller Design with Evolutionary Learning](https://ieeexplore.ieee.org/document/9611355/), Min Li, **Zhengyuan Shi**, et al. International Test Conference, 2021

**Journal Publication**
- [J4] [The Dawn of AI-Native EDA: Promises and Challenges of Large Circuit Models](https://arxiv.org/abs/2403.07257). Science China Information Science (SCIS), 2024. 
- [J3] [Customized FPGA Implementation of Authenticated Lightweight Cipher Fountain for IoT Systems](https://dl.acm.org/doi/10.1145/3643039), **Zhengyuan Shi**, Cheng Chen, Gangqiang Yang et al. ACM Transactions on Embedded Computing Systems (TECS), 2024
- [J2] [Hardware Optimizations of Fruit-80 Stream Cipher: Smaller than Grain](https://dl.acm.org/doi/10.1145/3569455), **Zhengyuan Shi**, Gangqiang Yang, et al. ACM Transactions on Reconfigurable Technology and Systems (TRETS), 2023
- [J1] [Design Space Exploration of Galois and Fibonacci Configuration based on Espresso Stream Cipher](https://dl.acm.org/doi/10.1145/3567428), **Zhengyuan Shi**, Cheng Chen, Gangqiang Yang, et al. ACM Transactions on Reconfigurable Technology and Systems (TRETS), 2023

# 🎖 Honors and Awards
**Acadamic Awards**
- *2025.01* Best Paper Awared Nominee, Asia and South Pacific Design Automation Conference (ASPDAC)
- *2022.06* Best Paper Awared Nominee, Design Automation Conference (DAC)
- *2021.04* Outstanding Undergraduate Thesis Award, Shandong University 

**Others**
- *2025.05* Association for Constraint Programming Scholarship
- *2023.09* International Conference on Computer-Aided Design (ICCAD) Student Scholar
- *2023.05* Design Automation Conference (DAC) Young Fellowship
- *2020.12* Presidential Scholarship, Shandong University 
- *2020.11* Outstanding Maker of Shandong Province (山东省优秀创客)
- *2020.09* Second Prize, National Undergraduate Electronics Design Contest (全国大学生电子设计竞赛)
- *2016.11* First Prize, National Olympiad in Informatics in Provinces (NOIP)

# 📖 Educations
- *2021.08 - Now (2025.11)*, Ph.D. Candidate, Department of Computer Science and Engineering, The Chinese University of Hong Kong. 
- *2017.09 - 2021.06*, B.Eng. in Information Engineering, School of Information Science and Engineering, Shandong University. 

# 💻 Internships
- *2024.05 - 2025.09*, National Technology and Innovation Center of EDA, Nanjing, China
- *2022.05 - 2024.05*, Noah's Lab, Huawei, Hong Kong S.A.R. 
- *2021.03 - 2021.06*, Hisilicon, China. 
- *2020.07 - 2020.11*, Central Hardware Engineering Department, Huawei, China. 
- *2019.12 - 2021.04*, Architecture Lab for Arithmetic and Security, CityU, supervised by [Prof. Ray C.C. Cheung](https://scholars.cityu.edu.hk/en/persons/chak-chung-ray-cheung(9874f0c3-ce32-4806-95b1-bb5ff42fe85d).html). 
- *2019.06 - 2019.09*, Xilinx, China.
- *2018.07 - 2018.08*, Visiting Student, Department of Electrical and Computer Engineering, University of British Columbia. 

# 🎙️ Invited Talks
- *2025.10*, Foundation Models and EDA Workshop, ICCAD. 
- *2025.01*, Young Scholars Forum of the School of Electronic and Computer Engineering, Peking University (PKU)
- *2025.01*, Outstanding Scholar Forum of Electronic and Electrical Engineering, Southern University of Science and Technology (SUSTech)
- *2024.10*, Qilu Youth Forum, Shandong University (SDU)
- *2024.06*, Large Circuit Model for Formal Verification, National Technology and Innovation Center of EDA
- *2024.05*, Tutorial: Boolean Satisfiability Solving State-of-the-Art, Internal Symposium of Electronics Design Automation (ISEDA)

# 💪 Services
- Chair, IEEE CUHK Student Branch
- Teaching Assistant, Embedded System Development and Applications (CENG4480) / Embedded System Design (CENG2400), CUHK
- Teaching Assistant, Applied Blockchain and Cryptocurrencies (FTEC5520), CUHK

# 😘😘😘 
My love 💗: Yiran Liu, Ph.D. candidate in the Faculty of Business Administration, University of Macau. 
<img src="./images/01.jpg" alt="photo" title="photo" width="50%" />