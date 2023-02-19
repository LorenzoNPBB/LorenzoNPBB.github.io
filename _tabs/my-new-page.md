---
layout: page
title: Colaboradores
icon: fas fa-code	
---

**Colaradores de la página** 

{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}

{% for persona in site.data.personas %}
  ## {{ persona.nombre }} - {{ persona.formacion }} - {{persona.edad}}
{% endfor %}

 **Como he hecho esto** 

 He creado un .json en _data con los nombres de los colaboradores.
 Después lo he puesto con liquid de esta manera para que se vea en mi GithubPages.

![tabla](https://images2.imgbox.com/c6/82/O42Co1qT_o.jpg)