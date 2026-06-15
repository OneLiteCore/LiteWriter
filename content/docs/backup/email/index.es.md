---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Servicio de copia de seguridad por correo electrónico
---

El servicio de copia de seguridad por correo electrónico usa tu propia cuenta de correo para enviar archivos de copia como adjuntos a tu propio buzón. Esto mantiene los archivos de copia dentro de una cuenta de correo que ya controlas, lo que te da más privacidad y plena propiedad sobre tus datos de copia de seguridad.

Nos importa mucho tu privacidad. La aplicación nunca subirá tu dirección de correo electrónico y nunca hará un uso indebido, recopilará ni robará tu contraseña.

# Por qué necesitas una contraseña de aplicación en lugar de la contraseña de tu correo

La mayoría de los proveedores de correo no permiten que las aplicaciones de terceros inicien sesión con la contraseña normal de tu correo electrónico. Esta es una política de seguridad común que ayuda a reducir el riesgo de filtraciones de contraseñas y abuso de cuentas.

Por eso, normalmente tendrás que crear una contraseña de aplicación de terceros o una contraseña específica para cliente en la configuración de tu cuenta de correo, y luego usar esa contraseña en la aplicación en lugar de tu contraseña normal.

# Documentos de ayuda de proveedores de correo comunes

- Documento de ayuda de Gmail: https://support.google.com/mail/answer/185833
- Documento de ayuda de QQ Mail: https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode

# Cómo entender los parámetros de inicio de sesión

- **Dirección del servidor IMAP**: El servidor que se usa para recibir y leer correos electrónicos.
- **Puerto IMAP**: El puerto de red que usa IMAP. El puerto IMAP predeterminado suele ser **993**.
- **Dirección del servidor SMTP**: El servidor que se usa para enviar correos electrónicos.
- **Puerto SMTP**: El puerto de red que usa SMTP. El puerto SMTP predeterminado suele ser **465** o **587**.
- **STARTTLS**: Una función de seguridad que actualiza una conexión simple a una conexión TLS cifrada después de que la conexión comienza. Si el puerto SMTP se establece en **587**, la aplicación habilitará y exigirá **STARTTLS** de forma predeterminada.
- **Dirección de correo electrónico**: La cuenta de correo que envía el correo de copia de seguridad y también lo recibe.
- **Contraseña de aplicación de terceros**: Una contraseña generada por tu proveedor de correo para aplicaciones externas. En la mayoría de los casos, no puedes usar aquí la contraseña normal de tu correo, porque los proveedores suelen bloquear el inicio de sesión directo con contraseña para aplicaciones de terceros por razones de seguridad.
