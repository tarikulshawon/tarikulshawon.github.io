---
permalink: /
title: "Tarikul Islam"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Welcome—I'm Tarikul Islam, a Lead Engineer at Samsung R&D Institute Bangladesh. I build AI-driven mobile and IoT products and collaborate on research that connects data, people, and impactful software.

Focus Areas
======
- Artificial Intelligence and Generative AI
- Large Language Models (LLMs)
- Computer Vision and Natural Language Processing
- Software Engineering for mobile and IoT systems

Currently
======
- Leading the Plant Care Plugin for SmartThings, including SmartThings integration and a standalone Android app
- Integrating Siri voice assistant and AI-driven features into SmartThings
- Mentoring engineers in machine learning and AI upskilling initiatives

News
======
<div class="news-section">
  <ul class="news-list">
    {% for item in site.data.news limit:3 %}
      <li class="news-card">
        <span class="news-date">{{ item.date }}</span>
        <div>
          <div class="news-title">{{ item.title }}</div>
          <div class="news-text">{{ item.detail }}</div>
        </div>
      </li>
    {% endfor %}
  </ul>
  <div class="news-actions">
    <a class="btn btn--primary" href="/news/">Show more</a>
  </div>
</div>

If you'd like to collaborate, feel free to reach out at tarikulcse14@gmail.com.
