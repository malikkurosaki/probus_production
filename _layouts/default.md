---
title: default
---

{% for page in site.pages %}
    {% if page.type == "menu" %}
        <a class=" " href="{{ page.url }}"> {{ page.title }}</a>
    {% endif %}     
{% endfor %}

{{ content }}

### ini footernya