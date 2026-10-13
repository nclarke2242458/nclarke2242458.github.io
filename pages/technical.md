---
title: Technical
layout: page-narrow
permalink: /technical.html
---
# Technical

{% assign posts = site.essay | where: "part", "Technical" | sort: "order" %}
{% for p in posts -%}
- [{{ p.title }}]({{ p.url | relative_url }})
{% endfor %}
