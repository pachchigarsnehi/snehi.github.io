---
layout: page
title: Pictures
permalink: /pictures/
---

# My Photo Gallery

Welcome to my photo gallery! Here, I share snapshots of my life, travels, and memorable moments.

{% for i in (1..6) %}
<div style="display: inline-block; margin: 10px; text-align: center;">
  <img src="/api/placeholder/300/200" alt="Placeholder Image {{ i }}" style="width: 300px; height: 200px; object-fit: cover;">
  <p>Caption for Image {{ i }}</p>
</div>
{% endfor %}

<script>
  // You can replace this with actual JavaScript to load and display your images
  console.log("Future enhancement: Add JavaScript to load and display actual images");
</script>

## About This Gallery

This gallery is a work in progress. In the future, I plan to add more features like:
- Categorized albums
- Lightbox for full-size image viewing
- Description and date for each photo
- And more!

Check back soon for updates and new photos!