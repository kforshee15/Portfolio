---
layout: home
---

# Welcome to My Portfolio

Hello! I'm a graphic designer showcasing my work and creative projects.

## Featured Work

Explore my portfolio projects below. Each piece represents my passion for design and attention to detail.

{% for item in site.portfolio %}
  <div class="portfolio-preview">
    <h3>{{ item.title }}</h3>
    <p>{{ item.excerpt }}</p>
    <a href="{{ item.url }}">View Project</a>
  </div>
{% endfor %}
