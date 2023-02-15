---
layout: page
title: Netlify
---

**Como configurar Netlify:**

Para configurar Netlify para alojar tu sitio web de GitHub Pages, sigue estos pasos:

1. Inicia sesión en tu cuenta de Netlify y haz clic en el botón "New site from Git" en la página principal.

2. Selecciona GitHub como el proveedor de alojamiento y autoriza a Netlify a acceder a tus repositorios de GitHub.

3. Selecciona el repositorio que contiene tu sitio web de GitHub Pages.

4. En la siguiente pantalla, asegúrate de que el "Branch to deploy" esté configurado en "main" o "master", según el nombre de la rama principal de tu repositorio.

5. En el campo Build command ponemos el comando con el que iniciamos el GithuPages en local.

6. En el campo "Publish directory", ingresa la ruta a la carpeta que contiene tu sitio web compilado. Esta ruta puede variar dependiendo de tu proyecto, pero si estás usando Jekyll, por ejemplo, la carpeta suele llamarse "_site".

7. Por último le damos a Deploy site
En el campo "Build command", ingresa el siguiente comando:

Una vez que tenemos todo esto ya tendríamos nuestro GithubPages subido a Netlify.

![Netlify](https://images2.imgbox.com/ef/03/RHiT6chA_o.jpg)


[Este es el link de mi página en Netlify](https://lorenzopages.netlify.app/)