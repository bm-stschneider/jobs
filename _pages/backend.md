---
title: "Backend Jobs"
permalink: /backend/
author: funke
author_profile: true
---

{% for item in site.backend %}
  <h3><a href="{{ item.url | absolute_url }}">{{ item.title }}</a></h3>
  <p>{{ item.excerpt }}</p>
{% endfor %}