---
title: "Introduccion_hugo"
date: 2023-04-29T15:00:12-05:00
draft: false
---
![Introduccion a hugo](/img/goHugo.webp)

## Introduccion a Hugo 
{.title}

Hugo es una herramienta de generación de sitios web estáticos de alto rendimiento que utiliza archivos de texto plano para crear páginas web. Es conocido por ser rápido y fácil de usar, lo que lo convierte en una opción popular para desarrolladores y diseñadores que buscan una forma eficiente de construir y mantener sitios web estáticos. Hugo utiliza la sintaxis Markdown para escribir contenido y plantillas personalizables para el diseño y la estructura de las páginas. Además, ofrece una amplia gama de funciones y características que lo hacen flexible y escalable para proyectos de cualquier tamaño y complejidad. 
{.text-left }

A continuación describiremos el proceso de creación de tu primera página web haciendo uso de esta herramienta.


**Windows**
{#windows .text-left}
**Requisitos**
{.text-left}
* Tener instalado Chocolatey (un gestor de paquetes para Windows).
{.text-left}
* Tener acceso a una línea de comando (cmd o PowerShell)
{.text-left}

1. Comando a ejecutar:
{.text-left}

>choco install hugo -confirm
{.code}

2. Creación del primer proyecto:
Para crear un nuevo proyecto en Hugo, debes seguir los siguientes pasos:
Abre la línea de comando y dirígete a la ubicación donde deseas crear tu nuevo proyecto. Ejecuta el siguiente comando para crear un nuevo sitio Hugo
{.text-left}
 >hugo new site nombre-del-sitio
{.code}
Luego, ejecuta el siguiente comando para crear tu primer contenido:
{.text-left}
>hugo new posts/mi-primer-post.md
{.code}



**MacOs**
{#MacOs .text-left}
**Requisitos**
{.text-left}

* Tener instalado Homebrew (un gestor de paquetes para MacOS)
* Tener acceso a una línea de comando (Terminal)
{.text-left}

Para crear un nuevo proyecto en Hugo, debes seguir los siguientes pasos:
{.text-left}

1. Abre Terminal y dirígete a la ubicación donde deseas crear tu nuevo proyecto. Ejecuta el siguiente comando para crear un nuevo sitio Hugo:
{.text-left}
>brew install hugo
{.code}
2. Creación del primer proyecto:
Para crear un nuevo proyecto en Hugo, debes seguir los siguientes pasos:
Abre Terminal y dirígete a la ubicación donde deseas crear tu nuevo proyecto. Ejecuta el siguiente comando para crear un nuevo sitio Hugo:
{.text-left}
>hugo new site nombre-del-sitio
{.code}
3. Luego, ejecuta el siguiente comando para crear tu primer contenido:
{.text-left}
>hugo new posts/mi-primer-post.md
{.code}


**Ubuntu**
{#ubuntu .text-left}
**Requisitos**
{.text-left}
1. Abre Terminal y ejecuta el siguiente comando para instalar Hugo:
{.text-left}
>sudo apt-get update
>sudo apt-get install hugo
{.code}
2. Creación del primer proyecto:
{.text-left}
Para crear un nuevo proyecto en Hugo, debes seguir los siguientes pasos:
Abre Terminal y dirígete a la ubicación donde deseas crear tu nuevo proyecto. Ejecuta el siguiente comando para crear un nuevo sitio Hugo:
{.text-left}
>hugo new site nombre-del-sitio
{.code}
Luego, ejecuta el siguiente comando para crear tu primer contenido:
{.text-left}
>hugo new posts/mi-primer-post.md
{.code}


**Probar tu sitio**
Para probar tu sitio, tienes que ejecutar el siguiente comando,el cual inicia un servidor web local que puedes acceder en tu navegador web en la dirección [http://localhost:1313/.](http://localhost:1313/.)
{.text-left}

Este lanzar un servidor de prueba, el cual a medida que realices cambios en el archivo "mi-primer-post.md" se visualizará  automáticamente.
{.text-left}

**En el siguiente post aprenderemos a generar platillas y personalizar el contenido de nuestra pagina**
{.text-center}

