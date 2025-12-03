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

Yangbo Wei  is a second-year Ph.D. student in the School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University (SJTU), supervised by [Prof. Lei He (IEEE Fellow)](https://www.sjtu.edu.cn/). 
Prior to my journey in SJTU, I obtained my B.Sc. degree in Physics from Southeast University (SEU) in 2024.

**My research interests lie at the intersection of Computer Architecture and Electronic Design Automation (EDA).**

My current research focuses on the following areas: 
- **AI Hardware Acceleration**: FPGA-based Overlay Processor Units (OPU) for LLMs, Speculative Decoding architectures.
- **LLM System Optimization**: Mixture-of-Experts (MoE) quantization, sparsity, and KV-cache management.
- **AI for EDA**: Automating semiconductor parameter extraction and Verilog generation using LLM Agents.

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Admitted to Shanghai Jiao Tong University as a Ph.D. student.
- *2024.05*: &nbsp;🏆🏆 Our paper *Knowledge Transfer for GaN HEMTs Parameter Extraction Based on Hybrid Model* received the **Best Paper Award** at ISEDA 2024!
- *2024.05*: &nbsp;🎉🎉 Graduated from Southeast University with a B.Sc. in Physics.

# 📝 Publications 

**Conference Publication**
- [C9] [Mixture-of-Trees: Learning to Select and Weigh Reasoning Paths for Efficient LLM inference](https://yangbowei.github.io), **Yangbo Wei**, et al., AAAI Conference on Artificial Intelligence (AAAI), 2026 **(CCF-A)**
- [C8] [DFVG: A Heterogeneous Architecture for Speculative Decoding with Draft-on-FPGA and Verify-on-GPU](https://yangbowei.github.io), **Yangbo Wei**, et al., ASPLOS, 2026 **(CCF-A)**
- [C7] [dLLM-OPU: An FPGA Overlay Processor for Accelerated Diffusion Large Language Models](https://yangbowei.github.io), **Yangbo Wei**, et al., Asia and South Pacific Design Automation Conference (ASPDAC), 2026 **(CCF-C)**
- [C6] [Vflow: Discovering optimal agentic workflows for verilog generation](https://yangbowei.github.io), **Yangbo Wei**, et al., Asia and South Pacific Design Automation Conference (ASPDAC), 2026 **(CCF-C)**
- [C5] [MECoT: Markov emotional chain-of-thought for personality-consistent role-playing](https://yangbowei.github.io), **Yangbo Wei**, et al., Annual Meeting of the Association for Computational Linguistics (ACL), 2025 **(CCF-A)**
- [C4] [MOE-OPU: An FPGA Overlay Processor Leveraging Expert Parallelism for MoE-based LLM](https://yangbowei.github.io), **Yangbo Wei***, et al. (Co-first), IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2025 **(CCF-B)**
- [C3] [FlightOPU: An FPGA Overlay Processor for LLM with HBM-Aware Multi-Die Architecture](https://yangbowei.github.io), **Yangbo Wei**, et al., International Conference on Field-Programmable Technology (FPT), 2025 **(CCF-C)**
- [C2] [BOPRO: Towards New Style Bayesian Optimization with Large Language Models](https://yangbowei.github.io), **Yangbo Wei**, et al., International Conference on Intelligent Computing (ICIC), 2025 **(CCF-C)**
- [C1] [Knowledge Transfer for GaN HEMTs Parameter Extraction Based on Hybrid Model](https://yangbowei.github.io), **Yangbo Wei**, et al., International Symposium on Electronic Design Automation (ISEDA), 2024 **(Best Paper Award)**


**Preprints / Under Review**
- [U3] [Pack-MoE: Training-Free Expert Packing for Resource-Constrained Edge Deployment](https://yangbowei.github.io), **Yangbo Wei**, et al., Under Review at Design Automation Conference (DAC), 2026
- [U2] [Cluster-of-Thought: Semantic-Structured KV-Cache Management for Long-Context Reasoning Models](https://yangbowei.github.io), **Yangbo Wei**, et al., Under Review at Design Automation Conference (DAC), 2026
- [U1] [EvoMAS: Heuristics in the Loop-Evolving Smarter Agentic Workflows](https://yangbowei.github.io), **Yangbo Wei**, et al., Under Review at ICLR, 2026

**Journal Publication**
- [J1] [ModelGen: Automating Semiconductor Parameter Extraction with Large Language Model Agents](https://yangbowei.github.io), **Yangbo Wei**, et al., ACM Transactions on Design Automation of Electronic Systems (TODAES) **(CCF-B)**

# 🎖 Honors and Awards
**Academic Awards**
- *2024.05* Best Paper Award, ISEDA 2024 (International Symposium on Electronic Design Automation)
- *2023* First Prize (Meritorious Winner), Mathematical Contest in Modeling (MCM/ICM)
- *2023* Second Prize, China Undergraduate Mathematical Contest in Modeling (National Level)

**Competitions**
- *2022* First Prize, Southeast University Programming Competition
- *2022* First Prize, Southeast University Electronic Design Competition

# 📖 Education
- *2024.09 - Present*, Ph.D. Student in Integrated Circuit Engineering, Shanghai Jiao Tong University (SJTU). 
- *2020.09 - 2024.06*, B.Sc. in Physics, Southeast University (SEU). 

# 💻 Projects
- **FPGA-based Overlay Processor Unit (OPU)**: Designed a scalable computing engine on Xilinx Alveo U200 to accelerate BERT, ViT, and LLaMA models. Implemented hardware-software co-design with PCIe data transfer.
- **Heterogeneous Speculative Decoding (DFVG)**: Proposed a Draft-on-FPGA, Verify-on-GPU architecture, achieving 3.26x throughput improvement for LLM inference.
- **Expert-Aware Quantization for MoE**: Implemented N:M sparsity and mixed-precision quantization for DeepSeek-V2-Lite, reducing parameter size by 2.76x.

# 💬 Skills
- **Languages**: Chinese (Native), English (CET-6, Reading/Writing Proficient)
- **Programming**: Python (PyTorch, Transformers), C/C++, Verilog
- **Tools**: Vivado, ModelSim, Vitis, LaTeX