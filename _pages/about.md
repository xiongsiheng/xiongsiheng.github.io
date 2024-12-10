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

# 🚀 Projects



## Temporal knowledge graph reasoning


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/RNN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TILP: Differentiable learning of temporal logical rules on knowledge graphs](https://openreview.net/pdf?id=_X12NmQKvX) \\
**Siheng Xiong**, Yuan Yang, Faramarz Fekri, James Clayton Kerce

[**Project**](https://github.com/xiongsiheng/TILP)

- TILP is the first differentiable framework for temporal logical rules learning. We introduce constrained random walk mechanism and temporal operators with temporal features modeling, e.g., recurrence, temporal order, interval between pair of relations, and duration.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/TEILP_framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TEILP: Time prediction over knowledge graphs via logical reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/29544) \\
**Siheng Xiong**, Yuan Yang, Ali Payani, James C Kerce, Faramarz Fekri

[**Project**](https://github.com/xiongsiheng/TEILP)

- TEILP is a follow-up work of TILP. We convert TKGs into a temporal event knowledge graph (TEKG) which equips us to develop a differentiable random walk approach. We also introduce conditional probability density functions, associated with the logical rules involving the query interval, using which we arrive at the time prediction.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/TILR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Temporal Inductive Logic Reasoning over Hypergraphs](https://www.ijcai.org/proceedings/2024/0400.pdf) \\
Yuan Yang, **Siheng Xiong**, Ali Payani, James C Kerce, Faramarz Fekri

[**Project**](https://github.com/gblackout/TILR)

- TILR is a reasoning framework that detects inductive patterns in temporal data via neural-logic methodology. The framework aims to assist the training of modern ML models by inducing patterns for accurate grounding with fewer data.

</div>
</div>




# 📝 Publication

## 📝 Preprints
- [DISCD: Distributed Lossy Semantic Communication for Logical Deduction of Hypothesis](https://drive.google.com/file/d/1Rur5UeNW7ETjFt5r4C0F66-FScQKG5tF/view?usp=drive_link) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri 2024 [[Repo]](https://github.com/xiongsiheng/SemCom)
- [Improving Causal Reasoning in Large Language Models: A Survey](https://arxiv.org/abs/2410.16676) Longxuan Yu\*, Delin Chen\*, **Siheng Xiong\***, Qingyang Wu, Qingzhen Liu, Dawei Li, Zhikai Chen, Xiaoze Liu, Liangming Pan 2024 [[Repo]](https://github.com/chendl02/Awesome-LLM-Causal-Reasoning)
- [Deliberate Reasoning for LLMs as Structure-aware Planning with Accurate World Model](https://arxiv.org/abs/2410.03136) **Siheng Xiong**, Ali Payani, Yuan Yang, Faramarz Fekri 2024 [[Repo]](https://github.com/xiongsiheng/SWAP).
- [The Compressor-Retriever Architecture for Language Model OS](https://arxiv.org/abs/2409.01495) Yuan Yang, **Siheng Xiong**, Ehsan Shareghi, Faramarz Fekri 2024 [[Repo]](https://github.com/gblackout/LM-OS)
- [Lossy Semantic Communication for the Logical Deduction of the State of the World](https://arxiv.org/abs/2410.01676) Ahmet Faruk Saz, **Siheng Xiong**, Faramarz Fekri 2024 [[Repo]](https://github.com/xiongsiheng/SemCom)
- [Model-Theoretic Logic for Mathematical Theory of Semantic Information and Communication](https://arxiv.org/abs/2401.17556) Ahmet Faruk Saz, **Siheng Xiong**, Yashas Malur Saidutta, Faramarz Fekri 2023 [[Repo]](https://github.com/xiongsiheng/Inductive-Semantic-Communication-Dataset)

## 📝 Published
- [Can LLMs Reason in the Wild with Programs?](https://aclanthology.org/2024.findings-emnlp.573) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri; EMNLP 2024 (findings) [[Repo]](https://github.com/gblackout/Reason-in-the-Wild)
- [Temporal Inductive Logic Reasoning over Hypergraphs](https://www.ijcai.org/proceedings/2024/0400.pdf) Yuan Yang, **Siheng Xiong**, Ali Payani, James C Kerce, Faramarz Fekri; IJCAI 2024 [[Repo]](https://github.com/gblackout/TILR)
- [Large Language Models Can Learn Temporal Reasoning](https://aclanthology.org/2024.acl-long.563/) **Siheng Xiong**, Ali Payani, Ramana Kompella, Faramarz Fekri; ACL 2024 (main) [[Repo]](https://github.com/xiongsiheng/TG-LLM)
- [Harnessing the power of large language models for natural language to first-order logic translation](https://aclanthology.org/2024.acl-long.375/) Yuan Yang, **Siheng Xiong**, Ali Payani, Ehsan Shareghi, Faramarz Fekri; ACL 2024 (main) [[Repo]](https://github.com/gblackout/LogicLLaMA)
- [TEILP: Time prediction over knowledge graphs via logical reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/29544) **Siheng Xiong**, Yuan Yang, Ali Payani, James C Kerce, Faramarz Fekri; AAAI 2024 (oral) [[Repo]](https://github.com/xiongsiheng/TEILP)
- [TILP: Differentiable learning of temporal logical rules on knowledge graphs](https://openreview.net/forum?id=_X12NmQKvX) **Siheng Xiong**, Yuan Yang, Faramarz Fekri, James Clayton Kerce; ICLR 2023 [[Repo]](https://github.com/xiongsiheng/TILP)
- [RSSPN: robust semi-supervised prototypical network for fault root cause classification in power distribution systems](https://ieeexplore.ieee.org/abstract/document/9606537) Tianqing Zheng, Yadong Liu, Yingjie Yan, **Siheng Xiong**, Tao Lin, Yanxia Chen, Zhiyong Wang, Xiuchen Jiang; IEEE Transactions on Power Delivery, 2021
- [Object recognition for power equipment via human‐level concept learning](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/gtd2.12088) **Siheng Xiong**, Yadong Liu, Yingjie Yan, Ling Pei, Peng Xu, Xiaofei Fu, Xiuchen Jiang; IET Generation, Transmission & Distribution, 2021 [[Repo]](https://github.com/xiongsiheng/Power-equipment-image-dataset)
- [Power equipment recognition method based on mask R-CNN and bayesian context network](https://ieeexplore.ieee.org/abstract/document/9281755) **Siheng Xiong**, Yadong Liu, Rui Xu, Ying Du, Zihan Cong, Yingjie Yan, Xiuchen Jiang; IEEE Power & Energy Society General Meeting (PESGM) 2020
- [Incipient fault identification in power distribution systems via human-level concept learning](https://ieeexplore.ieee.org/abstract/document/9094224) **Siheng Xiong**, Yadong Liu, Jian Fang, Jindun Dai, Lingen Luo, Xiuchen Jiang; IEEE Transactions on Smart Grid 2020 [[Repo]](https://github.com/xiongsiheng/Incipient-fault-waveform-dataset)


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
