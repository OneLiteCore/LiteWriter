---
ShowToc: true
title: Caracteres no válidos en los nombres de archivo
---

Esta aplicación guarda tus notas, capítulos, novelas y otros contenidos en archivos de texto. Elegimos el texto sin formato para ofrecer compatibilidad amplia y facilitar el uso en distintas plataformas. Así, aunque algún día dejes de usar la aplicación, podrás administrar y editar tus archivos fácilmente con otras aplicaciones y sistemas operativos.

## Caracteres no permitidos en los nombres de archivo: `\/:*?"<>|`

Estos caracteres tienen funciones especiales en los sistemas de archivos y en muchos programas habituales. Por eso, incluirlos en un nombre puede impedir que un archivo se cree, encuentre o abra de forma uniforme en distintos dispositivos. Por ejemplo, `/` separa las carpetas de una ruta, mientras que `\` sirve como separador de rutas en algunos sistemas y como carácter de escape en ciertos formatos de texto. Otros caracteres de este grupo pueden actuar como comodines, delimitadores o símbolos de control. Para que tus archivos sigan siendo fáciles de usar en distintas plataformas, la aplicación no permite estos caracteres en los nombres.

## ¿Por qué un nombre de archivo no puede empezar por `.` o `..`?

Android está basado en el núcleo de Linux. En las rutas de estilo Linux, `.` representa la carpeta actual y `..` representa la carpeta superior. Además, las herramientas de Linux y Android suelen tratar como ocultos los archivos y las carpetas cuyos nombres empiezan por un punto. La aplicación impide comenzar el nombre con un punto para evitar confusiones con estos componentes especiales de las rutas y mantener tus archivos visibles y fáciles de encontrar.
