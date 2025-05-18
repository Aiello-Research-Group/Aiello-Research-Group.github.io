---
layout: page
title: Research Topics
permalink: /research/
description: Aiello Research Group's main research topics.
nav: true
nav_order: 2
display_categories:
horizontal: false
---

<div class="research-topics">
  {% if site.enable_project_categories and page.display_categories %}
    {% for category in page.display_categories %}
      <a id="{{ category }}" href=".#{{ category }}">
        <h2 class="category">{{ category }}</h2>
      </a>
      {% assign categorized_projects = site.projects | where: "category", category %}
      {% assign sorted_projects = categorized_projects | sort: "importance" %}

      <div class="topics-grid">
        {% for project in sorted_projects %}
          <div class="topic-card">
            <div class="image-wrapper">
              <img src="{{ project.image | prepend: '/' | relative_url }}" alt="{{ project.title }} image">
            </div>
            <div class="card-body">
              <h3>{{ project.title }}</h3>
              <p>{{ project.description }}</p>
              <a class="read-more" href="{{ project.url | relative_url }}">Read more</a>
            </div>
          </div>
        {% endfor %}
      </div>
    {% endfor %}
  {% else %}
    {% assign sorted_projects = site.projects | sort: "importance" %}

    <div class="topics-grid">
      {% for project in sorted_projects %}
        <div class="topic-card">
          <div class="image-wrapper">
            <img src="{{ project.image | prepend: '/' | relative_url }}" alt="{{ project.title }} image">
          </div>
          <div class="card-body">
            <h3>{{ project.title }}</h3>
            <p>{{ project.description }}</p>
            <a class="read-more" href="{{ project.url | relative_url }}">Read more</a>
          </div>
        </div>
      {% endfor %}
    </div>
  {% endif %}
</div>