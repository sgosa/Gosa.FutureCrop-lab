---
layout: page
title: News
permalink: /news/
---

## Lab News

{% for item in site.data.news %}
- **{{ item.date }}**  
  <span class="{{ item.type }}">{{ item.title }}</span>  
  {{ item.content }}
{% endfor %}
