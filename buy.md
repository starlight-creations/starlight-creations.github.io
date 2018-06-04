---
layout: default
title: Buy
permalink: /buy
nav: true
---

{% for product in site.data.products %}
{{product.name}} - {{product.description}}
{% endfor %}