---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
---


Comparison of Transformer Models from Topological Perspective [\[Paper\]](https://david-li0406.github.io/files/dsc_214_report.pdf)
======
* We extract mention representations from the whole sentence encoding outputted by each transformer model (E.g. BERT, GPT2) and build mapper graphs as the model’s topological summary; analyzed the mapper graph and determine the consistency of graph similarity between two models, corresponding to their architectural similarity.

Diff-Transferer: Any-Speaker Adaptive Text-to-Speech with Diffusion [\[Paper\]](https://david-li0406.github.io/files/dsc291_final_project.pdf)
======
* We proposed Diff-Transferer, an any-speaker text-to-speech model with a shallow diffusion mechanism; stabilized the traning process of the diffusion model and reduced the number of training steps needed to reach convergence.

NLP Research Hotspots Analysis with Structural and Unstructured Data [\[Slides\]](https://david-li0406.github.io/files/DSC202_Final_PPT_1208_.pdf)
======
* We crawled information of NLP papers in recent three years from semantic scholar API; extracted keywords from the abstract of each paper and conducted unsupervised topic clustering; analyzed the authors’ collaboration relationship with Neo4j; analyzed the combination of different topics with co-occurrence heatmap

Mental Support Conversational Recommendation Chatbot
======
* We sampled the triplets in C3KG to simulate users’ emotional cause chains; use sampled data as the training data of the conversational recommendation system and built a progressive mental support conversational recommendation chatbot to reason user’s emotional causes and provide suggestions. Then we reproduced a production version code of the conversational recommendation model with TensorFlow; optimized and deployed the model in the cloud server; created an API to call the multi-turn model. We also built a demo to interact with the backend model; built a dialog component with Vue.js, including message boxes, input boxes, and interactive buttons; created a visualization box based on D3.js to interact with the model dynamically.

Automated Essay Scoring (AES) system [\[Github\]](https://github.com/David-Li0406/AES-system)
======
AES is a composition automatic scoring system to get feedback to users with wording recommendation and data visualization. We built it Flask and Vue.