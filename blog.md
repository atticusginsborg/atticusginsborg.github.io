---
title: Blog
permalink: /blog
---

{% for post in site.posts %}
{% include posts-list-item.html %}
{% endfor %}
