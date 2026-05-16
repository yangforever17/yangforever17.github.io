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

Yangbo Wei (韦杨波) is a second-year Ph.D. student in the School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University (SJTU), and the School of Computer Science, Eastern Institute of Technology, supervised by [Prof. Lei He (IEEE Fellow)](https://scholar.google.com/citations?hl=zh-CN&user=n_N-PJkAAAAJ&view_op=list_works).  
Prior to my journey in SJTU, I obtained my B.Sc. degree from Southeast University (SEU) in 2024.

**My research interests lie at the intersection of LLM Agents, Computer Architecture, and Electronic Design Automation (EDA).**

My current research focuses on the following areas:

- **AI Agents & Reasoning**: Agentic reasoning, Multi-Agent Systems (MAS), Efficient LLMs.  
- **AI Hardware Acceleration**: Energy-efficient AI inference, ASIC & FPGA design for AI, Memory- and Kernel-level optimization.  
- **LLM System Optimization**: Efficient LLM serving, Parallelism & memory optimization, Kernel-level execution, Runtime scheduling.  
- **AI for EDA**: LLM-based agents for electronic design automation (EDA).

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 Two papers were accepted by **ICML 2026**.
- *2025.11*: &nbsp;🚀🚀 Two papers were accepted by **ASPLOS 2026 (10.6%)** and **AAAI 2026 (17.6%)**.
- *2024.05*: &nbsp;🏆🏆 Our paper received the **Best Paper Award** at ISEDA 2024!


# 📝 Publications 

<div style="font-size: 0.9em; margin-bottom: 20px;">
<span style="background-color: #d9534f; color: white; padding: 2px 5px; border-radius: 3px;">CCF-A</span> Top Tier &nbsp;
<span style="background-color: #f0ad4e; color: white; padding: 2px 5px; border-radius: 3px;">CCF-B</span> Second Tier &nbsp;
<span style="background-color: #5bc0de; color: white; padding: 2px 5px; border-radius: 3px;">CCF-C</span> Third Tier
</div>

**Conference Publications**
- [C14] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **Topological Active Inference for Task Disambiguation** <br> **Yangbo Wei**, et al. <br> *International Conference on Machine Learning (ICML)*, 2026.
- [C13] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **EvoMAS: Heuristics in the Loop--Evolving Smarter Agentic Workflows** <br> **Yangbo Wei**, et al. <br> *International Conference on Machine Learning (ICML)*, 2026.
- [C12] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **PCBgen: Self-Evolving LLM Agent for Verifiable Specification-to-Schematic PCB Design** <br> **Yangbo Wei** (Co-first), et al. <br> *Design Automation Conference (DAC)*, 2026.
- [C11] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **From Fluid Dynamics to Chip Design: Foundation Neural Operators Address Data Bottleneck in 3D-ICs Thermal Simulation** <br> **Yangbo Wei** (Co-first), et al. <br> *Design Automation Conference (DAC)*, 2026.
- [C10] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **Mixture-of-Trees: Learning to Select and Weigh Reasoning Paths for Efficient LLM inference** <br> **Yangbo Wei**, et al. <br> *AAAI Conference on Artificial Intelligence (AAAI)*, 2026.
- [C9] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **DFVG: A Heterogeneous Architecture for Speculative Decoding with Draft-on-FPGA and Verify-on-GPU** <br> **Yangbo Wei** (Co-first), et al. <br> *Architectural Support for Programming Languages and Operating Systems (ASPLOS)*, 2026.
- [C8] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **MedAtlas: Evaluating LLMs for Multi-Round, Multi-Task Medical Reasoning Across Diverse Imaging Modalities and Clinical Text** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *AAAI Conference on Artificial Intelligence (AAAI oral)*, 2026.
- [C7] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **MECoT: Markov emotional chain-of-thought for personality-consistent role-playing** <br> **Yangbo Wei**, et al. <br> *Annual Meeting of the Association for Computational Linguistics (ACL findings)*, 2025.
- [C16] <span style="background-color: #f0ad4e; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-B</span> **MambaDATG: Domain-Adaptive Tri-Plane-Gated Pre-training for 3D Abdominal Segmentation** <br> **Yangbo Wei*** (Co-first), et al. <br> *IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)*, 2026.
- [C15] <span style="background-color: #f0ad4e; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-B</span> **H3DE-Net: Efficient and Accurate 3D Landmark Detection in Medical Imaging** <br> **Yangbo Wei*** (Co-first), et al. <br> *IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*, 2025.
- [C6] <span style="background-color: #f0ad4e; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-B</span> **MoE-OPU: An FPGA Overlay Processor Leveraging Expert Parallelism for MoE-based LLM** <br> **Yangbo Wei*** (Co-first), et al. <br> *IEEE/ACM International Conference on Computer-Aided Design (ICCAD)*, 2025.
- [C5] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **dLLM-OPU: An FPGA Overlay Processor for Accelerated Diffusion Large Language Models** <br> **Yangbo Wei**, et al. <br> *Asia and South Pacific Design Automation Conference (ASPDAC)*, 2026.
- [C4] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **Vflow: Discovering optimal agentic workflows for verilog generation** <br> **Yangbo Wei**, et al. <br> *Asia and South Pacific Design Automation Conference (ASPDAC)*, 2026.
- [C3] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **FlightOPU: An FPGA Overlay Processor for LLM with HBM-Aware Multi-Die Architecture** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *International Conference on Field-Programmable Technology (FPT invited)*, 2025.
- [C2] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **BOPRO: Towards New Style Bayesian Optimization with Large Language Models** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *International Conference on Intelligent Computing (ICIC)*, 2025.
- [C1] <span style="background-color: #ffd700; color: #d35400; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold; border: 1px solid #d35400;">Best Paper</span> **Knowledge Transfer for GaN HEMTs Parameter Extraction Based on Hybrid Model** <br> **Yangbo Wei**, et al. <br> *International Symposium on Electronic Design Automation (ISEDA)*, 2024. 🏆

**Journal Publications**
- [J1] <span style="background-color: #f0ad4e; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-B</span> **ModelGen: Automating Semiconductor Parameter Extraction with Large Language Model Agents** <br> **Yangbo Wei**, et al. <br> *ACM Transactions on Design Automation of Electronic Systems (TODAES)*.
  


# 🎖 Honors and Awards
**Academic Awards**
- *2026* **Silver Reviewer Award**, ICML 2026 (International Conference on Machine Learning)
- *2024.05* **Best Paper Award**, ISEDA 2024 (International Symposium on Electronic Design Automation)

**Competitions**
- *2023* First Prize (Meritorious Winner), Mathematical Contest in Modeling (MCM/ICM)
- *2023* Second Prize, China Undergraduate Mathematical Contest in Modeling (National Level)
- *2022* First Prize, Southeast University Electronic Design Competition

# 💼 Experience
**Academic Service**
- *2026* Reviewer, ICML 2026 (International Conference on Machine Learning)
- *2026* Reviewer, NeurIPS 2026 (Conference on Neural Information Processing Systems)

# 📖 Education
- *2024.09 - Present*, Ph.D. Student in Integrated Circuit Engineering, Shanghai Jiao Tong University (SJTU). 
- *2020.09 - 2024.06*, B.Sc. Southeast University (SEU). 



# 🏖️ Life & Misc

**“Don’t Panic. In a universe this big, a bug is nothing.”**
