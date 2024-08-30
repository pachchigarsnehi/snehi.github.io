---
layout: page
title: Thoughts
permalink: /thoughts/
---

# My Thoughts

This is where I share short, tweet-style thoughts and ideas. These are brief musings, interesting quotes, or quick observations.

{% for thought in site.data.thoughts limit:10 %}
---
**{{ thought.date | date: "%B %d, %Y" }}**

{{ thought.content }}
{% endfor %}