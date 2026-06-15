---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

Die App bietet einen internen Sicherungsmechanismus, der deine Kapiteldaten regelmäßig in eine .zip-Datei komprimiert.

# Interne Sicherungsdateien gehen verloren, wenn die App deinstalliert wird

Der eingebaute Mechanismus speichert die Sicherungs-.zip-Dateien in einem privaten App-Ordner. Dieser Ordner wird zusammen mit den anderen App-Daten gelöscht, wenn die App deinstalliert wird.

Verlasse dich daher nicht ausschließlich auf diesen Mechanismus, um deine Daten zu schützen. Er ist nicht als einzige Sicherungsmethode gedacht.

# So funktioniert es

Wenn du die App verlässt oder die täglich geplante Zeit erreicht ist, prüft die App, ob es Änderungen gibt, die noch nicht gesichert wurden. Falls ja, wird der Sicherungsvorgang gestartet. Standardmäßig liegen zwischen zwei Sicherungsvorgängen mindestens 8 Stunden.

Nachdem eine neue zip-Datei erstellt wurde, prüft die App auf alte Sicherungsdaten und löscht sie bei Bedarf. Standardmäßig behält die App die neuesten 20 Sicherungsdateien, sodass du dir keine Sorgen machen musst, dass Sicherungen zu viel Speicherplatz belegen.

Wenn du andere Sicherungsdienste wie Google Drive oder Gerätespeicher-Backups eingerichtet hast, wird die neueste zip-Datei auch dorthin hochgeladen.
