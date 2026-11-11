---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
page_class: primary-page
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

## Conference Papers
- **[NeurIPS'26]** Skill-Coupled Policy Optimization with Calibrated Group-Wise Advantage Estimation  
  <span class="page-detail" markdown="span">**Peng Wang**, Zhendong Chu, Chengshuai Shi, Matthias Poloczek, Cong Shen, Jing Yang</span>
- **[NeurIPS'26 Workshop: Towards Test-Time Continual Learning Agents]** Is One Score Enough? Rethinking the Evaluation of Sequentially Evolving LLM Memory [[arXiv]](https://arxiv.org/abs/2605.15384)  
  <span class="page-detail" markdown="span">Songwei Dong\*, Zihan Chen\*, Chengshuai Shi, **Peng Wang**, Jundong Li, Cong Shen</span>
- **[EMNLP'26 Main]** The Past Is Prologue: A Plug-in Controller for Selective Updates in Sequentially Evolving LLM Memory [[Paper]](https://aclanthology.org/2026.emnlp-main.677/)  
  <span class="page-detail" markdown="span">Zihan Chen, Songwei Dong, Chengshuai Shi, **Peng Wang**, Song Wang, Cong Shen, Jundong Li</span>
- **[ICLR'26]** Reward Is Enough: LLMs Are In-Context Reinforcement Learners [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2026/hash/b7511dfe2e7a1fa45e093cc75389abc2-Abstract-Conference.html)  
  <span class="page-detail" markdown="span">Kefan Song\*, Amir Moeini\*, **Peng Wang**, Lei Gong, Rohan Chandra, Shangtong Zhang, Yanjun Qi</span>
- **[EMNLP'25 Main]** Separate the Wheat from the Chaff: Winnowing Down Divergent Views in Retrieval Augmented Generation [[Paper]](https://aclanthology.org/2025.emnlp-main.587/)  
  <span class="page-detail" markdown="span">Song Wang, Zihan Chen, **Peng Wang**, Zhepei Wei, Zhen Tan, Yu Meng, Cong Shen, Jundong Li</span>
- **[EMNLP'25 Findings]** InfAL: Inference Time Adversarial Learning for Improving Research Ideation [[Paper]](https://aclanthology.org/2025.findings-emnlp.667/)  
  <span class="page-detail" markdown="span">Sikun Guo, Amir Hassan Shariatmadari, **Peng Wang**, Albert Huang, Aidong Zhang</span>
- **[AISTATS'25]** A Shared Low-Rank Adaptation Approach to Personalized RLHF [[arXiv]](https://arxiv.org/abs/2503.19201)  
  <span class="page-detail" markdown="span">Renpu Liu, **Peng Wang**, Donghao Li, Cong Shen, Jing Yang</span>
- **[ICLR'25 <span style="color: red;">Spotlight</span>]** CEB: Compositional Evaluation Benchmark for Fairness in Large Language Models [[arXiv]](https://arxiv.org/abs/2407.02408)  
  <span class="page-detail" markdown="span">Song Wang\*, **Peng Wang\***, Tong Zhou, Yushun Dong, Zhen Tan, Jundong Li</span>

- **[SoLaR@NeurIPS'24 Spotlight]** On Demonstration Selection for Improving Fairness in Language Models [[Paper]](https://openreview.net/forum?id=V9PCoMqqdO)  
  <span class="page-detail" markdown="span">Song Wang, **Peng Wang**, Yushun Dong, Tong Zhou, Lu Cheng, Yangfeng Ji, Jundong Li</span>

- **[TheWebConf'22]** Graph-based Extractive Explainer for Recommendations [[arXiv]](https://arxiv.org/abs/2202.09730)  
  <span class="page-detail" markdown="span">**Peng Wang\***, Renqin Cai\*, Hongning Wang</span>

## Journal Papers
- **[ACM SIGKDD Explorations'26]** A Survey of Scaling in Large Language Model Reasoning [[arXiv]](https://arxiv.org/abs/2504.02181)  
  <span class="page-detail" markdown="span">Zihan Chen, Song Wang, Zhen Tan, Xingbo Fu, Zhenyu Lei, **Peng Wang**, Huan Liu, Cong Shen, Jundong Li</span>
- **[JMIR]** Recruitment Challenges and Strategies in a Technology-Based Intervention for Dementia Caregivers: Descriptive Study [[Paper]](https://formative.jmir.org/2025/1/e59291/)  
  <span class="page-detail" markdown="span">Eunjung Ko, Ye Gao, **Peng Wang**, Lahiru Wijayasingha, Kathy D Wright, Kristina C Gordon, Hongning Wang, John A Stankovic, Karen M Rose</span>



