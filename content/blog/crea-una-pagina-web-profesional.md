---
title: "Crea una pagina web profesional"
---
![Crear una página web profesional](../../images/blog-1.jpg)
Hugo es el framework más rápido para construir sitios web. Te recomiendo seguir estos pasos en el sistema operativo Ubuntu o cualquier otro de linux, si utilizas IOSX o Windows te recomiendo instalar una maquina virutal con cualquier distribución de linux.

**1.- Instalar Hugo.**

Puedes instalar Hugo de manera rápida con la guía que hay en la página oficial de Hugo, tiene una guía para cada sistema operativo. Puedes ir a la página aquí.

**2.- Crear la carpeta raíz desde la terminal.**

Solo necesitas escribir este comando en la terminal:

$ hugo new site nombre_de_la_carpeta_raiz

**3.- Entra a la carpeta raíz**

Te colocas adentro de la carpeta raíz con estos comandos:

$ cd nombre_de_la_carpeta_raiz

**4.- Inicia el server de Hugo**

$ hugo server -D

*5.- Abre tu página en el navegador*

En el navegador escribe localhost:1313 y te parecerá una pantalla en blanco, esa es tu página web.

**6.- Agrega un tema**

Tienes una gran variedad de temas a escoger, en está dirección, [haz click aquí](https://themes.gohugo.io/), vas a encontrar todos los temas de hugo. Hay dos formas de agregar un tema en hugo, la primera sería escogiendo el tema y descargándolo para luego pegar esa carpeta en la subcarpeta themes de la carpeta raíz. Otra forma sería, con git instalado en tu máquina, copias la dirección del tema en GitHub y lo clonas en la carpeta theme con estos comandos:

$ git clone direccion_del_tema_en_github

**7.- Copia el sitio de ejemplo de tu tema**

El sitio de ejemplo del tema viene en la carpeta que se llama example site, copias su contenido y lo pegas en la carpeta raíz sustituyendo todos archivos con nombres iguales.

Si no viene el sitio de ejemplo puedes bajar uno de está dirección, [haz click aquí](https://github.com/gohugoio/hugoBasicExample).

### Conclusión

Hugo es una alternativa muy practica a Wordpress y es muy fácil de utilizar. Traté de resumirlo y hacerlo lo más claro posible, pero si tienes dudas puedes mandarme un correo a rycko.arcr@gmail.com y con gusto te responderé.

**[regresar a la pagina de blog](../../blog)**