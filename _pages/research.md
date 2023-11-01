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




<font size = 5> < pre > Explainable Few-shot Talent Recommendation{font-style: italic;} </pre>, 2023, Under Review </font>

- **Keywords:** Talent Recommendation, Few-shot Recommendation, Explainable Machine Learning, Cold-start Problem
- **Abstract:** Many companies encounter human resource challenges, with high recruitment costs and long hiring cycles being particularly prominent. Numerous studies propose models to expedite the matching of talent with jobs. However, they all overlook the cold-start problem caused by the scarcity of data in the warm-up stage of a new job position. Meanwhile, the interpretability of recommendation is also very important and rarely studied in talent recommendation. Therefore, we focus on solving the cold-start problem in the early stage of recruitment and propose an explainable few-shot talent recommendation model, named EFTR. Specifically, EFTR has a neural topic learning module to map job descriptions and resumes into a shared latent topic space, enabling the recommendation's interpretability. A few-shot learning module is designed to learn jobs' comprehensive representations based on limited information. Experimental results on two real-world datasets demonstrate the superiority of our proposed EFTR over state-of-the-art methods. 


<font size = 5> < pre > TJ-MTNet: A Multi-Task Learning Network for Job Mobility Prediction via Geographic Trajectories{font-style: italic;} </pre> , 2021, Work in Progress </font>
- **Keywords:** Job Mobility Prediction, Trajectory, Spatial-temporal, Multi-task Learning
- **Abstract:**  Job mobility is one of the most significant problems in enterprise and talent management. Traditionally, survey methods are widely adopted to analyze the key factors of job mobility, but the survey data cannot timely provide reliable information. Thanks to the development of smart de- vices with location services, it is convenient to collect people’s trajectories automatically and continuously. Furthermore, people’s trajectories may bear many indications about job mobility. To this end, we design a trajectory-based multi-task learn- ing network for job mobility prediction, namely TJ-MTNet. Specifically, TJ-MTNet includes: (1) a *multi-level spatial-temporal encoder* to capture the spatial-temporal patterns of trajectories; (2) a *graph-based activity encoder* to capture the semantic information hidden in trajectories, which per- forms graph convolutional neural networks on a constructed activity graph and (3) *task-specified gates and decoders* to filter out useful latent transition patterns with supervisions by the downstream tasks (i.e., job mobility prediction and an auxiliary task). The results on real-world mobility datasets show the superiority of TJ-MTNet against extensive baselines.
