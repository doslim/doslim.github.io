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

# Research


*Explainable Few-shot Talent Recommendation*, 2023

- Keywords: Talent Recommendation, Few-shot Recommendation, Explainable Machine Learning, Cold-start Problem
- Abstract: Many companies encounter human resource challenges, with high recruitment costs and long hiring cycles being particularly prominent. Numerous studies propose models to expedite the matching of talent with jobs. However, they all overlook the cold-start problem caused by the scarcity of data in the warm-up stage of a new job position. Meanwhile, the interpretability of recommendation is also very important and rarely studied in talent recommendation. Therefore, we focus on solving the cold-start problem in the early stage of recruitment and propose an explainable few-shot talent recommendation model, named EFTR. Specifically, EFTR has a neural topic learning module to map job descriptions and resumes into a shared latent topic space, enabling the recommendation's interpretability. A few-shot learning module is designed to learn jobs' comprehensive representations based on limited information. Experimental results on two real-world datasets demonstrate the superiority of our proposed EFTR over state-of-the-art methods. 

