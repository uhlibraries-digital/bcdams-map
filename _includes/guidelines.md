{% assign element = site.data.elements[page.data] %}

# {{ element.label }}

__URI:__ <{{ element.uri }}>

__Definition:__ {{ element.definition }}

{% if element.same_as_uri %}__Same As:__ <{{ element.same_as_uri }}>

{% endif %}__Obligation:__ {% include obligation_label.md %}

__Repeatable:__ {% if element.repeatable == true %}True{% else %}False{% endif %}

__Range:__ {% for r in element.range %}{% if r.uri %}[{{ r.label }}]({{ r.uri }})  {% elsif r.values %}{{ r.label }}:{% for value in r.values %}- {{ value }}{% endfor %}{% else %}{{ r.label }}{% endif %}{% endfor %}

{% for r in element.range %}
	{% if r.uri %}
		<a href="{{ r.uri }}">{{ r.label }}  </a>
	{% elsif r.values %}
		{{ r.label }}:<br>
		<ul>
		{% for value in r.values %}
			<li>{{ value }}</li>
		{% endfor %}
		</ul>
	{% else %}
		{{ r.label }}
	{% endif %}
{% endfor %}

---

## Input Guidelines
