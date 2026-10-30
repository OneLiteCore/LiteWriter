---
ShowToc: true
date: 2024-05-25
title: So verwendest du die Remote-Link-Funktion
---

Mit der Funktion "Link" kannst du App-Daten als ein PC-Verzeichnis einbinden, sodass du deine Daten mit PC-Software bearbeiten und verwalten kannst.

Diese Funktion basiert auf dem allgemeinen **WebDav**-Protokoll. Die meisten Betriebssysteme sollten es von Haus aus unterstützen, aber es ist vielleicht nicht ganz einfach zu bedienen. Hier ist daher ein einfacherer Weg.

## Windows

Auf Windows empfehlen wir dir die Drittanbieter-Software **RaiDrive**. Du kannst sie über den folgenden Link herunterladen:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Version 1.8.0 ist nicht die neueste, aber sie hat alles, was wir brauchen, und was noch wichtiger ist: Sie hat keine Werbung)

Installiere und öffne sie; du siehst möglicherweise ein Panel wie dieses. Folge einfach den Hinweisen:

![RaiDrive setup](/img/add_drive.webp)

1. Klicke oben auf die Schaltfläche "Add", um die Konfiguration aufzurufen.
2. Gehe zum Tab "NAS" und wähle die WebDav-Option
3. Gib den Laufwerksnamen nach Belieben ein
4. Gib die Adresse ein
    - neben dem Text "address" siehst du möglicherweise ein Kontrollkästchen; lass es einfach **NICHT ANGEHAKT**, damit wir eine http-URL verwenden können.
    - Gib die IP-Adresse und die Portnummer ein, die du findest, wenn du die Link-Funktion in der App aktivierst.
5. Gib deinen eigenen Benutzernamen und dein Passwort ein, falls du welche hast; andernfalls aktiviere einfach das Kontrollkästchen "Anonymous"
6. Klicke auf die Schaltfläche "OK", um das Einbinden zu starten

Wenn alles gut läuft, siehst du möglicherweise Folgendes:

![Done](/img/done.webp)

## Linux oder MacOS

### MacOS

Unter macOS kannst du den integrierten **Finder** verwenden, um dich mit dem WebDav-Dienst zu verbinden:

1. Öffne den **Finder**.
2. Klicke in der Menüleiste auf **Go** und wähle **Connect to Server…** (oder drücke `Command + K`).
3. Gib die in der App angezeigte Adresse in das Adressfeld ein, zum Beispiel `http://192.168.1.100:8080`.
4. Klicke auf **Connect**.
5. Gib bei Aufforderung deinen Benutzernamen und dein Passwort ein oder verbinde dich als Gast.
6. Nach der Verbindung erscheint der WebDav-Dienst im Finder als Netzlaufwerk, und du kannst wie in einem lokalen Ordner auf deine Daten zugreifen und sie verwalten.

### Linux

Unter Linux (am Beispiel von Ubuntu Desktop) kannst du den integrierten Dateimanager verwenden, um dich zu verbinden:

1. Öffne die App **Files**.
2. Klicke in der linken Seitenleiste auf **Other Locations**.
3. Suche unten das Feld **Connect to Server**.
4. Gib die Adresse im Format `dav://IP:Port` ein, zum Beispiel `dav://192.168.1.100:8080`.
5. Klicke auf **Connect**.
6. Gib bei Aufforderung deinen Benutzernamen und dein Passwort ein oder verbinde dich anonym.
7. Nach der Verbindung erscheint der WebDav-Dienst im Dateimanager als Netzwerkadresse.
