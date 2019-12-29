---
layout: page
title: Apple
---

{% assign items = site.data.smartphone.apple.iphone %}
{% for item in items %}
  <p>{{ item }}</p>
{% endfor %}
