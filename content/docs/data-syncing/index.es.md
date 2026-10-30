---
title: Cómo sincronizar datos  
date: 2024-09-20  
ShowToc: true
---

Técnicamente, nuestra aplicación no admite la sincronización de datos entre dispositivos. Aunque puedes usar la función de copia de seguridad para transferir tus datos de un dispositivo a otro, no se puede considerar como sincronización.

Dicho esto, todavía hay algunas formas de realizar la sincronización fuera de la aplicación.

# Establecer una carpeta de almacenamiento como la carpeta de inicio de la aplicación

Puedes establecer una carpeta en el almacenamiento de tu dispositivo como la carpeta de inicio de la aplicación. De esta manera, tus libros y capítulos se guardarán como subcarpetas y archivos de texto dentro de esta carpeta.

Dado que ya están almacenados como archivos, puedes utilizar herramientas externas de sincronización de archivos para sincronizar estos datos entre dispositivos.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing es una herramienta de sincronización de datos multiplataforma muy utilizada. Puedes usarla para sincronizar los datos de tu aplicación entre tus dispositivos móviles, PC, portátil o servidor doméstico.

Consulta la guía oficial de Syncthing para aprender a configurarla:

[Syncthing - Primeros pasos](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Discos en red

Algunos discos en red ofrecen una función de sincronización bidireccional de archivos. Si configuras la carpeta de inicio de la aplicación como la carpeta de sincronización, podrás sincronizar los datos entre dispositivos, con el beneficio adicional de usar el disco en red como una copia de seguridad.

# Git, SVN y Rsync

Para aquellos con conocimientos de programación, este método es altamente recomendado. Con aplicaciones como Termux, puedes usar herramientas de línea de comandos para sincronizar tus datos.

Si estás familiarizado con Git, SVN o Rsync, esta opción te ofrece gran flexibilidad. Sin embargo, si no estás familiarizado con estas herramientas, no te recomendamos este método, ya que requieren un conocimiento técnico y no están destinadas a usuarios comunes.

# Resumen

El objetivo principal de la aplicación es mantener los datos de los usuarios seguros. Dado que la sincronización de datos entre dos aplicaciones cliente no siempre es segura, hemos optado por no desarrollar una función de sincronización incorporada. En su lugar, recomendamos el uso de herramientas profesionales y confiables para la sincronización de datos.
