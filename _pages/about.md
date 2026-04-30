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

I am a final-year Ph.D. student in Machine Learning at the Georgia Institute of Technology, advised by [Prof. Faramarz Fekri](https://fekri.ece.gatech.edu/).

My research focuses on improving long-horizon reasoning and decision-making in large language models. I study post-training and system design for LLM agents, with a focus on deliberate reasoning and planning, as well as scalable agent systems that support adaptive retrieval and long-context interaction.


# 🚀 Featured Projects

### Long-Horizon LLM Agents

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 @ SPOT</div><img src='images/DeepControl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scaling Search-Augmented Reasoning Agents via Adaptive Information Control](https://openreview.net/pdf?id=nGEWOtne5c) \\
**Siheng Xiong**, Oguzhan Gungordu, Blair Johnson, James C. Kerce, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/DeepControl)

DeepControl is a post-training framework for search-augmented LLM agents that adaptively controls retrieval and expansion based on the agent’s reasoning state, improving long-horizon reasoning performance across diverse benchmarks.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Project 2025</div><img src='images/DeepVerify.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Evidence-Based Expert-Level Scientific Claim Verification](https://github.com/xiongsiheng/DeepVerify) \\
**Siheng Xiong**, Oguzhan Gungordu, Blair Johnson, Mika Okamoto, James C. Kerce, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/DeepVerify)

DeepVerify is an agentic framework for expert-level scientific claim verification, combining search, tool use, and structured reasoning to ground decisions in retrieved evidence.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/MLR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Language Model Reasoning with Structured Multi-Level Modeling](https://openreview.net/pdf?id=PlkzZhqBCd) \\
**Siheng Xiong**, Ali Payani, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/MLR)

MLR is a lightweight planner-executor framework for long-horizon reasoning, combining multi-level decomposition with scalable step-level supervision to improve both accuracy and training stability.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/SWAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deliberate Reasoning in Language Models as Structure-Aware Planning with an Accurate World Model](https://aclanthology.org/2025.acl-long.1540.pdf) \\
**Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/SWAP)

SWAP frames multi-step reasoning as structure-aware planning, where a world model predicts structured future states to guide action selection.

</div>
</div>




