---
ShowToc: true
date: 2026-10-31
title: Samba-backup-tjeneste
---

Samba er en universel fildelingsprotokol til lokale netværk (LAN), og den fungerer godt sammen med mange forskellige enheder og systemer.

# Forstå loginparametrene

- **Værtsnavn eller IP-adresse**: Adressen på den enhed, der kører Samba-serveren.
- **Port**: Samba-serverens port. Standard er **445**.
- **Samba-delingsnavn**: En Samba-server kan have flere delingsopsætninger, så du skal angive, hvilken deling der skal bruges.
- **Lagermappesti**: Lagringsstien under delingen. Den kan stå tom. Backupfilerne gemmes i denne sti; hvis den er tom, bruges delingens rodmappe.
- **Brugernavn**: Brugernavnet, som ikke må være tomt.
- **Adgangskode**: Adgangskoden, som ikke må være tom.
- **Begrænset WiFi-SSID**: Begrænser backup til et bestemt WiFi-netværk. Lad feltet stå tomt for at tillade backup på ethvert WiFi, eller angiv et SSID, så backup kun kører på det netværk. Samba bruges til fildeling på et lokalt netværk, så dette holder dine backups på et betroet WiFi.
