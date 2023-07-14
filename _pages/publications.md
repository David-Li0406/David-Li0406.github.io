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


* Automated Trans-Lingual Definition Generation via Contrastive Prompt Learning
* Fine-grained Contrastive Learning for Definition Generation
* C3KG: A Chinese Commonsense Conversation Knowledge Graph
* Domain Adaptation in Nuclei Semantic Segmentation

Works in Progress
======

* Multi-level Contrastive Learning for Scripts-based Character Understanding
* READ: Improving Relation Extraction from an Adversarial Perspective
* DAIL: Data Augmentation for In-Context Learning via Self-Paraphrase