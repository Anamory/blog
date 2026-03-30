---
layout: page
title: Math
permalink: /math/
---

# Math Posts

<ul>
{% for post in site.categories.math %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
