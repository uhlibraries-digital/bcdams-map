{% assign element = site.data.elements[page.data] %}

# {{ element.label }}

__URI:__ <{{ element.uri }}>

__Definition:__ {{ element.definition }}

__Same As:__ <{{ element.same_as_uri }}>

__Obligation:__ {% include obligation_label.md %}

__Repeatable:__ {% if element.repeatable == true %}True{% else %}False{% endif %}

---

## Input Guidelines
