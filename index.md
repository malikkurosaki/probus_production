---
layout: default
description: probus production project release
image: https://i.postimg.cc/WpGym7DV/image.png
---

<h3> List Project </h3>
<div style="display: flex; flex-wrap: wrap; flex-direction: row;">
     <div>
          {% for page in site.pages %}
            {% if page.type == "page" %}
              <a class="button" href="{{ site.url }}{{ page.permalink }}"> {{ page.title }}</a>
            {% endif %}
          {% endfor %}
      </div>
       <!-- {% for post in site.posts %}
                <div style="display: flex; flex-direction: column; width: 150px; height: 150px; border: 4px solid white;">
                    <a style="flex: 1; background-color: rgb(228, 228, 228);" href="{{ site.url }}{{ post.permalink }}">
                        <img style="width: 100%; object-fit: cover;" src="{{ post.image }}" alt="gambar icon">
                    </a>
                    {{ post.title }}
            </div>
        {% endfor %} -->
</div>

