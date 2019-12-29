---
layout: page
title: Apple
---

{% for item in site.data.smartphone.apple.iphone.iphone7 %}
  <p>{{ item.name }}</p>
{% endfor %}
