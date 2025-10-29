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

My research interests include reasoning and planning with large language models and knowledge graphs, as well as efficient long-context language modeling. More specifically, my current research focuses on **advancing the reasoning capabilities of large language models**.

# 🚀 Featured Projects

## Large Language Models Towards Reasoning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/DeepControl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeepControl: Enhancing Research Agents via Process-Level Verification]() \\
**Siheng Xiong**, Oguzhan Gungordu, Blair Johnson, Mika Okamoto, Clayton Kerce, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/DeepVerify)

- We propose DeepControl, a framework designed to verify both the reasoning and tool-usage processes of deep research agents. DeepControl acts as a plug-in module that enhances the reliability and effectiveness of research-oriented language agents by providing feedback and inspecting their intermediate workflows. To enable adaptive and self-improving control behavior, we train DeepControl through reinforcement fine-tuning, allowing it to learn when and how to intervene during complex reasoning and tool-invocation sequences.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/MPPA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Long Chain-of-Thought Reasoning with Multi-Path Planning with Aggregation](https://arxiv.org/pdf/2510.11620) \\
**Siheng Xiong**, Ali Payani, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/MPPA)

- We propose MPPA (Multi-Path Planning with Aggregation), a framework designed to help large reasoning models overcome Chain-of-Thought derailment by enabling multi-path planning aggregation. To train MPPA effectively, we introduce online Step-DPO, a process-level preference optimization scheme that leverages Twisted Sequential Monte Carlo to provide scalable, stepwise supervision. This approach enables efficient learning, stabilizes long-trajectory reasoning, and enhances overall reasoning accuracy.

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
- ``Preprint 2025`` [DeepControl: Enhancing Research Agents via Process-Level Verification]() **Siheng Xiong**, Oguzhan Gungordu, Blair Johnson, Mika Okamoto, Clayton Kerce, Faramarz Fekri  [[Repo]](https://github.com/xiongsiheng/DeepVerify)
- ``Preprint 2025`` [Enhancing Long Chain-of-Thought Reasoning with Multi-Path Planning with Aggregation](https://arxiv.org/pdf/2510.11620) **Siheng Xiong**, Ali Payani, Faramarz Fekri,  [[Repo]](https://github.com/xiongsiheng/MPPA)
- ``Preprint 2025`` [Long-Context Modeling with Dynamic Hierarchical Sparse Attention for On-Device LLMs](https://drive.google.com/file/d/12DVC0Yzw7jUaYLZl8K-fhpLdgMnMWDpz/view?usp=sharing) **Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho [[Repo]](https://drive.google.com/drive/folders/1AVdQOfCqRPYNNBzcfiSw1r-lBpRKO9Uy?usp=sharing)
- ``Preprint 2024`` [The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/pdf/2409.01495) Yuan Yang, **Siheng Xiong**, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LM-OS)
- ``Preprint 2024`` [On The Theory of Semantic Information and Communication for Logical Inference](https://arxiv.org/pdf/2401.17556) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/Inductive-Semantic-Communication-Dataset)

## 📝 Published
- ``NeurIPS 2025 @ ER`` [Long-Context Modeling with Dynamic Hierarchical Sparse Attention for On-Device LLMs](https://arxiv.org/pdf/2510.24606) **Siheng Xiong**, Joe Zou, Faramarz Fekri, Yae Jee Cho [[Repo]](https://github.com/xiongsiheng/DHSA)
- ``ACS 2025`` [Deliberate Planning in Language Models with Symbolic Representation](https://arxiv.org/pdf/2505.01479) **Siheng Xiong**, Zhangding Liu, Jieyu Zhou, Yusen Su [[Repo]](https://github.com/xiongsiheng/SymPlanner)
- ``ACL 2025 (main)`` [Deliberate Reasoning in Language Models as Structure-Aware Planning with an Accurate World Model](https://arxiv.org/pdf/2410.03136) **Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/SWAP)
- ``NAACL 2025 (main)`` [CausalEval: Towards Better Causal Reasoning in Language Models](https://arxiv.org/pdf/2410.16676) Longxuan Yu\*, Delin Chen\*, **Siheng Xiong\***, Qingyang Wu, Qingzhen Liu, Dawei Li, Zhikai Chen, Xiaoze Liu, Liangming Pan [[Repo]](https://github.com/chendl02/Awesome-LLM-Causal-Reasoning)
- ``Globecom 2025`` [Analysis of Semantic Communication for Logic-based Hypothesis Deduction](https://arxiv.org/pdf/2508.21755) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri
- ``ICMLCN 2025`` [DISCD: Distributed Lossy Semantic Communication for Logical Deduction of Hypothesis](https://arxiv.org/pdf/2502.05744) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri [[Repo]](https://github.com/ahmetfsaz/DISCD)
- ``WCNC 2025`` [Lossy Semantic Communication for the Logical Deduction of the State of the World](https://arxiv.org/pdf/2410.01676) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/SemCom)
- ``EMNLP 2024`` [Can LLMs Reason in the Wild with Programs?](https://aclanthology.org/2024.findings-emnlp.573.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/Reason-in-the-Wild)
- ``IJCAI 2024`` [Temporal Inductive Logic Reasoning over Hypergraphs](https://www.ijcai.org/proceedings/2024/0400.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/gblackout/TILR)
- ``ACL 2024 (main)`` [Large Language Models Can Learn Temporal Reasoning](https://aclanthology.org/2024.acl-long.563.pdf) **Siheng Xiong**, Ali Payani, Ramana Kompella, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TG-LLM)
- ``ACL 2024 (main)`` [Harnessing the power of large language models for natural language to first-order logic translation](https://aclanthology.org/2024.acl-long.375.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LogicLLaMA)
- ``AAAI 2024`` <span style="color:red">(Oral)</span> [TEILP: Time prediction over knowledge graphs via logical reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/29544) **Siheng Xiong**, Yuan Yang, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TEILP)
- ``ICLR 2023`` [TILP: Differentiable learning of temporal logical rules on knowledge graphs](https://openreview.net/pdf?id=_X12NmQKvX) **Siheng Xiong**, Yuan Yang, Faramarz Fekri, James Clayton Kerce [[Repo]](https://github.com/xiongsiheng/TILP)
- ``IEEE Transactions on Power Delivery 2021`` [RSSPN: robust semi-supervised prototypical network for fault root cause classification in power distribution systems](https://ieeexplore.ieee.org/abstract/document/9606537) Tianqing Zheng, Yadong Liu, Yingjie Yan, **Siheng Xiong**, Tao Lin, Yanxia Chen, Zhiyong Wang, Xiuchen Jiang
- ``IET Generation, Transmission & Distribution 2021`` [Object recognition for power equipment via human‐level concept learning](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/gtd2.12088) **Siheng Xiong**, Yadong Liu, Yingjie Yan, Ling Pei, Peng Xu, Xiaofei Fu, Xiuchen Jiang [[Repo]](https://github.com/xiongsiheng/Power-equipment-image-dataset)
- ``PESGM 2020`` [Power equipment recognition method based on mask R-CNN and bayesian context network](https://ieeexplore.ieee.org/abstract/document/9281755) **Siheng Xiong**, Yadong Liu, Rui Xu, Ying Du, Zihan Cong, Yingjie Yan, Xiuchen Jiang
- ``IEEE Transactions on Smart Grid 2020`` [Incipient fault identification in power distribution systems via human-level concept learning](https://ieeexplore.ieee.org/abstract/document/9094224) **Siheng Xiong**, Yadong Liu, Jian Fang, Jindun Dai, Lingen Luo, Xiuchen Jiang [[Repo]](https://github.com/xiongsiheng/Incipient-fault-waveform-dataset)


# 🎖 Honors and Awards
- China National Scholarship (Top 1% Rank)
- China UHV Scholarship (Top 1% Rank)
- China National Mathematical Modeling Competition, Regional First Prize
- China National College Students' Mathematics Competition, Second Prize
- Mathematical Contest in Modeling, Meritorious Winner
- Xi'an Jiaotong University Outstanding Student, Outstanding Undergraduate Graduate
- Kaggle Santander Value Prediction Challenge, Silver Medal (Top 3.4% Rank)


# 📖 Education
- Georgia Institute of Technology, Machine Learning, Ph.D.
- Shanghai Jiao Tong University, ECE, Master Degree.
- Xi'an Jiaotong University, ECE, Bachelor Degree. 


# 💻 Experience
- *2025.05 - 2025.08*, Applied Research Intern, Google, Sunnyvale, California
- *2023.09 - 2024.04*, Research Intern, Cisco, San Jose, California
- *2020.05 - 2021.01*, Research Student Assistant, Rutgers University (Mentor: [Dimitris N. Metaxas](https://scholar.google.com/citations?user=a7VNhCIAAAAJ)), New Brunswick, New Jersey


# 📄 Services
- Program Committee for *AAAI*
- Conference Reviewer for *NIPS, ICLR, ICML, AAAI, ACL, EMNLP, NAACL, EACL*
- Journal Reviewer for *FAI, FCS, AJCST, COMPJ*