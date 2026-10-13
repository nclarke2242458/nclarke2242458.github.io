---
title: Blog
layout: page-narrow
permalink: /blog.html
---
# Blog

{% assign posts = site.essay | where: "part", "Blog" | sort: "order" %}
{% for p in posts -%}
- [{{ p.title }}]({{ p.url | relative_url }})
{% endfor %}
