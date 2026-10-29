---
ShowToc: true
copy_mark: copied
date: 2024-05-25
title: Zo gebruik je de functie Remote Link
---

Met de functie "Link" kun je app-gegevens als een pc-map koppelen, zodat je pc-software kunt gebruiken om je gegevens te bewerken en te beheren.

Deze functie is gebaseerd op het algemene **WebDav**-protocol. De meeste besturingssystemen zouden dit standaard moeten ondersteunen, maar het is misschien niet zo eenvoudig te gebruiken. Hier is dus een eenvoudigere manier.

## Windows

Op Windows raden we de software van derden **RaiDrive** aan. Je kunt deze downloaden door op de onderstaande link te klikken:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Versie 1.8.0 is niet de nieuwste, maar heeft alles wat we nodig hebben en, belangrijker nog, geen advertenties)

Installeer en open het; je ziet mogelijk een paneel zoals dit. Volg gewoon de tips:

![RaiDrive setup](/img/add_drive.webp)

1. Klik bovenaan op de knop "Add" om naar de configuratie te gaan.
2. Ga naar het tabblad "NAS" en selecteer de WebDav-optie
3. Voer de stationsnaam naar wens in
4. Voer het adres in
    - naast de tekst "address" zie je mogelijk een selectievakje; laat het gewoon **NIET AANGEVINKT** zodat we een http-url kunnen gebruiken.
    - Voer het IP-adres en het poortnummer in, die je kunt vinden wanneer je de linkfunctie in de app inschakelt.
5. Voer je eigen gebruikersnaam en wachtwoord in als je die hebt; anders vink je gewoon het selectievakje "Anonymous" aan
6. Klik op de knop "OK" om het koppelen te starten

Als alles goed gaat, zie je mogelijk dit:

![Done](/img/done.webp)

## Linux of MacOS

### MacOS

Op macOS kun je de ingebouwde **Finder** gebruiken om verbinding te maken met de WebDav-service:

1. Open de **Finder**.
2. Klik in de menubalk op **Go** en kies **Connect to Server…** (of druk op `Command + K`).
3. Voer het in de app getoonde adres in het adresveld in, bijvoorbeeld `http://192.168.1.100:8080`.
4. Klik op **Connect**.
5. Voer desgevraagd je gebruikersnaam en wachtwoord in, of maak verbinding als gast.
6. Zodra de verbinding tot stand is gebracht, verschijnt de WebDav-service in de Finder als netwerkstation en kun je je gegevens als een lokale map benaderen en beheren.

### Linux

Op Linux (met Ubuntu desktop als voorbeeld) kun je de ingebouwde bestandsbeheerder gebruiken om verbinding te maken:

1. Open de app **Files**.
2. Klik in de linkerzijbalk op **Other Locations**.
3. Zoek onderaan het veld **Connect to Server**.
4. Voer het adres in de indeling `dav://IP:poort` in, bijvoorbeeld `dav://192.168.1.100:8080`.
5. Klik op **Connect**.
6. Voer desgevraagd je gebruikersnaam en wachtwoord in, of maak anoniem verbinding.
7. Zodra de verbinding tot stand is gebracht, verschijnt de WebDav-service in de bestandsbeheerder als netwerklocatie.
