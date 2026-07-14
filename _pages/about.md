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
<span class="pub-badge pub-badge--a">CCF-A</span> Top Tier
<span class="pub-badge pub-badge--b">CCF-B</span> Second Tier
<span class="pub-badge pub-badge--c">CCF-C</span> Third Tier
<span class="pub-badge pub-badge--best">Award</span> Award
</div>

<p class="publication-summary">As first author or co-first author, I have published <strong>17 papers</strong>, including <strong>7 CCF-A papers</strong> and <strong>6 CCF-B papers</strong>.</p>

<div class="publication-list">
  <section class="pub-group">
    <h2>Agentic AI & Reasoning</h2>
    <article class="pub-item">
      <div class="pub-item__venue">arXiv 2026</div>
      <h3><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=_OnEpYMAAAAJ&citation_for_view=_OnEpYMAAAAJ:roLk4NBRz8UC">SkillSmith: Co-Evolving Skills and Tools for Self-Improving Agent Systems</a></h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span>First Author</span><span>Preprint</span><span>Self-Improving Agents</span><span>Skill-Tool Co-Evolution</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ICML 2026</div>
      <h3>Topological Active Inference for Task Disambiguation</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Active Inference</span><span>Task Disambiguation</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ICML 2026</div>
      <h3>EvoMAS: Heuristics in the Loop--Evolving Smarter Agentic Workflows</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Agent Workflows</span><span>Heuristic Evolution</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ACL 2025</div>
      <h3>MECoT: Markov Emotional Chain-of-Thought for Personality-Consistent Role-Playing</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Role-Playing</span><span>Emotional CoT</span></div>
    </article>
  </section>

  <section class="pub-group">
    <h2>LLM Systems & Architecture</h2>
    <article class="pub-item">
      <div class="pub-item__venue">ICCAD 2026</div>
      <h3>Cluster-of-Thought: Semantic-Structured KV-Cache Management for Long-Context Reasoning Models</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--b">CCF-B</span><span>First Author</span><span>KV Cache</span><span>Long-Context Reasoning</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">AAAI 2026</div>
      <h3>Mixture-of-Trees: Learning to Select and Weigh Reasoning Paths for Efficient LLM Inference</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Reasoning Paths</span><span>Efficient Inference</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ASPLOS 2026</div>
      <h3>DFVG: A Heterogeneous Architecture for Speculative Decoding with Draft-on-FPGA and Verify-on-GPU</h3>
      <p><strong>Yangbo Wei</strong> (Co-first), et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Co-first</span><span>Speculative Decoding</span><span>FPGA-GPU</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ISCAS 2026</div>
      <h3><a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=_OnEpYMAAAAJ&citation_for_view=_OnEpYMAAAAJ:UebtZRa9Y70C">Harnessing Spatiotemporal Redundancy for Fast Diffusion Models on FPGA</a></h3>
      <p>Authors, ..., <strong>Yangbo Wei</strong> (4th Author).</p>
      <div class="pub-item__tags"><span>4th Author</span><span>Diffusion Models</span><span>FPGA Acceleration</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ASPDAC 2026</div>
      <h3>dLLM-OPU: An FPGA Overlay Processor for Accelerated Diffusion Large Language Models</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--c">CCF-C</span><span>Diffusion LLM</span><span>Overlay Processor</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ICCAD 2025</div>
      <h3>MoE-OPU: An FPGA Overlay Processor Leveraging Expert Parallelism for MoE-Based LLM</h3>
      <p><strong>Yangbo Wei</strong> (Co-first), et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--b">CCF-B</span><span>Co-first</span><span>MoE</span><span>Expert Parallelism</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">FPT 2025</div>
      <h3>FlightOPU: An FPGA Overlay Processor for LLM with HBM-Aware Multi-Die Architecture</h3>
      <p>Authors, ..., <strong>Yangbo Wei</strong> (3rd Author).</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--c">CCF-C</span><span>Invited</span><span>HBM</span><span>Multi-Die</span></div>
    </article>
  </section>

  <section class="pub-group">
    <h2>AI for EDA</h2>
    <article class="pub-item">
      <div class="pub-item__venue">ICCAD 2026</div>
      <h3>PCBclaw: Hierarchical Multi-Agent Schematic Synthesis and Verification for MCU System Boards</h3>
      <p><strong>Yangbo Wei</strong> (Co-first), et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--b">CCF-B</span><span>Co-first</span><span>Multi-Agent EDA</span><span>Schematic Verification</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">DAC 2026</div>
      <h3>PCBgen: Self-Evolving LLM Agent for Verifiable Specification-to-Schematic PCB Design</h3>
      <p><strong>Yangbo Wei</strong> (Co-first), et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Co-first</span><span>PCB Design</span><span>Self-Evolving Agent</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">DAC 2026</div>
      <h3>From Fluid Dynamics to Chip Design: Foundation Neural Operators Address Data Bottleneck in 3D-ICs Thermal Simulation</h3>
      <p><strong>Yangbo Wei</strong> (Co-first), et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Co-first</span><span>3D-IC Thermal</span><span>Neural Operators</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ASPDAC 2026</div>
      <h3>Vflow: Discovering Optimal Agentic Workflows for Verilog Generation</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--c">CCF-C</span><span>Verilog Generation</span><span>Workflow Search</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">TODAES</div>
      <h3>ModelGen: Automating Semiconductor Parameter Extraction with Large Language Model Agents</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--b">CCF-B</span><span>Journal</span><span>Parameter Extraction</span><span>LLM Agents</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ISEDA 2024</div>
      <h3>Knowledge Transfer for GaN HEMTs Parameter Extraction Based on Hybrid Model</h3>
      <p><strong>Yangbo Wei</strong>, et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--best">Best Paper</span><span>GaN HEMTs</span><span>Knowledge Transfer</span></div>
    </article>
  </section>

  <section class="pub-group">
    <h2>AI for Science & Healthcare</h2>
    <article class="pub-item">
      <div class="pub-item__venue">AAAI Oral 2026</div>
      <h3>MedAtlas: Evaluating LLMs for Multi-Round, Multi-Task Medical Reasoning Across Diverse Imaging Modalities and Clinical Text</h3>
      <p>Authors, ..., <strong>Yangbo Wei</strong> (3rd Author).</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--a">CCF-A</span><span>Oral</span><span>Medical Reasoning</span><span>Multimodal Evaluation</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">ICASSP 2026</div>
      <h3>MambaDATG: Domain-Adaptive Tri-Plane-Gated Pre-Training for 3D Abdominal Segmentation</h3>
      <p><strong>Yangbo Wei</strong> (Co-first), et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--b">CCF-B</span><span>Co-first</span><span>3D Segmentation</span><span>Domain Adaptation</span></div>
    </article>
    <article class="pub-item">
      <div class="pub-item__venue">BIBM 2025</div>
      <h3>H3DE-Net: Efficient and Accurate 3D Landmark Detection in Medical Imaging</h3>
      <p><strong>Yangbo Wei</strong> (Co-first), et al.</p>
      <div class="pub-item__tags"><span class="pub-badge pub-badge--b">CCF-B</span><span>Co-first</span><span>Landmark Detection</span><span>Medical Imaging</span></div>
    </article>
  </section>
</div>


# 🎖 Honors and Awards
**Academic Awards**
- *2026* **Travel Grant Award**, ICML 2026 (International Conference on Machine Learning)
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
