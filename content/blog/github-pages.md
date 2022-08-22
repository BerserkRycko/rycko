+++
title = "Hosting en github"
+++
![Crear una página web profesional](../../images/blog-2.jpg)
¿Quieres conseguir hosting gratis y de calidad? Es muy sencillo, a continuación te dejo una guía de como conseguir hosting gratis y construir una página profesional de manera muy rápida y fácil.

Antes que nada dejame aclararte que estos hosting son para sitios web estáticos.

### Sitios web estáticos

Los sitios web estáticos son sitios que son principalmente informativos, no tienen una interacción con el cliente en el momento de la sesión, por lo que este tipo de sitios web son recomendables para tiendas de afiliación, blogs, webs educativas, landing page, páginas para ad sense y lo que puedas imaginar.

### hosting gratis para tu página web con github

#### Crea tu página web estática.

Lo primero es crear tu página web, yo te recomiendo hacerlo con hugo, que es un generador de sitios estáticos y aquí te dejo el enlace, [abrelo aquí](crea-una-pagina-web-profesional), a un artículo donde explico como hacerlo.

#### Subelo a github

**1.-** Debes tener una cuenta en github con cualquier correo la puedes abrir.

**2.-** Crea un nuevo repositorio nuevo, da click en el botón verde que dice new en la sección repositories en el lado derecho de la pantalla.

**3.-** Nombralo con esta nomenclatura (Muy importante). example.github.io

**4.-** Abre tu repositorio y clonalo en tu computadora con el botón verde que dice clone or download, solo dale click y copia la dirección que se te desplega. Después abre una ventana de terminal y escribe:

git clone la-dirección-que-copiaste-en-el-repositorio

**5.-** Copia todos los archivos de tu página estática en el directorio clonado.

**6.-** Subelo por medio de git con estos comandos: git add . git commit -m “puedes nombrarlo como tu quieras” git push origin master

con esto ya debería de estar tu sitio arriba.

### Configura github pages

Haz click, en el repositorio, en la sección configuration en la última pestaña del lado derecho de la sección. Después desplázate hasta la sección que se llama github pages y cambia la sección que dice Source, donde aparecerá un botón que dice none, entonces despliega y escoge master branch o master branch/docs folder y habilita la casilla enforce https. Dale refrescar a la pagina y te aparecerá un mensaje como este:

- Your site is published at https://example.github.io, 
Por último también puedes configurar un dominio propio en la sección custom domain.

Espero que esta información te sea de utilidad para tus proyectos.

**[regresar a la pagina de blog](../../blog)**