{% if page.set == "dptf" %}
	{% assign element = site.data.dptf[page.data] %}
{% else %}
	{% assign element = site.data.damstf[page.data] %}
{% endif %}

# {{ element.label }}

__URI:__ <{{ element.uri }}>

__Definition:__ {{ element.definition }}

__Same As:__ <{{ element.same_as }}>

__Obligation:__ {% include obligation_label.md %}

__Repeatable:__ {% if element.repeatable == "true" %}True{% else %}False{% endif %}

---

## Input Guidelines
