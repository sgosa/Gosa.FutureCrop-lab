---
layout: page
title: People
permalink: /people/
---

## Our Team

{% for member in site.data.team %}
### {{ member.name }}
**Role:** {{ member.position }}  
**Email:** {{ member.email }}  
{{ member.bio }}
{% endfor %}
