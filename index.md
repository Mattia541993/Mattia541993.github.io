---
myvar: gatto
layout: home
---

{% if page.myvar == "cane" %}
{{ page.myvar }}
{% endif %}

what can I do? bubu

{% render_time %}
page rendered at:
{% endrender_time %}
