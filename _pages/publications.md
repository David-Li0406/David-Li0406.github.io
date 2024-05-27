---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

(* Equal Contribution)

2024
======
* Balancing Speciality and Versatility: a Coarse to Fine Framework for Supervised Fine-tuning Large Language Model<br />
Hengyuan Zhang, Yanru Wu, **Dawei Li**, Zacc Yang, Rui Zhao, Yong Jiang, Fei Tan
* Can LLMs Learn from Previous Mistakes? Investigating LLMs' Errors to Boost for Reasoning<br />
Yongqi Tong, **Dawei Li**, Sizhe Wang, Yujia Wang, Fei Teng, Jingbo Shang
* READ: Improving Relation Extraction from an Adversarial Perspective<br />
**Dawei Li**, William P Hogan, Jingbo Shang. **NAACL 2024 (Findings)**
* Contextualization Distillation from Large Language Model for Knowledge Graph Completion<br />
**Dawei Li**, Zhen Tan, Tianlong Chen, Huan Liu. **EACL 2024 (Findings)**

2023
======
* Multi-level Contrastive Learning for Scripts-based Character Understanding<br />
**Dawei Li**, Hengyuan Zhang, Yanran Li, Shiping Yang. **EMNLP 2023**
* Automated Trans-Lingual Definition Generation via Contrastive Prompt Learning<br />
Hengyuan Zhang, **Dawei Li**, Yanran Li, Chenming Shang, Chufan Shi, Yong Jiang. **BEA-ACL 2023**

2022
======
* Fine-grained Contrastive Learning for Definition Generation<br />
Hengyuan Zhang*, **Dawei Li**\*, Shiping Yang, Yanran Li. **AACL 2022 (Oral)**
* C3KG: A Chinese Commonsense Conversation Knowledge Graph<br />
**Dawei Li**, Yanran Li, Jiayi Zhang, Ke Li, Chen Wei, Jianwei Cui, Bin Wang. **ACL 2022 (Findings)**
* Domain Adaptation in Nuclei Semantic Segmentation<br />
**Dawei Li**, Zongxuan Shi, Hao Zhang, Renhao Zhang. **CVAD 2022**

Preprint
======
* DALK: Dynamic Co-Augmentation of LLMs and KG to answer Alzheimer's Disease Questions with Scientific Literature<br />
**Dawei Li**\*, Shu Yang*, Zhen Tan, Jae Young Baik, Sunkwon Yun, Joseph Lee, Aaron Chacko, Bojian Hou, Duy Duong-Tran, Ying Ding, Huan Liu, Li Shen, Tianlong Chen
* DAIL: Data Augmentation for In-Context Learning via Self-Paraphrase<br />
**Dawei Li**, Yaxuan Li, Dheeraj Mekala, Shuyao Li, Yulin wang, Xueqi Wang, William P Hogan, Jingbo Shang


Works in Progress
======
* A Question-centric Multi-experts Contrastive Learning Framework for Improving Deep Sequential Knowledge Tracing<br />
Hengyuan Zhang, Zitao Liu, Chenming Shang, **Dawei Li**, Yong Jiang