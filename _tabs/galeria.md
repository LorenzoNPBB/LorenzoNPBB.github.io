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



![Image](/assets/img/python.png)

----------------------------
![Image](/assets/img/github.png)



**Como he hecho esto**

He subido las imágenes a mi proyecto en la carpeta assets/img. Después las he llamado con Markdown buscando en la ruta donde están.

![fotos](https://images2.imgbox.com/42/f9/YSlonYRP_o.jpg)