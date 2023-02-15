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




![Image](/assets/img/github.png)
![Image](/assets/img/python.png)


