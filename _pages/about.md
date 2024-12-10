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

Hello everyone, my name is Siheng Xiong. Currently, I am a fourth year Ph.D. student from Georgia Institute of Technology, supervised by [Prof. Faramarz Fekri](https://fekri.ece.gatech.edu/). Previously, I received my bachelor and master degree from Xi'an Jiaotong University and Shanghai Jiao Tong University, respectively. 

My research interest includes knowledge graph reasoning and large language models. Specifically, my current research is mainly about **Large Language Models Towards Reasoning**. 

# 🚀 Featured Projects

## Large Language Models Towards Reasoning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/SWAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deliberate Reasoning for LLMs as Structure-aware Planning with Accurate World Model](https://arxiv.org/abs/2410.03136) \\
**Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/SWAP)

- SWAP is a structure-aware planning framework for multi-step reasoning with LLMs. At each step, given the current state, represented as a graph, and an action, the accurate world model predicts the next state as an updated graph. The policy model is guided by this graph to propose next action.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/Casual-LM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improving Causal Reasoning in Large Language Models: A Survey](https://arxiv.org/abs/2410.16676) \\
Longxuan Yu\*, Delin Chen\*, **Siheng Xiong\***, Qingyang Wu, Qingzhen Liu, Dawei Li, Zhikai Chen, Xiaoze Liu, Liangming Pan

[**Project**](https://github.com/chendl02/Awesome-LLM-Causal-Reasoning)

- We provide a comprehensive review of research aimed at enhancing LLMs for causal reasoning. We evaluate the performance of LLMs on various causal reasoning tasks, providing key findings and in-depth analysis.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/Tiger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Can LLMs Reason in the Wild with Programs?](https://aclanthology.org/2024.findings-emnlp.573) \\
Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri

[**Project**](https://github.com/gblackout/Reason-in-the-Wild)

- Tiger is a TactIc-Guided ReasonER designed to tackle reasoning-in-the-wild tasks by generating and refining programs. It learns from previous trajectories to iteratively improve program generation, enabling more effective reasoning (like OpenAI o1 model).

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/TG-LLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Large Language Models Can Learn Temporal Reasoning](https://aclanthology.org/2024.acl-long.563/) \\
**Siheng Xiong**, Ali Payani, Ramana Kompella, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/TG-LLM)

- TG-LLM performs temporal reasoning in two steps: 1) Text-to-Temporal Graph translation: generate (relevant) temporal graph given the context and keyword (extracted from questions); 2) Temporal Graph Reasoning: perform deliberate Chain-of-Thought reasoning over the temporal graph.


