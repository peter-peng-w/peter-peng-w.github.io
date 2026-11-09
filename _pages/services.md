---
layout: archive
title: "Services"
permalink: /services/
author_profile: true
redirect_from:
  - /services
# Add published PDF files here to show links on the guest lecture.
# Each entry takes a title and a local URL, such as /files/lecture-slides.pdf.
guest_lecture_slides: []
---

{% include base_path %}

<div class="services-page">
  <section class="service-section" aria-labelledby="teaching-heading">
    <header class="service-section__header">
      <h2 id="teaching-heading">Teaching</h2>
      <p class="service-institution">University of Virginia</p>
    </header>

    <h3 class="service-role">Graduate Teaching Assistant</h3>
    <ul class="service-courses" role="list">
      <li class="service-course">
        <div class="service-course__copy">
          <span class="service-course__code">CS 4774</span>
          <h4>Machine Learning</h4>
        </div>
        <div class="service-terms">
          <span class="service-term service-term--fall">Fall 2026</span>
          <span class="service-term service-term--spring">Spring 2026</span>
        </div>
      </li>
      <li class="service-course">
        <div class="service-course__copy">
          <span class="service-course__code">CS 6501</span>
          <h4>Natural Language Processing</h4>
        </div>
        <div class="service-terms">
          <span class="service-term service-term--spring">Spring 2025</span>
        </div>
      </li>
      <li class="service-course">
        <div class="service-course__copy">
          <span class="service-course__code">CS 6762</span>
          <h4>Signal Processing, Machine Learning and Control</h4>
        </div>
        <div class="service-terms">
          <span class="service-term service-term--fall">Fall 2024</span>
        </div>
      </li>
    </ul>

    <h3 class="service-role">Guest Lecturer</h3>
    <ul class="service-courses" role="list">
      <li class="service-course">
        <div class="service-course__copy">
          <span class="service-course__code">ECE 6501</span>
          <h4>Reinforcement Learning and LLM</h4>
        </div>
        <div class="service-terms">
          <span class="service-term service-term--fall">Fall 2025</span>
        </div>
        {% if page.guest_lecture_slides.size > 0 %}
        <div class="service-course__resources">
          {% for slides in page.guest_lecture_slides %}
          <a class="service-slides" href="{{ slides.url | relative_url | escape }}">
            <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6M8 13h8M8 17h5"/></svg>
            <span>{{ slides.title | escape }}</span>
            <span class="service-slides__format">PDF</span>
          </a>
          {% endfor %}
        </div>
        {% endif %}
      </li>
    </ul>
  </section>

  <section class="service-section service-section--reviewer" aria-labelledby="reviewer-heading">
    <header class="service-section__header">
      <h2 id="reviewer-heading">Reviewer</h2>
    </header>
    <ul class="service-reviewers" role="list">
      <li>
        <span class="service-reviewers__label">Conference Reviewer</span>
        <span>NeurIPS, ICML, ICLR, AAAI, ACL, NAACL, EMNLP, ACM FAccT</span>
      </li>
      <li>
        <span class="service-reviewers__label">Journal Reviewer</span>
        <span>ACM TIST, IEEE TCCN, TMLR</span>
      </li>
      <li>
        <span class="service-reviewers__label">Awards</span>
        <span>ICML 2026 Gold Reviewer</span>
      </li>
    </ul>
  </section>
</div>
