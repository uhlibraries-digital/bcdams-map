{% if element.obligation == "required" %}Required
{% elsif element.obligation == "requiredWhenAvailable" %}Required When Available
{% elsif element.obligation == "stronglyRecommended" %}Strongly Recommended
{% elsif element.obligation == "recommended" %}Recommended
{% else %}Optional{% endif %}
