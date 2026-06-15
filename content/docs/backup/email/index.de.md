---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: E-Mail-Backup-Dienst
---

Der E-Mail-Backup-Dienst verwendet dein eigenes E-Mail-Konto, um Backup-Dateien als Anhänge an dein eigenes Postfach zu senden. Dadurch bleiben die Backup-Dateien in einem E-Mail-Konto, das du bereits selbst kontrollierst, was dir mehr Privatsphäre und die volle Kontrolle über deine Backup-Daten gibt.

Deine Privatsphäre ist uns sehr wichtig. Die App wird deine E-Mail-Adresse niemals hochladen und dein Passwort niemals missbrauchen, sammeln oder stehlen.

# Warum du ein App-Passwort statt deines E-Mail-Passworts brauchst

Die meisten E-Mail-Anbieter erlauben es Drittanbieter-Apps nicht, sich mit deinem normalen E-Mail-Passwort anzumelden. Das ist eine gängige Sicherheitsrichtlinie, die hilft, das Risiko von Passwortlecks und Kontomissbrauch zu verringern.

Deshalb musst du in den Einstellungen deines E-Mail-Kontos normalerweise ein App-Passwort oder ein clientspezifisches Passwort erstellen und dieses dann in der App anstelle deines normalen E-Mail-Passworts verwenden.

# Hilfedokumente für gängige E-Mail-Anbieter

- Gmail-Hilfedokument: https://support.google.com/mail/answer/185833
- QQ-Mail-Hilfedokument: https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode

# Die Anmeldeparameter verstehen

- **IMAP-Serveradresse**: Der Server, der zum Empfangen und Lesen von E-Mails verwendet wird.
- **IMAP-Port**: Der Netzwerkport, der von IMAP verwendet wird. Der Standardport für IMAP ist normalerweise **993**.
- **SMTP-Serveradresse**: Der Server, der zum Senden von E-Mails verwendet wird.
- **SMTP-Port**: Der Netzwerkport, der von SMTP verwendet wird. Der Standardport für SMTP ist normalerweise **465** oder **587**.
- **STARTTLS**: Eine Sicherheitsfunktion, die eine unverschlüsselte Verbindung nach dem Verbindungsaufbau auf eine verschlüsselte TLS-Verbindung umstellt. Wenn der SMTP-Port auf **587** gesetzt ist, aktiviert die App **STARTTLS** standardmäßig und verlangt dessen Verwendung.
- **E-Mail-Adresse**: Das E-Mail-Konto, das die Backup-E-Mail sendet und sie auch empfängt.
- **App-Passwort eines Drittanbieters**: Ein Passwort, das dein E-Mail-Anbieter für externe Apps erstellt. In den meisten Fällen kannst du hier nicht dein normales E-Mail-Passwort verwenden, weil Anbieter aus Sicherheitsgründen die direkte Passwortanmeldung für Drittanbieter-Apps normalerweise blockieren.
