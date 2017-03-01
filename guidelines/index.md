---
layout: template1
title: Metadata Input Guidelines
comments: false
---

# Metadata Input Guidelines

## Descriptive
{% for field in site.data.order.descriptive %}
  {% assign element = site.data.elements[field] %}
  * [{{ element.label }}]({{ site.url }}/guidelines/{{ element.name }})
{% endfor %}

## Administrative
{% for field in site.data.order.administrative %}
  {% assign element = site.data.elements[field] %}
  * [{{ element.label }}]({{ site.url }}/guidelines/{{ element.name }})
{% endfor %}
