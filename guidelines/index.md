---
layout: template1
title: Metadata Input Guidelines
comments: false
---

# DPTF
{% for field in site.data.order.dptf %}
  {% assign element = site.data.dptf[field] %}
  * [{{ element.label }}](https://{{ site.url }}/guidelines/{{ element.name }})
{% endfor %}