### Long-Context and Memory Systems

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/DHSA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Long-Context Modeling with Dynamic Hierarchical Sparse Attention for Memory-Constrained LLM Inference](https://drive.google.com/file/d/1ubDI2GM3cUjeuqARLmbZsdd5uoSbss2E/view?usp=sharing) \\
**Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho


[**Project**](https://github.com/xiongsiheng/DHSA)

DHSA is an efficient sparse attention framework for long-context LLM inference that reduces prefill cost and memory usage while preserving accuracy under tight device constraints.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LM-OS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/pdf/2409.01495) \\
Yuan Yang, **Siheng Xiong**, Ehsan Shareghi, Faramarz Fekri

[**Project**](https://github.com/gblackout/LM-OS)

Compressor-Retriever is a model-agnostic architecture for lifelong context management in LLM-based systems, using the base model’s forward pass to compress and retrieve memory while remaining fully differentiable.

</div>
</div>




# 📝 Selected Publications

## 📝 Conference Papers
- ``ICML 2026`` <span style="color:red">(Spotlight)</span> [Long-Context Modeling with Dynamic Hierarchical Sparse Attention for Memory-Constrained LLM Inference](https://drive.google.com/file/d/1ubDI2GM3cUjeuqARLmbZsdd5uoSbss2E/view?usp=sharing) **Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho [[Repo]](https://github.com/xiongsiheng/DHSA)
- ``ICML 2026`` [Planning through World Model for Automated Heuristic Design via Self-Evolving LLMs](https://arxiv.org/pdf/2601.20539) Oguzhan Gungordu, **Siheng Xiong**, Faramarz Fekri [[Repo]]()
- ``ICLR 2026`` [Enhancing Language Model Reasoning with Structured Multi-Level Modeling](https://openreview.net/pdf?id=PlkzZhqBCd) **Siheng Xiong**, Ali Payani, Faramarz Fekri  [[Repo]](https://github.com/xiongsiheng/MLR)
- ``ACS 2025`` [Deliberate Planning in Language Models with Symbolic Representation](https://openreview.net/pdf?id=uJHpaZlIvT) **Siheng Xiong**, Zhangding Liu, Jieyu Zhou, Yusen Su [[Repo]](https://github.com/xiongsiheng/SymPlanner)
- ``ACL 2025 (main)`` [Deliberate Reasoning in Language Models as Structure-Aware Planning with an Accurate World Model](https://aclanthology.org/2025.acl-long.1540.pdf) **Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/SWAP)
- ``NAACL 2025 (main)`` [CausalEval: Towards Better Causal Reasoning in Language Models](https://aclanthology.org/2025.naacl-long.622.pdf) Longxuan Yu\*, Delin Chen\*, **Siheng Xiong\***, Qingyang Wu, Dawei Li, Zhikai Chen, Xiaoze Liu, Liangming Pan [[Repo]](https://github.com/chendl02/Awesome-LLM-Causal-Reasoning)
- ``EMNLP 2024`` [Can LLMs Reason in the Wild with Programs?](https://aclanthology.org/2024.findings-emnlp.573.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/Reason-in-the-Wild)
- ``IJCAI 2024`` [Temporal Inductive Logic Reasoning over Hypergraphs](https://www.ijcai.org/proceedings/2024/0400.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/gblackout/TILR)
- ``ACL 2024 (main)`` [Large Language Models Can Learn Temporal Reasoning](https://aclanthology.org/2024.acl-long.563.pdf) **Siheng Xiong**, Ali Payani, Ramana Kompella, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TG-LLM)
- ``ACL 2024 (main)`` [Harnessing the power of large language models for natural language to first-order logic translation](https://aclanthology.org/2024.acl-long.375.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LogicLLaMA)
- ``AAAI 2024`` <span style="color:red">(Oral)</span> [TEILP: Time prediction over knowledge graphs via logical reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/29544) **Siheng Xiong**, Yuan Yang, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TEILP)
- ``ICLR 2023`` [TILP: Differentiable learning of temporal logical rules on knowledge graphs](https://openreview.net/pdf?id=_X12NmQKvX) **Siheng Xiong**, Yuan Yang, Faramarz Fekri, James Clayton Kerce [[Repo]](https://github.com/xiongsiheng/TILP)

## 📝 Workshop Papers
- ``ICLR 2026 @ SPOT`` [Scaling Search-Augmented Reasoning Agents via Adaptive Information Control](https://openreview.net/pdf?id=nGEWOtne5c) **Siheng Xiong**, Oguzhan Gungordu, Blair Johnson, James C. Kerce, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/DeepControl)
- ``NeurIPS 2025 @ ER`` [Long-Context Modeling with Dynamic Hierarchical Sparse Attention for On-Device LLMs](https://openreview.net/pdf?id=pvrHkHRVx3) **Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho [[Repo]](https://github.com/xiongsiheng/DHSA)

## 📝 Preprints
- ``Preprint 2026`` [Adaptive Information Control for Search-Augmented LLM Reasoning](https://arxiv.org/pdf/2602.01672) **Siheng Xiong**, Oguzhan Gungordu, Blair Johnson, James C. Kerce, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/DeepControl)
- ``Preprint 2025`` [Enhancing Long Chain-of-Thought Reasoning with Multi-Path Planning with Aggregation](https://arxiv.org/pdf/2510.11620) **Siheng Xiong**, Ali Payani, Faramarz Fekri  [[Repo]](https://github.com/xiongsiheng/MPPA)
- ``Preprint 2024`` [The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/pdf/2409.01495) Yuan Yang, **Siheng Xiong**, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LM-OS)



# 🎖 Honors and Awards
- China National Scholarship (Top 1% Rank)
- China UHV Scholarship (Top 1% Rank)
- Kaggle Santander Value Prediction Challenge, Silver Medal (Top 3.4% Rank)


# 📖 Education
- Georgia Institute of Technology, Ph.D. in Machine Learning
- Shanghai Jiao Tong University, M.S. in Electrical and Computer Engineering
- Xi'an Jiaotong University, B.S. in Electrical and Computer Engineering


# 💻 Experience
- *2025.05 - 2025.08*, Applied Research Intern, Google, Sunnyvale, California
- *2023.09 - 2024.04*, Research Intern, Cisco Research, San Jose, California
- *2020.05 - 2021.01*, Research Student Assistant, Rutgers University (Mentor: [Dimitris N. Metaxas](https://scholar.google.com/citations?user=a7VNhCIAAAAJ)), New Brunswick, New Jersey


# 📄 Services
- Program Committee for *AAAI*
- Conference Reviewer for *NeurIPS, ICML, ICLR, ACL, EMNLP, NAACL, EACL, KDD, AAAI, ECML*
- Journal Reviewer for *ACM TIST*
