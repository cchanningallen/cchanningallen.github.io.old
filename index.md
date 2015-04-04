---
layout: page
title: Welcome
---

{% for post in site.posts %}
  <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
