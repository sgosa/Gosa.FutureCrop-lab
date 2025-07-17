---
layout: page
title: Blog
permalink: /blog/
---

## Blog

Welcome to my blog where I share thoughts on research, science, technology, and the future of agriculture.

---

### 📌 Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}
