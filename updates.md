---
layout: page
title: "Updates"
permalink: /updates/
---

{% for post in site.posts %}
  <p><a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}</p>
{% endfor %}
