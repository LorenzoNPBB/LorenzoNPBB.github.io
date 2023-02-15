---
layout: page
title: Galeria
---

**Imagen Estática**

{% for file in site.static_files %}
    {{ file.path}} <br>
{% endfor %}