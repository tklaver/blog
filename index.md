---
layout: page
title: "Toms blog"
---

# Toms blog

{% for post in site.posts %}
  <h2>[{{ post.title }}]({{ post.url }})</h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
{% endfor %}
