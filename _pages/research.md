---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




<!-- <font size = 5> <i> Explainable Few-shot Talent Recommendation</i>, 2023, Under Review </font>

- **Keywords:** Talent Recommendation, Few-shot Recommendation, Explainable Machine Learning, Cold-start Problem
- **Abstract:** Many companies encounter human resource challenges, with high recruitment costs and long hiring cycles being particularly prominent. Numerous studies propose models to expedite the matching of talent with jobs. However, they all overlook the cold-start problem caused by the scarcity of data in the warm-up stage of a new job position. Meanwhile, the interpretability of recommendation is also very important and rarely studied in talent recommendation. Therefore, we focus on solving the cold-start problem in the early stage of recruitment and propose an explainable few-shot talent recommendation model, named EFTR. Specifically, EFTR has a neural topic learning module to map job descriptions and resumes into a shared latent topic space, enabling the recommendation's interpretability. A few-shot learning module is designed to learn jobs' comprehensive representations based on limited information. Experimental results on two real-world datasets demonstrate the superiority of our proposed EFTR over state-of-the-art methods. 


<font size = 5> <i>TJ-MTNet: A Multi-Task Learning Network for Job Mobility Prediction via Geographic Trajectories</i>, 2021, Work in Progress </font>
- **Keywords:** Job Mobility Prediction, Trajectory, Spatial-temporal, Multi-task Learning
- **Abstract:**  Job mobility is one of the most significant problems in enterprise and talent management. Traditionally, survey methods are widely adopted to analyze the key factors of job mobility, but the survey data cannot timely provide reliable information. Thanks to the development of smart de- vices with location services, it is convenient to collect people’s trajectories automatically and continuously. Furthermore, people’s trajectories may bear many indications about job mobility. To this end, we design a trajectory-based multi-task learn- ing network for job mobility prediction, namely TJ-MTNet. Specifically, TJ-MTNet includes: (1) a *multi-level spatial-temporal encoder* to capture the spatial-temporal patterns of trajectories; (2) a *graph-based activity encoder* to capture the semantic information hidden in trajectories, which per- forms graph convolutional neural networks on a constructed activity graph and (3) *task-specified gates and decoders* to filter out useful latent transition patterns with supervisions by the downstream tasks (i.e., job mobility prediction and an auxiliary task). The results on real-world mobility datasets show the superiority of TJ-MTNet against extensive baselines. -->

Archived Publications
====

### 1.  Helmsman of the Masses? Evaluate the Opinion Leadership of Large Language Models in the Werewolf Game

Silin Du, Xiaowei Zhang, *First Conference on Language Modeling (COLM)*, 2024

[![Paper](https://img.shields.io/badge/Paper-OpenReview%20-green)](https://openreview.net/forum?id=xMt9kCv5YR#discussion) [![Code](https://img.shields.io/badge/Code-Github%20Link-orange)](https://github.com/doslim/Evaluate-the-Opinion-Leadership-of-LLMs) 

- **Keywords**: Opinion Leadership, Large Language Models, Werewolf Game, Simulation, Human-AI Interaction
- **Abstract:** Large language models (LLMs) have exhibited memorable strategic behaviors in social deductive games. However, the significance of opinion leadership exhibited by LLM-based agents has been overlooked, which is crucial for practical applications in multi-agent and human-AI interaction settings. Opinion leaders are individuals who have a noticeable impact on the beliefs and behaviors of others within a social group. In this work, we employ the Werewolf game as a simulation platform to assess the opinion leadership of LLMs. The game features the role of the Sheriff, tasked with summarizing arguments and recommending decision options, and therefore serves as a credible proxy for an opinion leader. We develop a framework integrating the Sheriff role and devise two novel metrics for evaluation based on the critical characteristics of opinion leaders. The first metric measures the reliability of the opinion leader, and the second assesses the influence of the opinion leader on other players' decisions. We conduct extensive experiments to evaluate LLMs of different scales. In addition, we collect a Werewolf question-answering dataset (WWQA) to assess and enhance LLM's grasp of the game rules, and we also incorporate human participants for further analysis. The results suggest that the Werewolf game is a suitable test bed to evaluate the opinion leadership of LLMs and few LLMs possess the capacity for opinion leadership.


### 2.  L3TR: Large Language Models for Listwise Talent Recommendation

Silin Du, Hongyan Liu, *International Conference on Information Systems (ICIS)*, 2024. 

- **Keywords**:  Large language models, Talent recommendation, Listwise recommendation, Fine-tuning, Positional encoding, Position bias
- **Abstract:** Many companies encounter human resource challenges, with high recruitment costs and long hiring cycles being particularly prominent. Numerous studies propose models to expedite the matching of talent with jobs. The remarkable ability of large language models (LLMs) to understand texts provides unprecedented opportunities to build LLM-based talent recommendation models. However, previous attempts focus on the pointwise setting, requiring LLMs to repeatedly process some text and ignoring the relationship among talents in the candidate list, which is inefficient and inferior. Therefore, we propose a novel method to enhance LLMs with the listwise talent recommendation task, named L3TR. First, we propose two strategies to extract the recommendation results from LLMs. Then we design a hierarchical positional embedding to enhance the connection between the job postings and each resume in the candidate list. Experiments on a real-world dataset show the superiority of L3TR over classic methods and LLM-based methods in terms of accuracy.

Unarchived Paper and Working Paper
====

### 3.  Exploring a New Competency Modeling Process via Large Language Models

Silin Du, Manqing Xin, 2024, Working paper

- **Keywords**: Large Language Models, Competency Modeling, Human Resources Management