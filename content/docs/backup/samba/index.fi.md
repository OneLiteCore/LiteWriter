---
ShowToc: true
date: 2026-10-31
title: Samba-varmuuskopiopalvelu
---

Samba on yleiskäyttöinen tiedostonjakoprotokolla lähiverkkoihin (LAN), ja se toimii hyvin monenlaisten laitteiden ja järjestelmien kanssa.

# Kirjautumisparametrien ymmärtäminen

- **Isäntänimi tai IP-osoite**: Samba-palvelinta ajavan laitteen osoite.
- **Portti**: Samba-palvelimen portti. Oletusarvo on **445**.
- **Samba-jaon nimi**: Samba-palvelimella voi olla useita jakoasetuksia, joten sinun on kerrottava, mitä jakoa käytetään.
- **Tallennuskansion polku**: Tallennuspolku jaon sisällä. Sen voi jättää tyhjäksi. Varmuuskopiot tallennetaan tähän polkuun; jos se on tyhjä, käytetään jaon juurihakemistoa.
- **Käyttäjätunnus**: Käyttäjätunnus, joka ei voi olla tyhjä.
- **Salasana**: Salasana, joka ei voi olla tyhjä.
- **Rajoitettu WiFi-SSID**: Rajoittaa varmuuskopioinnin tiettyyn WiFi-verkkoon. Jätä kenttä tyhjäksi, jotta varmuuskopiot sallitaan missä tahansa WiFi-verkossa, tai anna SSID, jotta varmuuskopio suoritetaan vain siinä verkossa. Sambaa käytetään tiedostojen jakamiseen lähiverkossa, joten näin varmuuskopiot pysyvät luotettavassa WiFi-verkossa.
