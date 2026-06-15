---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

Appen har en intern sikkerhedskopieringsmekanisme, som med jævne mellemrum komprimerer dine kapiteldata til en .zip-fil.

# Interne sikkerhedskopifiler går tabt, hvis appen afinstalleres

Den indbyggede mekanisme gemmer sikkerhedskopiens .zip-filer i en privat app-mappe. Denne mappe bliver slettet sammen med andre appdata, hvis appen afinstalleres.

Stol derfor ikke kun på denne mekanisme for at beskytte dine data. Den er ikke designet til at være din eneste sikkerhedskopieringsmetode.

# Sådan virker det

Når du forlader appen, eller på det planlagte tidspunkt hver dag, tjekker appen, om der er ændringer, som endnu ikke er blevet sikkerhedskopieret. Hvis der er det, bliver sikkerhedskopieringsprocessen startet. Som standard er der mindst 8 timer mellem to sikkerhedskopieringsprocesser.

Når en ny zip-fil er oprettet, tjekker appen for gamle sikkerhedskopidata og sletter dem om nødvendigt. Som standard beholder appen de 20 nyeste sikkerhedskopifiler, så du behøver ikke bekymre dig om, hvorvidt sikkerhedskopier bruger for meget lagerplads.

Hvis du har konfigureret andre sikkerhedskopitjenester, såsom Google Drive eller sikkerhedskopiering til enhedens lager, bliver den nyeste zip-fil også uploadet dertil.
