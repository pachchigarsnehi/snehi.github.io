---
layout: page
title: Essays
permalink: /essays/
---

# My Essays

Here you'll find a collection of my essays on various topics.

{% for essay in site.essays %}
  <h2><a href="{{ essay.url | relative_url }}">{{ essay.title }}</a></h2>
  <p>{{ essay.excerpt }}</p>
{% endfor %}