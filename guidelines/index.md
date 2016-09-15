---
layout: template1
title: Metadata Input Guidelines
comments: false
---

# Descriptive Metadata Input Guidelines

## DPTF
{% for field in site.data.order.dptf %}
  {% assign element = site.data.dptf[field] %}
  * [{{ element.label }}]({{ site.url }}/guidelines/{{ element.name }})
{% endfor %}

## DAMSTF
{% for field in site.data.order.damstf %}
  {% assign element = site.data.damstf[field] %}
  * [{{ element.label }}]({{ site.url }}/guidelines/{{ element.name }})
{% endfor %}
