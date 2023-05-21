---
title: "Introducción hugo"
date: 2023-04-29T15:00:12-05:00
draft: false
description: "Introducción a la increible herramienta  de creación de contenido estatico Hugo."
img: "/img/goHugo.webp"
author: "Luis Pacheco"
keywords:
    - "introducción a hugo,"
    - "desarrollo de contenido estatico,"
    - "Hugo,"
    - "goHugo,"
    - "crear proyecto de hugo"
---
![Introduccion a hugo](/img/goHugo.webp)

# Introduccion a Hugo 
{.title}

Hugo es una poderosa herramienta para la creación de proyectos de proposito general rapido, y facil de usar.
Util para la generación de codigo estatico.
Este esta escrito en lenguaje Go.
{.text-left}
Se caracteriza por ser multiplataforma, disponible  para su uso en Windows, Mac Os y distrubuciones linux como
{.text-left}
- Ubuntu
- Fedora
- OpenSUSE
- Solus
- Arch linux
{.text-left}

Para poder instalar esta maravillosa  herramienta puedes seguir las instrucciones dadas en la pagina oficial de [Hugo](https://gohugo.io/installation/),
ten en cuenta que esta documentacón se en ingles, en ella se encontrará como realizar este proceso para las distintas plataformas.


## Guia de uso.
{.title}
**Crear un nuevo proyecto.**
Para crear un nuevo proyecto debe de ejecutar el siguiente comando:
{.text-left}
>> hugo new site **nombre_de_sitio**
{.code}
Este comando te generará el andamiaje de tu primer sitio con hugo, el cual te creará los siguiente archivos
{.text-left}
![Estrutura del proyecto](/img/estructura_proyecto.png)
Al iniciar a trabajar con hugo podemos hacerlo usando un tema diseñado por  la comunidad, o crear tu propio diseño.
Para generar tu propio diseño puede hacer uso del directorio **layouts** y en ella definir un su interior un subdirectorio llamado **_default**, dentro de este crearemos 3 archivos.
{.text-left}
- baseof.html
    > En el cual se definirá el diseño compartido de todas tus paginas.
- list.html
    > En esta se definirá la vistas de tipo listas, mas adelante explicaremos este tipo de vista.
- single.html
    > En esta se definirá la estructa del contenido individual
{.text-left}



Ademas, en el directorio definiremos un archivo llamado index.html, el cual sera el punto de entrada para nuestro proyecto.
Para el alcanze de este primer post de hugo, editaremos el archivo **layouts/_default/baseof.html**, y añadiremos  el siguiente  codigo:
{.text-left}
> \<!DOCTYPE html>
> \<html>
> \<head>
> \</head>
> \<body>
>    \<div id="content" class="container-fluid">
>       \{\{\- block "main" . \}\}\{\{\- end \}\}
>   \</div>
> \</body>
> \</html>
{.code}

Guardamos y editaremos  el archivo **layouts/index.html**, añadiendo el siguiente codigo.
{.text-left}

> \{\{define "main" .\}\}
>  \<h1>Tu primer proyecto en hugo </h1>
> \{\{end\}\}
{.code}

Ahora para visualizar nuestro proyecto ejecutaremos el siguiente comando:
> hugo server -D
{.code}
Despues de ejecutarlo podemos abrir nuestro navegador y nos diriguiremos a **localhost:1313** y podremos visualizar el contenido que hemos creado.
con esto finalizamos esta primera parte de crear proyectos en hugo.
{.text-left}
En la proxima entrada crearemos contenidos para vistas de tipo list y single.
{.text-left}
