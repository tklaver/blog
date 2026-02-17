---
layout: page
title: "Toms blog"
---

# Toms blog

{% for post in site.posts %}
  ## [{{ post.title }}]({{ post.url }})
  {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
