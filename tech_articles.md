---
layout: page
title: Technical Articles
permalink: /tech_articles/
---

# Technical Articles

Welcome to my collection of technical articles. Here, I dive deep into various topics related to software development, programming languages, and technology trends.

{% for article in site.tech_articles %}
## [{{ article.title }}]({{ article.url | relative_url }})

{{ article.excerpt | strip_html | truncatewords: 50 }}

[Read more]({{ article.url | relative_url }})

---
{% endfor %}

Stay tuned for more articles coming soon!