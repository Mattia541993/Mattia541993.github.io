---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
myvar: cane
layout: home
---
{% if page.myvar == "cane" %}
{{ page.myvar }}
{% endif %}

{% render_time %}
page rendered at:
{% endrender_time %}

