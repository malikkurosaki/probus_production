{% for page in site.pages %}
    <a class=" " href="{{ page.url }}"> {{ page.title }}</a>
{% endfor %}