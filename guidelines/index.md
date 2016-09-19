---
layout: template1
title: Metadata Input Guidelines
comments: false
---

# Metadata Input Guidelines

## Descriptive
{% for field in site.data.order.descriptive %}
  {% assign element = site.data.elements[field] %}
  * [{{ element.label }}]({{ element.guidelines_uri }})
{% endfor %}

## Administrative
{% for field in site.data.order.administrative %}
  {% assign element = site.data.elements[field] %}
  * [{{ element.label }}]({{ element.guidelines_uri }})
{% endfor %}
