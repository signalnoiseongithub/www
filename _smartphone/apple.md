---
layout: page
title: Apple
---

{% assign items = site.data.smartphone.apple.iphone.iphone7 %}
{% for item in items %}
  <p>{{ item.name }}</p>
{% endfor %}
