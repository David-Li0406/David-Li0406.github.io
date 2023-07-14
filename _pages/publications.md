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

* Automated Trans-Lingual Definition Generation via Contrastive Prompt Learning
Hengyuan Zhang, **Dawei Li**, Yanran Li, Chenming Shang, Chufan Shi, Yong Jiang. **BEA-ACL 2023**
* Fine-grained Contrastive Learning for Definition Generation
Hengyuan Zhang*, **Dawei Li\***, Shiping Yang, Yanran Li. **AACL 2022 (Oral)**
* C3KG: A Chinese Commonsense Conversation Knowledge Graph
**Dawei Li**, Yanran Li, Jiayi Zhang, Ke Li, Chen Wei, Jianwei Cui, Bin Wang. **ACL 2022 (Findings)**
* Domain Adaptation in Nuclei Semantic Segmentation
**Dawei Li**, Zongxuan Shi, Hao Zhang, Renhao Zhang. **CVAD 2022**

Works in Progress
======

* Multi-level Contrastive Learning for Scripts-based Character Understanding
**Dawei Li**, Hengyuan Zhang, Yanran Li, Shiping Yang
* READ: Improving Relation Extraction from an Adversarial Perspective
**Dawei Li**, William P Hogan, Jingbo Shang
* DAIL: Data Augmentation for In-Context Learning via Self-Paraphrase
**Dawei Li**, Yaxuan Li, Dheeraj Mekala, Shuyao Li, Yulin wang, Xueqi Wang, William P Hogan, Jingbo Shang