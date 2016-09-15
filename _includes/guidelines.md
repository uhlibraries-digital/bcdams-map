{% if page.set == "dptf" %}
	{% assign element = site.data.dptf[page.data] %}
{% else %}
	{% assign element = site.data.damstf[page.data] %}
{% endif %}

# Input Guidelines: {{ element.label }}
<{{ element.uri }}>

---
