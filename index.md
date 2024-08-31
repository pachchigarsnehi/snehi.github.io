---
layout: home
title: Welcome
---

# Welcome to My Personal Website

Hello! I'm Snehi, and this is my personal corner of the internet. Here, you'll find my thoughts, essays, technical articles, and more.

## Recent Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all posts]({{ '/blog' | relative_url }})

## Featured Essays

{% for essay in site.essays limit:2 %}
- [{{ essay.title }}]({{ essay.url | relative_url }})
{% endfor %}

[View all essays]({{ '/essays' | relative_url }})

## Latest Technical Articles

{% for article in site.tech_articles limit:2 %}
- [{{ article.title }}]({{ article.url | relative_url }})
{% endfor %}

[View all technical articles]({{ '/tech_articles' | relative_url }})