---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->

### Conference Papers
- **[AISTATS'25]** A Shared Low-Rank Adaptation Approach to Personalized RLHF  
  Renpu Liu, **Peng Wang**, Donghao Li, Cong Shen, Jing Yang
- **[ICLR'25 <span style="color: red;">Spotlight</span>]** CEB: Compositional Evaluation Benchmark for Fairness in Large Language Models [[arXiv]](https://arxiv.org/abs/2407.02408)  
  Song Wang\*, **Peng Wang\***, Tong Zhou, Yushun Dong, Zhen Tan, Jundong Li 

- **[SoLaR@NeurIPS'24 Spotlight]** On Demonstration Selection for Improving Fairness in Language Models  
  Song Wang, **Peng Wang**, Yushun Dong, Tong Zhou, Lu Cheng, Yangfeng Ji, Jundong Li

- **[TheWebConf'22]** Graph-based Extractive Explainer for Recommendations [[arXiv]](https://arxiv.org/abs/2202.09730)  
  **Peng Wang\***, Renqin Cai\*, Hongning Wang

### Journal Papers
- **[JMIR]** Recruitment Challenges and Strategies in a Technology-Based Intervention for Dementia Caregivers: Descriptive Study  
  Eunjung Ko, Ye Gao, **Peng Wang**, Lahiru Wijayasingha, Kathy D Wright, Kristina C Gordon, Hongning Wang, John A Stankovic, Karen M Rose



