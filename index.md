---
myvar: gatto
layout: home
---

{% if page.myvar == "cane" %}
{{ page.myvar }}
{% endif %}

{% render_time %}
page rendered at:
{% endrender_time %}
