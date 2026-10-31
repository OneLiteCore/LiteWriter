---
ShowToc: true
date: 2026-10-31
title: Samba-Backup-Dienst
---

Samba ist ein universelles Dateifreigabeprotokoll für lokale Netzwerke (LAN) und funktioniert mit vielen verschiedenen Geräten und Systemen zuverlässig zusammen.

# Die Anmeldeparameter verstehen

- **Hostname oder IP-Adresse**: Die Adresse des Geräts, auf dem der Samba-Server läuft.
- **Port**: Der Port des Samba-Servers. Der Standardwert ist **445**.
- **Samba-Freigabename**: Ein Samba-Server kann mehrere Freigaben haben, daher musst du angeben, welche Freigabe verwendet werden soll.
- **Speicherordnerpfad**: Der Speicherpfad innerhalb der Freigabe. Er kann leer bleiben. Die Backups werden unter diesem Pfad gespeichert; ist er leer, wird das Stammverzeichnis der Freigabe verwendet.
- **Benutzername**: Der Benutzername, der nicht leer sein darf.
- **Passwort**: Das Passwort, das nicht leer sein darf.
- **Eingeschränkte WiFi-SSID**: Beschränkt die Sicherung auf ein bestimmtes WiFi-Netzwerk. Lass das Feld leer, um Sicherungen in jedem WiFi zuzulassen, oder gib eine SSID ein, damit die Sicherung nur in diesem Netzwerk ausgeführt wird. Samba dient der Dateifreigabe im lokalen Netzwerk – so bleiben deine Backups auf einem vertrauenswürdigen WiFi.
