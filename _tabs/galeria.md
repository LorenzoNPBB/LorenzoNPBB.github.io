---
layout: page
title: Galeria
---

**Imagen Estática**

{% for file in site.static_files %}
    {% if file.image %}
        <img src="{{file.path}}" alt="{file.name}">
    {% endif %}
{% endfor %}