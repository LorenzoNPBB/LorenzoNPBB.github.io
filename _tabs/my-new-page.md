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