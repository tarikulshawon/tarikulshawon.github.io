---
layout: single
title: "News"
permalink: /news/
author_profile: true
---

Latest updates and milestones.

<div class="news-section">
  <ul class="news-list">
    {% for item in site.data.news %}
      <li class="news-card">
        <span class="news-date">{{ item.date }}</span>
        <div>
          <div class="news-title">
            {% if item.link %}
              <a href="{{ item.link }}" target="_blank" rel="noopener">{{ item.title }}</a>
            {% else %}
              {{ item.title }}
            {% endif %}
          </div>
          <div class="news-text">{{ item.detail }}</div>
        </div>
      </li>
    {% endfor %}
  </ul>
</div>
