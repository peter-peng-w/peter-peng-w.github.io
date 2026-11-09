---
layout: archive
title: "Services"
permalink: /services/
author_profile: true
page_class: primary-page
redirect_from:
  - /services
# Add published PDFs for the Fall 2025 ECE 6501 guest lecture here.
# Each entry takes a title and a local URL, such as /files/lecture-slides.pdf.
guest_lecture_slides: []
---

{% include base_path %}

<div class="services-page">
  <section class="service-section" aria-labelledby="teaching-heading">
    <h2 id="teaching-heading">Teaching</h2>
    <p class="page-detail">University of Virginia</p>

    <h3 class="service-role">Graduate Teaching Assistant</h3>
    <ul class="service-list" role="list">
      <li>
        CS 4774 Machine Learning
        <span class="service-term">· <a href="https://qiyanjun.github.io/2026Fall-UVA-CS-MachineLearningDeep/" aria-label="Fall 2026 CS 4774 Machine Learning course website">Fall 2026</a>, Spring 2026</span>
      </li>
      <li>
        CS 6501 Natural Language Processing
        <span class="service-term">· <a href="https://yumeng5.github.io/teaching/2025-spring-cs6501" aria-label="Spring 2025 CS 6501 Natural Language Processing course website">Spring 2025</a></span>
      </li>
      <li>
        CS 6762 Signal Processing, Machine Learning and Control <span class="service-term">· Fall 2024</span>
      </li>
    </ul>

    <h3 class="service-role">Guest Lecturer</h3>
    <ul class="service-list" role="list">
      <li>
        CS 4774 Machine Learning <span class="service-term">· Fall 2026</span>
        <p class="page-detail service-detail">
          How Are Large Language Models Trained? From next-token prediction to reasoning ·
          <a href="{{ '/files/CS4774_GuestLecture_LLM_NextTokenToReasoning.pdf' | relative_url | escape }}" aria-label="Slides (PDF) for How Are Large Language Models Trained?">Slides (PDF)</a>
        </p>
      </li>
      <li>
        ECE 6501 Reinforcement Learning and LLM <span class="service-term">· Fall 2025</span>
        {% if page.guest_lecture_slides.size > 0 %}
        <p class="page-detail service-detail">
          {% for slides in page.guest_lecture_slides %}
          <a href="{{ slides.url | relative_url | escape }}">{{ slides.title | escape }} (PDF)</a>{% unless forloop.last %} · {% endunless %}
          {% endfor %}
        </p>
        {% endif %}
      </li>
    </ul>
  </section>

  <section class="service-section" aria-labelledby="reviewer-heading">
    <h2 id="reviewer-heading">Reviewer</h2>
    <ul class="service-list" role="list">
      <li>Conference Reviewer · NeurIPS, ICML, ICLR, AAAI, ACL, NAACL, EMNLP, ACM FAccT</li>
      <li>Journal Reviewer · ACM TIST, IEEE TCCN, TMLR</li>
      <li>Awards · ICML 2026 Gold Reviewer</li>
    </ul>
  </section>
</div>
