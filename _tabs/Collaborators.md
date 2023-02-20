---
layout: page
title: Collaborators
icon: fas fa-code	
---

**Colaradores de la página** 


<table>
  <tr>
    <th>Nombre</th>
    <th>Formacion</th>
    <th>Edad</th>
  </tr>
{% for persona in site.data.personas %}
  <tr> <td>{{ persona.nombre }} </td>
  <td> {{ persona.formacion }} </td> 
  <td>{{persona.edad}} </td> 
  </tr>
{% endfor %}

</table>


 **Como he hecho esto** 

 He creado un .json en _data con los nombres de los colaboradores.
 Después lo he puesto con liquid de esta manera para que se vea en mi GithubPages.

![tabla](https://images2.imgbox.com/c6/82/O42Co1qT_o.jpg)