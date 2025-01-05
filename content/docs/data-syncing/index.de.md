---
title: So synchronisieren Sie Daten  
date: 2024-09-20  
ShowToc: true
copy_mark: src
---

Technisch gesehen unterstützt unsere App keine Synchronisierung von Daten zwischen Geräten. Obwohl Sie die Backup-Funktion nutzen können, um Ihre Daten von einem Gerät auf ein anderes zu übertragen, kann das nicht als Synchronisierung bezeichnet werden.

Das heißt, es gibt dennoch einige Möglichkeiten, um eine Synchronisierung außerhalb der App durchzuführen.

# Legen Sie einen Speicherordner als App-Heimatordner fest

Sie können einen Ordner im Speicher Ihres Geräts als Heimatordner der App festlegen. In diesem Fall werden Ihre Bücher und Kapitel als Unterordner und Textdateien in diesem Speicherordner gespeichert.

Da sie bereits als Dateien gespeichert sind, können Sie externe Tools zur Dateisynchronisierung verwenden, um diese Daten zwischen Geräten zu synchronisieren.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing ist ein weit verbreitetes plattformübergreifendes Tool zur Datensynchronisierung. Sie können es verwenden, um die Daten Ihrer App zwischen Ihren mobilen Geräten, Ihrem PC, Laptop oder Heimserver zu synchronisieren.

Schauen Sie sich die offizielle Anleitung von Syncthing an, um zu erfahren, wie Sie es einrichten:

[Syncthing - Erste Schritte](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Netzlaufwerke

Einige Netzlaufwerke bieten eine Funktion zur bidirektionalen Dateisynchronisierung. Wenn Sie den Heimatordner der App als Synchronisierungsordner festlegen, können Sie Daten zwischen Geräten synchronisieren und gleichzeitig das Netzlaufwerk als Backup nutzen.

# Git, SVN und Rsync

Für diejenigen mit Programmierkenntnissen ist dies der empfohlene Weg. Mit Apps wie Termux können Sie Befehlszeilentools verwenden, um Ihre Daten zu synchronisieren.

Wenn Sie mit Git, SVN oder Rsync vertraut sind, bietet diese Option große Flexibilität. Wenn nicht, empfehlen wir diese Methode nicht, da sie technisches Wissen erfordert und nicht für normale Benutzer gedacht ist.

# Zusammenfassung

Das Hauptziel der App ist es, die Daten der Benutzer sicher zu halten. Da die Synchronisierung von Daten zwischen zwei Client-Apps nicht immer sicher ist, haben wir uns entschieden, keine integrierte Synchronisierungsfunktion zu entwickeln. Stattdessen empfehlen wir die Verwendung zuverlässiger, professioneller Tools zur Datensynchronisierung.
