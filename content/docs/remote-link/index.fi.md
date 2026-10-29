---
ShowToc: true
copy_mark: copied
date: 2024-05-25
title: Näin käytät Remote Link -ominaisuutta
---

"Link"-ominaisuuden avulla voit liittää sovelluksen tiedot PC-hakemistoksi, jotta voit muokata ja hallita tietojasi PC-ohjelmistolla.

Tämä ominaisuus perustuu yleiseen **WebDav**-protokollaan. Useimpien käyttöjärjestelmien pitäisi tukea sitä suoraan, mutta sen käyttö ei ehkä ole kovin helppoa. Tässä on siksi helpompi tapa.

## Windows

Windowsilla suosittelemme kolmannen osapuolen ohjelmistoa **RaiDrive**. Voit ladata sen napsauttamalla alla olevaa linkkiä:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Versio 1.8.0 ei ole uusin, mutta siinä on kaikki mitä tarvitsemme, ja mikä tärkeämpää, siinä ei ole mainoksia)

Asenna ja avaa se; saatat nähdä tällaisen paneelin. Seuraa vain vinkkejä:

![RaiDrive setup](/img/add_drive.webp)

1. Napsauta yläreunan "Add"-painiketta siirtyäksesi määrityksiin.
2. Siirry "NAS"-välilehteen ja valitse WebDav-vaihtoehto
3. Anna aseman nimi haluamallasi tavalla
4. Anna osoite
    - "address"-tekstin vieressä saatat nähdä valintaruudun; jätä se **VALITSEMATTA**, jotta voimme käyttää http-osoitetta.
    - Anna IP-osoite ja porttinumero, jotka löydät, kun otat linkkiominaisuuden käyttöön sovelluksessa.
5. Anna mukautettu käyttäjätunnuksesi ja salasanasi, jos sinulla on sellaiset; muussa tapauksessa valitse vain "Anonymous"-valintaruutu
6. Napsauta "OK"-painiketta aloittaaksesi liittämisen

Jos kaikki menee hyvin, saatat nähdä tämän:

![Done](/img/done.webp)

## Linux tai MacOS

Odottaa valmistumista.
