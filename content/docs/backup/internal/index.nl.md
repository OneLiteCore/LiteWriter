---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Interne back-upservice
---

De app biedt een intern back-upmechanisme dat je hoofdstukgegevens periodiek comprimeert naar een .zip-bestand.

# Interne back-upbestanden gaan verloren als de app wordt verwijderd

Het ingebouwde mechanisme slaat back-up-.zip-bestanden op in een privémap van de app. Deze map wordt samen met de andere appgegevens verwijderd als de app wordt verwijderd.

Vertrouw daarom niet uitsluitend op dit mechanisme om je gegevens veilig te houden. Het is niet bedoeld als je enige back-upmethode.

# Hoe het werkt

Wanneer je de app verlaat, of op het geplande tijdstip elke dag, controleert de app of er wijzigingen zijn die nog niet zijn geback-upt. Als dat zo is, wordt het back-upproces gestart. Standaard zit er minstens 8 uur tussen twee back-upprocessen.

Nadat een nieuw zip-bestand is aangemaakt, controleert de app op oude back-upgegevens en verwijdert die indien nodig. Standaard bewaart de app de 20 nieuwste back-upbestanden, zodat je je geen zorgen hoeft te maken dat back-ups te veel opslagruimte innemen.

Als je andere back-updiensten hebt ingesteld, zoals Google Drive of apparaatsopslagback-up, wordt het nieuwste zip-bestand daar ook naartoe geüpload.
