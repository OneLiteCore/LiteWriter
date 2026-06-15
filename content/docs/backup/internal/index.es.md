---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

La aplicación ofrece un mecanismo de copia de seguridad interna que comprime periódicamente los datos de tus capítulos en un archivo .zip.

# Los archivos de copia de seguridad interna se perderán si desinstalas la aplicación

El mecanismo integrado guarda los archivos de copia de seguridad .zip en una carpeta privada de la aplicación. Esta carpeta, junto con los demás datos de la aplicación, se eliminará si desinstalas la aplicación.

Por eso, no dependas únicamente de este mecanismo para mantener tus datos seguros. No está diseñado para ser tu único método de copia de seguridad.

# Cómo funciona

Cuando sales de la aplicación, o a la hora programada de cada día, la aplicación comprueba si hay cambios que todavía no se han respaldado. Si los hay, se activa el proceso de copia de seguridad. De forma predeterminada, hay un intervalo de al menos 8 horas entre procesos de copia de seguridad.

Después de crear un nuevo archivo zip, la aplicación comprueba si hay datos de copia antiguos y los elimina si es necesario. De forma predeterminada, la aplicación conserva los 20 archivos de copia de seguridad más recientes, por lo que no tienes que preocuparte de que las copias ocupen demasiado espacio de almacenamiento.

Si has configurado otros servicios de copia de seguridad, como Google Drive o la copia del almacenamiento del dispositivo, el archivo zip más reciente también se subirá allí.
