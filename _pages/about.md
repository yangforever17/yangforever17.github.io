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

<section class="profile-hero">
  <img class="profile-hero__pet" src="/images/kkk.png" alt="" aria-hidden="true">
  <div class="profile-hero__eyebrow">LLM Agents · Computer Architecture · AI for EDA</div>
  <h1 class="profile-hero__name">Yangbo Wei <span>韦杨波</span></h1>
  <p class="profile-hero__summary">I am a second-year Ph.D. student in the School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University (SJTU), and the School of Computer Science, Eastern Institute of Technology, supervised by <a href="https://scholar.google.com/citations?hl=zh-CN&user=n_N-PJkAAAAJ&view_op=list_works">Prof. Lei He (IEEE Fellow)</a>. Prior to my journey in SJTU, I obtained my B.Sc. degree from Southeast University (SEU) in 2024.</p>
  <p class="profile-hero__focus">My research explores agentic and efficient AI systems across reasoning, hardware acceleration, LLM serving, and electronic design automation.</p>
</section>

<section class="research-grid" aria-label="Research interests">
  <div class="research-card">
    <span>01</span>
    <strong>AI Agents & Reasoning</strong>
    <p>Agentic reasoning, Multi-Agent Systems (MAS), Efficient LLMs.</p>
  </div>
  <div class="research-card">
    <span>02</span>
    <strong>AI Hardware Acceleration</strong>
    <p>Energy-efficient AI inference, ASIC & FPGA design for AI, Memory- and Kernel-level optimization.</p>
  </div>
  <div class="research-card">
    <span>03</span>
    <strong>LLM System Optimization</strong>
    <p>Efficient LLM serving, Parallelism & memory optimization, Kernel-level execution, Runtime scheduling.</p>
  </div>
  <div class="research-card">
    <span>04</span>
    <strong>AI for EDA</strong>
    <p>LLM-based agents for electronic design automation (EDA).</p>
  </div>
</section>

# 🔥 News
<div class="news-timeline" markdown="1">
- *2026.04*: &nbsp;🎉🎉 Two papers were accepted by **ICML 2026**.
- *2025.11*: &nbsp;🚀🚀 Two papers were accepted by **ASPLOS 2026 (10.6%)** and **AAAI 2026 (17.6%)**.
- *2024.05*: &nbsp;🏆🏆 Our paper received the **Best Paper Award** at ISEDA 2024!
</div>


# 📝 Publications 

<div class="publication-legend">
<span class="pub-badge pub-badge--a">CCF-A</span> Top Tier &nbsp;
<span class="pub-badge pub-badge--b">CCF-B</span> Second Tier &nbsp;
<span class="pub-badge pub-badge--c">CCF-C</span> Third Tier
</div>

<div class="publication-list" markdown="1">

