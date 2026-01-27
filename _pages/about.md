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

Hello everyone, my name is Siheng Xiong. I am currently a final-year Ph.D. student in Machine Learning at the Georgia Institute of Technology, advised by [Prof. Faramarz Fekri](https://fekri.ece.gatech.edu/). Prior to this, I earned my Bachelor's degree from Xi'an Jiaotong University and my Master's degree from Shanghai Jiao Tong University. 

My research focuses on enabling deliberate reasoning and planning in large language models, with an emphasis on **model-based reasoning, long-context modelling, and structure-aware representations**, and with additional attention to efficiency and scalability.

# 🚀 Featured Projects

## Large Language Models for Reasoning and Planning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/PathWise.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Planning through World Model for Automated Heuristic Design via Self-Evolving LLMs]() \\
Oguzhan Gungordu, **Siheng Xiong**, Faramarz Fekri

[**Project**]()

- We introduce PathWise, a multi-agent framework that formulates automated heuristic design as a sequential planning problem. PathWise represents the search process using an entailment graph as a stateful memory and combines a policy agent, a world model, and critic agents to guide heuristic generation through planned evolutionary actions. The framework enables structured reasoning, reuse of prior derivations, and controlled self-evolution of LLM-generated heuristics.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/DeepControl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scaling Search-Augmented Reasoning Agents via Adaptive Information Control]() \\
**Siheng Xiong**, Oguzhan Gungordu, Faramarz Fekri

[**Project**](https://drive.google.com/drive/folders/1AJbT6Umvn1-gYby3tOPHhOgfomzl-mbk?usp=sharing)

- We propose DeepControl, a framework designed to verify both the reasoning and tool-usage processes of deep research agents. DeepControl acts as a plug-in module that enhances the reliability and effectiveness of research-oriented language agents by providing feedback and inspecting their intermediate workflows. To enable adaptive and self-improving control behavior, we train DeepControl through reinforcement fine-tuning, allowing it to learn when and how to intervene during complex reasoning and tool-invocation sequences.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/MLR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Language Model Reasoning with Structured Multi-Level Modeling](https://drive.google.com/file/d/1mg6N90vcH991lW86EL_Dzl2ecCcmQvNN/view?usp=sharing) \\
**Siheng Xiong**, Ali Payani, Faramarz Fekri

[**Project**]()

- We propose MLR (Multi-Level Reasoning), a planner–executor framework trained with iterative Step-DPO that enables more stable and robust long-horizon reasoning.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/SWAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deliberate Reasoning in Language Models as Structure-Aware Planning with an Accurate World Model](https://aclanthology.org/2025.acl-long.1540.pdf) \\
**Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/SWAP)

- SWAP (Structure-Aware Planning) is a structure-aware planning framework for multi-step reasoning with LMs. At each step, given the current state, represented as a graph, and an action, the enhanced world model predicts the next state as an updated graph. The policy model is guided by this graph to propose next action.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2025</div><img src='images/Casual-LM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CausalEval: Towards Better Causal Reasoning in Language Models](https://aclanthology.org/2025.naacl-long.622.pdf) \\
Longxuan Yu\*, Delin Chen\*, **Siheng Xiong\***, Qingyang Wu, Dawei Li, Zhikai Chen, Xiaoze Liu, Liangming Pan

[**Project**](https://github.com/chendl02/Awesome-LLM-Causal-Reasoning)

- We provide a comprehensive review of research aimed at enhancing LMs for causal reasoning. We evaluate the performance of different LMs and methods on various causal reasoning tasks, providing key findings and in-depth analysis.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/Tiger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Can LLMs Reason in the Wild with Programs?](https://aclanthology.org/2024.findings-emnlp.573.pdf) \\
Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri

[**Project**](https://github.com/gblackout/Reason-in-the-Wild)

- Tiger is a TactIc-Guided ReasonER designed to tackle reasoning-in-the-wild tasks by generating and refining programs. It learns from previous trajectories to iteratively improve program generation, enabling more effective reasoning (like OpenAI o1 model).

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/TG-LLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Large Language Models Can Learn Temporal Reasoning](https://aclanthology.org/2024.acl-long.563.pdf) \\
**Siheng Xiong**, Ali Payani, Ramana Kompella, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/TG-LLM)

- TG-LLM performs temporal reasoning in two steps: 1) Text-to-Temporal Graph translation: generate (relevant) temporal graph given the context and keyword (extracted from questions); 2) Temporal Graph Reasoning: perform deliberate Chain-of-Thought reasoning over the temporal graph.


