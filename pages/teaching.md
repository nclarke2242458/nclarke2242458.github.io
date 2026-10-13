---
title: Teaching
layout: page-narrow
permalink: /teaching.html
---
# Teaching

{% assign posts = site.essay | where: "part", "Teaching" | sort: "order" %}
{% for p in posts -%}
- [{{ p.title }}]({{ p.url | relative_url }})
{% endfor %}
