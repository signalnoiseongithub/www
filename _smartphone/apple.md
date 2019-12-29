---
layout: page
title: Apple
---

{% for item site.data.smartphone.apple.iphone.iphone7 %}
  <p>{{ item.name }}</p>
{% endfor %}
