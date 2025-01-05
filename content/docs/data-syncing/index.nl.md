---
title: Hoe gegevens te synchroniseren  
date: 2024-09-20  
ShowToc: true
copy_mark: src
---

Technisch gezien ondersteunt onze app geen gegevenssynchronisatie tussen apparaten. Hoewel je de back-upfunctie kunt gebruiken om je gegevens van het ene apparaat naar het andere over te zetten, kan dit niet als synchronisatie worden beschouwd.

Dat gezegd hebbende, zijn er toch enkele manieren om buiten de app te synchroniseren.

# Stel een Opslagmap in als de Startmap van de App

Je kunt een map in de opslag van je apparaat instellen als de startmap van de app. In deze configuratie worden je boeken en hoofdstukken opgeslagen als submappen en tekstbestanden in de opslagmap.

Aangezien ze al als bestanden zijn opgeslagen, kun je externe bestandssynchronisatie-tools gebruiken om deze gegevens op verschillende apparaten te synchroniseren.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing is een veelgebruikt, cross-platform gegevenssynchronisatietool. Je kunt het gebruiken om de gegevens van je app te synchroniseren tussen je mobiele apparaten, pc, laptop of thuisserver.

Bekijk de officiële handleiding van Syncthing om te leren hoe je het kunt instellen:

[Syncthing - Aan de Slag](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Netwerkschijven

Sommige netwerkschijven bieden een bidirectionele bestandssynchronisatiefunctie. Door je startmap van de app als synchronisatiemap in te stellen, kun je gegevens synchroniseren tussen apparaten, met als bijkomend voordeel dat je de netwerkschijf kunt gebruiken als back-upserver.

# Git, SVN en Rsync

Voor degenen met programmeerkennis wordt deze methode sterk aanbevolen. Met apps zoals Termux kun je opdrachtregeltools gebruiken om je gegevens te synchroniseren.

Als je bekend bent met Git, SVN of Rsync, biedt deze optie veel flexibiliteit. Als je echter niet bekend bent met deze tools, raden we deze methode niet aan, omdat ze technische kennis vereisen en niet bedoeld zijn voor gewone gebruikers.

# Samenvatting

Het primaire doel van de app is om de gegevens van gebruikers veilig te houden. Aangezien het synchroniseren van gegevens tussen twee cliëntapps niet altijd veilig is, hebben we ervoor gekozen om geen ingebouwde synchronisatiefunctie te ontwikkelen. In plaats daarvan raden we aan om betrouwbare, professionele tools te gebruiken voor gegevenssynchronisatie.