</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/LogicLLaMA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Harnessing the power of large language models for natural language to first-order logic translation](https://aclanthology.org/2024.acl-long.375/) \\
Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri

[**Project**](https://github.com/gblackout/LogicLLaMA)

- LogicLLaMA can be used standalone or to correct previously generated rules by other models for the NL-FOL translation task.

</div>
</div>



## The Language Model OS

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LM-OS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/abs/2409.01495) \\
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
- ``Preprint 2024`` [DISCD: Distributed Lossy Semantic Communication for Logical Deduction of Hypothesis](https://drive.google.com/file/d/1Rur5UeNW7ETjFt5r4C0F66-FScQKG5tF/view?usp=drive_link) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/SemCom)
- ``Preprint 2024``[Improving Causal Reasoning in Large Language Models: A Survey](https://arxiv.org/abs/2410.16676) Longxuan Yu\*, Delin Chen\*, **Siheng Xiong\***, Qingyang Wu, Qingzhen Liu, Dawei Li, Zhikai Chen, Xiaoze Liu, Liangming Pan [[Repo]](https://github.com/chendl02/Awesome-LLM-Causal-Reasoning)
- ``Preprint 2024`` [Deliberate Reasoning for LLMs as Structure-aware Planning with Accurate World Model](https://arxiv.org/abs/2410.03136) **Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/SWAP).
- ``Preprint 2024`` [The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/abs/2409.01495) Yuan Yang, **Siheng Xiong**, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LM-OS)
- ``Preprint 2024`` [Lossy Semantic Communication for the Logical Deduction of the State of the World](https://arxiv.org/abs/2410.01676) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/SemCom)
- ``Preprint 2023`` [Model-Theoretic Logic for Mathematical Theory of Semantic Information and Communication](https://arxiv.org/abs/2401.17556) Ahmet Faruk Saz, **Siheng Xiong**, Yashas Malur Saidutta, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/Inductive-Semantic-Communication-Dataset)

## 📝 Published
- ``EMNLP 2024`` [Can LLMs Reason in the Wild with Programs?](https://aclanthology.org/2024.findings-emnlp.573) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/Reason-in-the-Wild)
- ``IJCAI 2024`` [Temporal Inductive Logic Reasoning over Hypergraphs](https://www.ijcai.org/proceedings/2024/0400.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/gblackout/TILR)
- ``ACL 2024 (main)`` [Large Language Models Can Learn Temporal Reasoning](https://aclanthology.org/2024.acl-long.563/) **Siheng Xiong**, Ali Payani, Ramana Kompella, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TG-LLM)
- ``ACL 2024 (main)`` [Harnessing the power of large language models for natural language to first-order logic translation](https://aclanthology.org/2024.acl-long.375/) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri [[Repo]](https://github.com/gblackout/LogicLLaMA)
- ``AAAI 2024`` <span style="color:red">(Oral)</span> [TEILP: Time prediction over knowledge graphs via logical reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/29544) **Siheng Xiong**, Yuan Yang, Ali Payani, James C Kerce, Faramarz Fekri [[Repo]](https://github.com/xiongsiheng/TEILP)
- ``ICLR 2023`` [TILP: Differentiable learning of temporal logical rules on knowledge graphs](https://openreview.net/forum?id=_X12NmQKvX) **Siheng Xiong**, Yuan Yang, Faramarz Fekri, James Clayton Kerce [[Repo]](https://github.com/xiongsiheng/TILP)
- ``IEEE Transactions on Power Delivery 2021`` [RSSPN: robust semi-supervised prototypical network for fault root cause classification in power distribution systems](https://ieeexplore.ieee.org/abstract/document/9606537) Tianqing Zheng, Yadong Liu, Yingjie Yan, **Siheng Xiong**, Tao Lin, Yanxia Chen, Zhiyong Wang, Xiuchen Jiang
- ``IET Generation, Transmission & Distribution 2021`` [Object recognition for power equipment via human‐level concept learning](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/gtd2.12088) **Siheng Xiong**, Yadong Liu, Yingjie Yan, Ling Pei, Peng Xu, Xiaofei Fu, Xiuchen Jiang [[Repo]](https://github.com/xiongsiheng/Power-equipment-image-dataset)
- ``PESGM 2020`` [Power equipment recognition method based on mask R-CNN and bayesian context network](https://ieeexplore.ieee.org/abstract/document/9281755) **Siheng Xiong**, Yadong Liu, Rui Xu, Ying Du, Zihan Cong, Yingjie Yan, Xiuchen Jiang
- ``IEEE Transactions on Smart Grid 2020`` [Incipient fault identification in power distribution systems via human-level concept learning](https://ieeexplore.ieee.org/abstract/document/9094224) **Siheng Xiong**, Yadong Liu, Jian Fang, Jindun Dai, Lingen Luo, Xiuchen Jiang [[Repo]](https://github.com/xiongsiheng/Incipient-fault-waveform-dataset)


# 🎖 Honors and Awards
- China National Scholarship (Top 1%)
- China UHV Scholarship (Top 1%)

# 📖 Education
- Georgia Institute of Technology, Machine Learning, Ph.D.
- Shanghai Jiao Tong University, ECE, Master Degree.
- Xi'an Jiaotong University, ECE, Bachelor Degree. 

# 💻 Internship
- *2023.09 - 2024.04*, Software Engineer PhD Intern, Cisco, San Jose, California
- *2020.05 - 2021.01*, Research Student Assistant, Rutgers University (Mentor: [Dimitris N. Metaxas](https://scholar.google.com/citations?user=a7VNhCIAAAAJ)), New Brunswick, New Jersey

# 📄 Services
- Reviewers for NIPS, ICLR, ICML, AAAI, ACL, EMNLP, FAI, AJCST