**Conference Publications**
- [C14] <span class="pub-badge pub-badge--a">CCF-A</span> **Topological Active Inference for Task Disambiguation** <br> **Yangbo Wei**, et al. <br> *International Conference on Machine Learning (ICML)*, 2026.
- [C13] <span class="pub-badge pub-badge--a">CCF-A</span> **EvoMAS: Heuristics in the Loop--Evolving Smarter Agentic Workflows** <br> **Yangbo Wei**, et al. <br> *International Conference on Machine Learning (ICML)*, 2026.
- [C12] <span class="pub-badge pub-badge--a">CCF-A</span> **PCBgen: Self-Evolving LLM Agent for Verifiable Specification-to-Schematic PCB Design** <br> **Yangbo Wei** (Co-first), et al. <br> *Design Automation Conference (DAC)*, 2026.
- [C11] <span class="pub-badge pub-badge--a">CCF-A</span> **From Fluid Dynamics to Chip Design: Foundation Neural Operators Address Data Bottleneck in 3D-ICs Thermal Simulation** <br> **Yangbo Wei** (Co-first), et al. <br> *Design Automation Conference (DAC)*, 2026.
- [C10] <span class="pub-badge pub-badge--a">CCF-A</span> **Mixture-of-Trees: Learning to Select and Weigh Reasoning Paths for Efficient LLM inference** <br> **Yangbo Wei**, et al. <br> *AAAI Conference on Artificial Intelligence (AAAI)*, 2026.
- [C9] <span class="pub-badge pub-badge--a">CCF-A</span> **DFVG: A Heterogeneous Architecture for Speculative Decoding with Draft-on-FPGA and Verify-on-GPU** <br> **Yangbo Wei** (Co-first), et al. <br> *Architectural Support for Programming Languages and Operating Systems (ASPLOS)*, 2026.
- [C8] <span class="pub-badge pub-badge--a">CCF-A</span> **MedAtlas: Evaluating LLMs for Multi-Round, Multi-Task Medical Reasoning Across Diverse Imaging Modalities and Clinical Text** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *AAAI Conference on Artificial Intelligence (AAAI oral)*, 2026.
- [C7] <span class="pub-badge pub-badge--a">CCF-A</span> **MECoT: Markov emotional chain-of-thought for personality-consistent role-playing** <br> **Yangbo Wei**, et al. <br> *Annual Meeting of the Association for Computational Linguistics (ACL findings)*, 2025.
- [C16] <span class="pub-badge pub-badge--b">CCF-B</span> **MambaDATG: Domain-Adaptive Tri-Plane-Gated Pre-training for 3D Abdominal Segmentation** <br> **Yangbo Wei*** (Co-first), et al. <br> *IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)*, 2026.
- [C15] <span class="pub-badge pub-badge--b">CCF-B</span> **H3DE-Net: Efficient and Accurate 3D Landmark Detection in Medical Imaging** <br> **Yangbo Wei*** (Co-first), et al. <br> *IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*, 2025.
- [C6] <span class="pub-badge pub-badge--b">CCF-B</span> **MoE-OPU: An FPGA Overlay Processor Leveraging Expert Parallelism for MoE-based LLM** <br> **Yangbo Wei*** (Co-first), et al. <br> *IEEE/ACM International Conference on Computer-Aided Design (ICCAD)*, 2025.
- [C5] <span class="pub-badge pub-badge--c">CCF-C</span> **dLLM-OPU: An FPGA Overlay Processor for Accelerated Diffusion Large Language Models** <br> **Yangbo Wei**, et al. <br> *Asia and South Pacific Design Automation Conference (ASPDAC)*, 2026.
- [C4] <span class="pub-badge pub-badge--c">CCF-C</span> **Vflow: Discovering optimal agentic workflows for verilog generation** <br> **Yangbo Wei**, et al. <br> *Asia and South Pacific Design Automation Conference (ASPDAC)*, 2026.
- [C3] <span class="pub-badge pub-badge--c">CCF-C</span> **FlightOPU: An FPGA Overlay Processor for LLM with HBM-Aware Multi-Die Architecture** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *International Conference on Field-Programmable Technology (FPT invited)*, 2025.
- [C2] <span class="pub-badge pub-badge--c">CCF-C</span> **BOPRO: Towards New Style Bayesian Optimization with Large Language Models** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *International Conference on Intelligent Computing (ICIC)*, 2025.
- [C1] <span class="pub-badge pub-badge--best">Best Paper</span> **Knowledge Transfer for GaN HEMTs Parameter Extraction Based on Hybrid Model** <br> **Yangbo Wei**, et al. <br> *International Symposium on Electronic Design Automation (ISEDA)*, 2024. 🏆

**Journal Publications**
- [J1] <span class="pub-badge pub-badge--b">CCF-B</span> **ModelGen: Automating Semiconductor Parameter Extraction with Large Language Model Agents** <br> **Yangbo Wei**, et al. <br> *ACM Transactions on Design Automation of Electronic Systems (TODAES)*.
  
</div>


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
