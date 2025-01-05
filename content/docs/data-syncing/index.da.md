---
title: Sådan synkroniserer du data  
date: 2024-09-20  
ShowToc: true
copy_mark: "src"
---

Teknisk set understøtter vores app ikke synkronisering af data mellem enheder. Selvom du kan bruge backup-funktionen til at overføre dine data fra en enhed til en anden, kan det ikke kaldes synkronisering.

Det sagt, har du stadig nogle måder at udføre synkronisering uden for appen.

# Sæt en lagringsmappe som appens hjemmemappe

Du kan indstille en mappe i din enheds lager som appens hjemmemappe. I denne opsætning gemmes dine bøger og kapitler som undermapper og tekstfiler i lagringsmappen.

Da de allerede er gemt som filer, kan du bruge eksterne værktøjer til synkronisering af filer for at synkronisere disse data mellem enheder.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing er et meget brugt, tværplatforms værktøj til datasynkronisering. Du kan bruge det til at synkronisere din apps data mellem dine mobile enheder, PC, laptop eller hjemme-server.

Tjek Syncthings officielle guide for at lære, hvordan du opsætter det:

[Syncthing - Kom godt i gang](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Netværksdiske

Nogle netværksdiske tilbyder en funktion til tovejs-synkronisering af filer. Ved at indstille din apps hjemmemappe som synkroniseringsmappen kan du synkronisere data mellem enheder og samtidig bruge netværksdisken som en backup-server.

# Git, SVN og Rsync

For dem med programmeringskundskaber anbefales denne metode stærkt. Ved hjælp af apps som Termux kan du køre kommandolinjeværktøjer til synkronisering af dine data.

Hvis du er bekendt med Git, SVN eller Rsync, giver denne mulighed stor fleksibilitet. Men hvis du ikke kender disse værktøjer, anbefaler vi det ikke, da de kræver teknisk viden og ikke er beregnet til almindelige brugere.

# Resumé

Appens primære mål er at holde brugernes data sikre. Da synkronisering af data mellem to klientapps ikke altid er sikkert, har vi valgt ikke at udvikle en indbygget synkroniseringsfunktion. I stedet anbefaler vi at bruge pålidelige, professionelle værktøjer til datasynkronisering.
