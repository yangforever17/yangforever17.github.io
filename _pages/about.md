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

Yangbo Wei is a first-year Ph.D. student in the School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University (SJTU), supervised by [Prof. Lei He (IEEE Fellow)](https://www.sjtu.edu.cn/). 
Prior to my journey in SJTU, I obtained my B.Sc. degree in Physics from Southeast University (SEU) in 2024.

**My research interests lie at the intersection of AI Agents, Computer Architecture, and Electronic Design Automation (EDA).**

My current research focuses on the following areas: 
- **AI Agents & Reasoning**: Emotional Chain-of-Thought (CoT), Multi-Agent System (MAS) optimization, and heuristic-driven agentic workflows.
- **AI Hardware Acceleration**: FPGA-based Overlay Processor Units (OPU) for LLMs, Speculative Decoding architectures.
- **LLM System Optimization**: Mixture-of-Experts (MoE) quantization, sparsity, and KV-cache management.
- **AI for EDA**: Automating semiconductor parameter extraction and Verilog generation using LLM Agents.

# 🔥 News
- *2025.11*: &nbsp;🚀🚀 **Double Strike!** Two papers were accepted by **ASPLOS 2026** and **AAAI 2026**! My research on *Speculative Decoding* and *Reasoning Paths* is getting recognized. 
- *2024.09*: &nbsp;🎉🎉 Admitted to Shanghai Jiao Tong University as a Ph.D. student.
- *2024.05*: &nbsp;🏆🏆 Our paper *Knowledge Transfer for GaN HEMTs Parameter Extraction Based on Hybrid Model* received the **Best Paper Award** at ISEDA 2024!
- *2024.05*: &nbsp;🎉🎉 Graduated from Southeast University with a B.Sc. in Physics.

# 📝 Publications 

<div style="font-size: 0.9em; margin-bottom: 20px;">
<span style="background-color: #d9534f; color: white; padding: 2px 5px; border-radius: 3px;">CCF-A</span> Top Tier &nbsp;
<span style="background-color: #f0ad4e; color: white; padding: 2px 5px; border-radius: 3px;">CCF-B</span> Second Tier &nbsp;
<span style="background-color: #5bc0de; color: white; padding: 2px 5px; border-radius: 3px;">CCF-C</span> Third Tier
</div>

**Conference Publications**
- [C9] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **Mixture-of-Trees: Learning to Select and Weigh Reasoning Paths for Efficient LLM inference** <br> **Yangbo Wei**, et al. <br> *AAAI Conference on Artificial Intelligence (AAAI)*, 2026.
- [C8] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **DFVG: A Heterogeneous Architecture for Speculative Decoding with Draft-on-FPGA and Verify-on-GPU** <br> **Yangbo Wei** (Co-first), et al. <br> *Architectural Support for Programming Languages and Operating Systems (ASPLOS)*, 2026.
- [C7] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **MECoT: Markov emotional chain-of-thought for personality-consistent role-playing** <br> **Yangbo Wei**, et al. <br> *Annual Meeting of the Association for Computational Linguistics (ACL)*, 2025.
- [C6] <span style="background-color: #f0ad4e; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-B</span> **MOE-OPU: An FPGA Overlay Processor Leveraging Expert Parallelism for MoE-based LLM** <br> **Yangbo Wei*** (Co-first), et al. <br> *IEEE/ACM International Conference on Computer-Aided Design (ICCAD)*, 2025.
- [C5] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **dLLM-OPU: An FPGA Overlay Processor for Accelerated Diffusion Large Language Models** <br> **Yangbo Wei**, et al. <br> *Asia and South Pacific Design Automation Conference (ASPDAC)*, 2026.
- [C4] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **Vflow: Discovering optimal agentic workflows for verilog generation** <br> **Yangbo Wei**, et al. <br> *Asia and South Pacific Design Automation Conference (ASPDAC)*, 2026.
- [C3] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **FlightOPU: An FPGA Overlay Processor for LLM with HBM-Aware Multi-Die Architecture** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *International Conference on Field-Programmable Technology (FPT)*, 2025.
- [C2] <span style="background-color: #5bc0de; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-C</span> **BOPRO: Towards New Style Bayesian Optimization with Large Language Models** <br> Authors, ..., **Yangbo Wei** (3rd Author). <br> *International Conference on Intelligent Computing (ICIC)*, 2025.
- [C1] <span style="background-color: #ffd700; color: #d35400; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold; border: 1px solid #d35400;">Best Paper</span> **Knowledge Transfer for GaN HEMTs Parameter Extraction Based on Hybrid Model** <br> **Yangbo Wei**, et al. <br> *International Symposium on Electronic Design Automation (ISEDA)*, 2024. 🏆

**Preprints / Under Review**
- [U3] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **Pack-MoE: Training-Free Expert Packing for Resource-Constrained Edge Deployment** <br> **Yangbo Wei**, et al. <br> *Under Review at Design Automation Conference (DAC)*, 2026.
- [U2] <span style="background-color: #d9534f; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-A</span> **Cluster-of-Thought: Semantic-Structured KV-Cache Management for Long-Context Reasoning Models** <br> **Yangbo Wei**, et al. <br> *Under Review at Design Automation Conference (DAC)*, 2026.
- [U1] <span style="background-color: #999; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">Preprint</span> **EvoMAS: Heuristics in the Loop-Evolving Smarter Agentic Workflows** <br> **Yangbo Wei**, et al. <br> *Under Review at ICLR*, 2026.

**Journal Publications**
- [J1] <span style="background-color: #f0ad4e; color: white; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; font-weight: bold;">CCF-B</span> **ModelGen: Automating Semiconductor Parameter Extraction with Large Language Model Agents** <br> **Yangbo Wei**, et al. <br> *ACM Transactions on Design Automation of Electronic Systems (TODAES)*.

# 🎖 Honors and Awards
**Academic Awards**
- *2024.05* **Best Paper Award**, ISEDA 2024 (International Symposium on Electronic Design Automation)
- *2023* First Prize (Meritorious Winner), Mathematical Contest in Modeling (MCM/ICM)
- *2023* Second Prize, China Undergraduate Mathematical Contest in Modeling (National Level)

**Competitions**
- *2022* First Prize, Southeast University Programming Competition
- *2022* First Prize, Southeast University Electronic Design Competition

# 📖 Education
- *2024.09 - Present*, Ph.D. Student in Integrated Circuit Engineering, Shanghai Jiao Tong University (SJTU). 
- *2020.09 - 2024.06*, B.Sc. in Physics, Southeast University (SEU). 

# 💻 Projects
- **AI Agents & Reasoning (MECoT & EvoMAS)**: Developed "Markov Emotional Chain-of-Thought" (MECoT) to enhance personality-consistent role-playing in LLMs. Proposed EvoMAS to optimize Multi-Agent Systems (MAS) workflows using heuristic evolution loops for smarter agentic collaboration.
- **FPGA-based Overlay Processor Unit (OPU)**: Designed a scalable computing engine on Xilinx Alveo U200 to accelerate BERT, ViT, and LLaMA models. Implemented hardware-software co-design with PCIe data transfer.
- **Heterogeneous Speculative Decoding (DFVG)**: Proposed a Draft-on-FPGA, Verify-on-GPU architecture, achieving 3.26x throughput improvement for LLM inference.
- **Expert-Aware Quantization for MoE**: Implemented N:M sparsity and mixed-precision quantization for DeepSeek-V2-Lite, reducing parameter size by 2.76x.


# 🏖️ Life & Misc

**“Don’t Panic. In a universe this big, a bug is nothing.”**

