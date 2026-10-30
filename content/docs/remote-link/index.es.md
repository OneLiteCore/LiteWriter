---
ShowToc: true
date: 2024-05-25
title: Cómo usar la función de enlace remoto
---

La función "Enlace" te permite asignar los datos de la aplicación como un directorio de PC, para que puedas usar software de PC para editar y gestionar tus datos.

Esta función se basa en el protocolo general **WebDav**. La mayoría de los sistemas operativos deberían ser compatibles de forma nativa, pero puede que no sea tan fácil de usar. Así que aquí tienes una forma más sencilla.

## Windows

En la plataforma Windows te recomendamos el software de terceros **RaiDrive**. Puedes descargarlo haciendo clic en el enlace siguiente:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(La versión 1.8.0 no es la más reciente, pero tiene todo lo que necesitamos y, lo que es más importante, no tiene anuncios)

Instálalo y ábrelo; es posible que veas un panel como este, solo sigue las indicaciones:

![RaiDrive setup](/img/add_drive.webp)

1. Haz clic en el botón "Add" de la parte superior para entrar en la configuración.
2. Ve a la pestaña "NAS" y selecciona la opción WebDav
3. Introduce el nombre de la unidad como prefieras
4. Introduce la dirección
    - junto al texto "address" es posible que veas una casilla de verificación; déjala **SIN MARCAR** para poder usar una URL http.
    - Introduce la dirección IP y el número de puerto, que puedes encontrar cuando actives la función de enlace en la aplicación.
5. Introduce tu nombre de usuario y contraseña personalizados si los tienes; de lo contrario, marca la casilla "Anonymous"
6. Haz clic en el botón "OK" para iniciar el mapeo

Si todo va bien, es posible que veas esto:

![Done](/img/done.webp)

## Linux o MacOS

### MacOS

En macOS, puedes usar el **Finder** integrado para conectarte al servicio WebDav:

1. Abre el **Finder**.
2. En la barra de menú, haz clic en **Go** y elige **Connect to Server…** (o pulsa `Command + K`).
3. Introduce en el campo de dirección la dirección que se muestra en la aplicación, por ejemplo `http://192.168.1.100:8080`.
4. Haz clic en **Connect**.
5. Si se te solicita, introduce tu nombre de usuario y contraseña, o conéctate como invitado.
6. Una vez conectado, el servicio WebDav aparecerá en el Finder como una unidad de red, y podrás acceder a tus datos y gestionarlos como una carpeta local.

### Linux

En Linux (tomando como ejemplo el escritorio de Ubuntu), puedes usar el administrador de archivos integrado para conectarte:

1. Abre la aplicación **Files**.
2. Haz clic en **Other Locations** en la barra lateral izquierda.
3. Busca el campo **Connect to Server** en la parte inferior.
4. Introduce la dirección con el formato `dav://IP:puerto`, por ejemplo `dav://192.168.1.100:8080`.
5. Haz clic en **Connect**.
6. Si se te solicita, introduce tu nombre de usuario y contraseña, o conéctate de forma anónima.
7. Una vez conectado, el servicio WebDav aparecerá en el administrador de archivos como una ubicación de red.
