---
layout: page
title: Apple
---

<div>
{% for item_hash in site.data.smartphone.apple.iphone %}
{% assign item = item_hash[0] %}
  <p>{{ item.name }}</p>
{% endfor %}
</div>
