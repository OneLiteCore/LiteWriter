---
ShowToc: true
date: 2026-10-31
title: Samba-back-upservice
---

Samba is een universeel protocol voor het delen van bestanden binnen een lokaal netwerk (LAN) en werkt goed samen met uiteenlopende apparaten en systemen.

# De aanmeldparameters begrijpen

- **Hostnaam of IP-adres**: Het adres van het apparaat waarop de Samba-server draait.
- **Poort**: De poort van de Samba-server. De standaardwaarde is **445**.
- **Naam van de Samba-share**: Een Samba-server kan meerdere share-configuraties hebben, dus je moet aangeven welke share je wilt gebruiken.
- **Pad van de opslagmap**: Het opslagpad binnen de share. Dit mag leeg blijven. De back-ups worden in dit pad opgeslagen; is het leeg, dan wordt de hoofdmap van de share gebruikt.
- **Gebruikersnaam**: De gebruikersnaam, die niet leeg mag zijn.
- **Wachtwoord**: Het wachtwoord, dat niet leeg mag zijn.
- **Beperkte WiFi-SSID**: Beperkt de back-up tot een specifiek WiFi-netwerk. Laat het veld leeg om back-ups op elk WiFi-netwerk toe te staan, of voer een SSID in zodat de back-up alleen op dat netwerk wordt uitgevoerd. Samba deelt bestanden via een lokaal netwerk, dus zo blijven je back-ups op een vertrouwd WiFi-netwerk.
