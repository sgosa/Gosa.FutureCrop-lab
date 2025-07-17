---
layout: page
title: Publications
permalink: /publications/
---

## Selected Publications

{% for pub in site.data.publist %}
- **{{ pub.authors }}** ({{ pub.year }}). *{{ pub.title }}*. _{{ pub.journal }}_.  
  [DOI/Link]({{ pub.url }})
{% endfor %}
