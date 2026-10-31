---
ShowToc: true
date: 2026-10-31
title: Servicio de copia de seguridad Samba
---

Samba es un protocolo universal para compartir archivos dentro de una red de área local (LAN) y funciona bien con una amplia variedad de dispositivos y sistemas.

# Comprender los parámetros de inicio de sesión

- **Nombre de host o dirección IP**: La dirección del dispositivo que ejecuta el servidor Samba.
- **Puerto**: El puerto del servidor Samba. El valor predeterminado es **445**.
- **Nombre del recurso compartido de Samba**: Un servidor Samba puede tener varias configuraciones de recursos compartidos, así que debes indicar cuál quieres usar.
- **Ruta de la carpeta de almacenamiento**: La ruta de almacenamiento dentro del recurso compartido. Puede quedar vacía. Las copias de seguridad se guardan en esta ruta; si está vacía, se usa el directorio raíz del recurso compartido.
- **Nombre de usuario**: El nombre de usuario, que no puede estar vacío.
- **Contraseña**: La contraseña, que no puede estar vacía.
- **SSID de WiFi restringido**: Limita la copia de seguridad a una red WiFi concreta. Déjalo vacío para permitir copias en cualquier WiFi, o introduce un SSID para que solo se ejecute en esa red. Como Samba se usa para compartir archivos en una red local, esto mantiene tus copias en un WiFi de confianza.
