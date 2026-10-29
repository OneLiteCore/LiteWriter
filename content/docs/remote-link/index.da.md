---
ShowToc: true
copy_mark: copied
date: 2024-05-25
title: Sådan bruger du Remote Link-funktionen
---

"Link"-funktionen giver dig mulighed for at kortlægge appdata som en mappe på pc'en, så du kan bruge pc-software til at redigere og administrere dine data.

Denne funktion er baseret på den generelle **WebDav**-protokol. De fleste operativsystemer burde understøtte den direkte, men det er måske ikke helt let at bruge. Her er derfor en nemmere måde at gøre det på.

## Windows

På Windows anbefaler vi tredjepartssoftwaren **RaiDrive**. Du kan downloade den ved at klikke på linket nedenfor:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Version 1.8.0 er ikke den nyeste, men den har alt, hvad vi har brug for, og vigtigere endnu, den har ingen reklamer)

Installer og åbn den; du vil muligvis se et panel som dette. Følg blot vejledningen:

![RaiDrive setup](/img/add_drive.webp)

1. Klik på knappen "Add" øverst for at gå ind i konfigurationen.
2. Gå til fanen "NAS", og vælg indstillingen WebDav
3. Indtast drevnavnet, som du ønsker det
4. Indtast adressen
    - ved siden af teksten "address" vil du muligvis se et afkrydsningsfelt; lad det blot forblive **IKKE-AFKRYSET**, så vi kan bruge en http-url.
    - Indtast IP-adressen og portnummeret, som du kan finde, når du aktiverer linkfunktionen i appen.
5. Indtast dit eget brugernavn og kodeord, hvis du har nogen; ellers skal du blot markere afkrydsningsfeltet "Anonymous"
6. Klik på knappen "OK" for at starte kortlægningen

Hvis alt går godt, vil du muligvis se dette:

![Done](/img/done.webp)

## Linux eller MacOS

### MacOS

På macOS kan du bruge den indbyggede **Finder** til at oprette forbindelse til WebDav-tjenesten:

1. Åbn **Finder**.
2. Klik på **Go** i menulinjen, og vælg **Connect to Server…** (eller tryk på `Command + K`).
3. Indtast den adresse, der vises i appen, i adressefeltet, for eksempel `http://192.168.1.100:8080`.
4. Klik på **Connect**.
5. Indtast dit brugernavn og kodeord, hvis du bliver bedt om det, eller opret forbindelse som gæst.
6. Når forbindelsen er oprettet, vises WebDav-tjenesten i Finder som et netværksdrev, og du kan få adgang til og administrere dine data som en lokal mappe.

### Linux

På Linux (med Ubuntu desktop som eksempel) kan du bruge den indbyggede filhåndtering til at oprette forbindelse:

1. Åbn appen **Files**.
2. Klik på **Other Locations** i venstre sidepanel.
3. Find feltet **Connect to Server** nederst.
4. Indtast adressen i formatet `dav://IP:port`, for eksempel `dav://192.168.1.100:8080`.
5. Klik på **Connect**.
6. Indtast dit brugernavn og kodeord, hvis du bliver bedt om det, eller opret forbindelse anonymt.
7. Når forbindelsen er oprettet, vises WebDav-tjenesten i filhåndteringen som en netværksplacering.
