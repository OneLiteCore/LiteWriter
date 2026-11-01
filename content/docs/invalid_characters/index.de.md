---
ShowToc: true
title: Ungültige Zeichen in Dateinamen
---

Diese App speichert deine Notizen, Kapitel, Romane und andere Inhalte in Textdateien. Das schlichte Textformat sorgt für breite Kompatibilität und plattformübergreifende Nutzbarkeit. Selbst wenn du die App irgendwann nicht mehr verwendest, kannst du deine Dateien problemlos in anderen Apps und Betriebssystemen verwalten und bearbeiten.

## Diese Zeichen sind in Dateinamen nicht zulässig: `\/:*?"<>|`

Diese Zeichen haben in Dateisystemen und vielen gängigen Programmen eine besondere Bedeutung. In Dateinamen können sie deshalb dazu führen, dass Dateien auf unterschiedlichen Geräten nicht zuverlässig erstellt, gefunden oder geöffnet werden. Beispielsweise trennt `/` Verzeichnisse in einem Pfad. `\` dient auf manchen Systemen ebenfalls als Pfadtrenner und in bestimmten Textformaten als Escape-Zeichen. Andere Zeichen dieser Gruppe können als Platzhalter, Trennzeichen oder Steuerzeichen verwendet werden. Damit deine Dateien plattformübergreifend problemlos nutzbar bleiben, lässt die App diese Zeichen in Dateinamen nicht zu.

## Warum darf ein Dateiname nicht mit `.` oder `..` beginnen?

Android basiert auf dem Linux-Kernel. In Linux-artigen Pfaden steht `.` für das aktuelle Verzeichnis und `..` für das übergeordnete Verzeichnis. Außerdem werden Dateien und Ordner, deren Namen mit einem Punkt beginnen, von Linux- und Android-Werkzeugen üblicherweise als verborgen behandelt. Die App verhindert daher einen Punkt am Anfang, um Verwechslungen mit speziellen Pfadbestandteilen zu vermeiden und deine Dateien sichtbar und leicht auffindbar zu halten.