</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/LogicLLaMA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Harnessing the power of large language models for natural language to first-order logic translation](https://aclanthology.org/2024.acl-long.375.pdf) \\
Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri

[**Project**](https://github.com/gblackout/LogicLLaMA)

- LogicLLaMA can be used standalone or to correct previously generated rules by other models for the NL-FOL translation task.

</div>
</div>



## Long Context Language Modelling

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/DHSA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Long-Context Modeling with Dynamic Hierarchical Sparse Attention for On-Device LLMs](https://arxiv.org/pdf/2510.24606) \\
**Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho


[**Project**](https://github.com/xiongsiheng/DHSA)

- We introduce Dynamic Hierarchical Sparse Attention (DHSA), a plug-in module integrated into each Transformer layer that enables multi-head attention to skip unimportant token pairs. The key idea is to exploit chunk-level similarity to guide token-level sparsity prediction, enhanced with dynamic chunking and length-normalized chunk representations. DHSA attains the performance of dense attention while significantly reducing both latency and memory usage.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LM-OS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/pdf/2409.01495) \\
Yuan Yang, **Siheng Xiong**, Ehsan Shareghi, Faramarz Fekri

[**Project**](https://github.com/gblackout/LM-OS)

- We introduce compressor-retriever, a model-agnostic architecture designed for life-long context management. Our approach exclusively uses the base model's forward function to compress and retrieve context, ensuring end-to-end differentiability.

</div>
</div>



## Temporal Knowledge Graph Reasoning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/TILR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TILR: Temporal Inductive Logic Reasoning over Hypergraphs](https://www.ijcai.org/proceedings/2024/0400.pdf) \\
Yuan Yang, **Siheng Xiong**, Ali Payani, James C Kerce, Faramarz Fekri

[**Project**](https://github.com/gblackout/TILR)

- TILR is a reasoning framework that detects inductive patterns in temporal data via neural-logic methodology. The framework aims to assist the training of modern ML models by inducing patterns for accurate grounding with fewer data.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/TEILP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TEILP: Time prediction over knowledge graphs via logical reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/29544) \\
**Siheng Xiong**, Yuan Yang, Ali Payani, James C Kerce, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/TEILP)

- TEILP is a follow-up work of TILP. We convert TKGs into a temporal event knowledge graph (TEKG) which equips us to develop a differentiable random walk approach. We also introduce conditional probability density functions, associated with the logical rules involving the query interval, using which we arrive at the time prediction.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/TILP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TILP: Differentiable learning of temporal logical rules on knowledge graphs](https://openreview.net/pdf?id=_X12NmQKvX) \\
**Siheng Xiong**, Yuan Yang, Faramarz Fekri, James Clayton Kerce

[**Project**](https://github.com/xiongsiheng/TILP)

- TILP is the first differentiable framework for temporal logical rules learning. We introduce constrained random walk mechanism and temporal operators with temporal features modeling, e.g., recurrence, temporal order, interval between pair of relations, and duration.

</div>
</div>



# 📝 Selected Publications

## 📝 Preprints
- ``Preprint 2026`` [Planning through World Model for Automated Heuristic Design via Self-Evolving LLMs]() Oguzhan Gungordu, **Siheng Xiong**, Faramarz Fekri [[Repo]]()
- ``Preprint 2025`` [DeepControl: Enhancing Research Agents via Process-Level Verification]() **Siheng Xiong**, Oguzhan Gungordu, Faramarz Fekri [[Repo]](https://drive.google.com/drive/folders/1AJbT6Umvn1-gYby3tOPHhOgfomzl-mbk?usp=sharing)
- ``Preprint 2025`` [Enhancing Long Chain-of-Thought Reasoning with Multi-Path Planning with Aggregation](https://arxiv.org/pdf/2510.11620) **Siheng Xiong**, Ali Payani, Faramarz Fekri  [[Repo]](https://github.com/xiongsiheng/MPPA)
- ``Preprint 2025`` [Long-Context Modeling with Dynamic Hierarchical Sparse Attention for On-Device LLMs](https://drive.google.com/file/d/12DVC0Yzw7jUaYLZl8K-fhpLdgMnMWDpz/view?usp=sharing) **Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho [[Repo]](https://drive.google.com/drive/folders/1AVdQOfCqRPYNNBzcfiSw1r-lBpRKO9Uy?usp=sharing)
- ``Preprint 2024`` [The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/pdf/2409.01495) Yuan Yang, **Siheng Xiong**, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LM-OS)

## 📝 Published
- ``ICLR 2026`` [Enhancing Language Model Reasoning with Structured Multi-Level Modeling](https://drive.google.com/file/d/1mg6N90vcH991lW86EL_Dzl2ecCcmQvNN/view?usp=sharing) **Siheng Xiong**, Ali Payani, Faramarz Fekri  [[Repo]]()
- ``NeurIPS 2025 @ ER`` [Long-Context Modeling with Dynamic Hierarchical Sparse Attention for On-Device LLMs](https://arxiv.org/pdf/2510.24606) **Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho [[Repo]](https://github.com/xiongsiheng/DHSA)
- ``ACS 2025`` [Deliberate Planning in Language Models with Symbolic Representation](https://arxiv.org/pdf/2505.01479) **Siheng Xiong**, Zhangding Liu, Jieyu Zhou, Yusen Su [[Repo]](https://github.com/xiongsiheng/SymPlanner)
- ``ACL 2025 (main)`` [Deliberate Reasoning in Language Models as Structure-Aware Planning with an Accurate World Model](https://arxiv.org/pdf/2410.03136) **Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/SWAP)
- ``NAACL 2025 (main)`` [CausalEval: Towards Better Causal Reasoning in Language Models](https://arxiv.org/pdf/2410.16676) Longxuan Yu\*, Delin Chen\*, **Siheng Xiong\***, Qingyang Wu, Qingzhen Liu, Dawei Li, Zhikai Chen, Xiaoze Liu, Liangming Pan [[Repo]](https://github.com/chendl02/Awesome-LLM-Causal-Reasoning)
- ``EMNLP 2024`` [Can LLMs Reason in the Wild with Programs?](https://aclanthology.org/2024.findings-emnlp.573.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/Reason-in-the-Wild)
- ``IJCAI 2024`` [Temporal Inductive Logic Reasoning over Hypergraphs](https://www.ijcai.org/proceedings/2024/0400.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/gblackout/TILR)
- ``ACL 2024 (main)`` [Large Language Models Can Learn Temporal Reasoning](https://aclanthology.org/2024.acl-long.563.pdf) **Siheng Xiong**, Ali Payani, Ramana Kompella, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TG-LLM)
- ``ACL 2024 (main)`` [Harnessing the power of large language models for natural language to first-order logic translation](https://aclanthology.org/2024.acl-long.375.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LogicLLaMA)
- ``AAAI 2024`` <span style="color:red">(Oral)</span> [TEILP: Time prediction over knowledge graphs via logical reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/29544) **Siheng Xiong**, Yuan Yang, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TEILP)
- ``ICLR 2023`` [TILP: Differentiable learning of temporal logical rules on knowledge graphs](https://openreview.net/pdf?id=_X12NmQKvX) **Siheng Xiong**, Yuan Yang, Faramarz Fekri, James Clayton Kerce [[Repo]](https://github.com/xiongsiheng/TILP)


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
- Conference Reviewer for *NeurIPS, ICML, ICLR, ACL, EMNLP, NAACL, EACL, KDD, AAAI*
- Journal Reviewer for *ACM TIST*