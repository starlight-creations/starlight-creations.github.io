---
layout: default
title: Rent
permalink: /rent
nav: true
---

{% for package in site.data.rentals %}
{{package.name}} - {{package.description}}
{% endfor %}