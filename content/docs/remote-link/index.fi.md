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

### MacOS

macOS:ssa voit käyttää sisäänrakennettua **Finder**-ohjelmaa WebDav-palveluun yhdistämiseen:

1. Avaa **Finder**.
2. Napsauta valikkopalkissa **Go** ja valitse **Connect to Server…** (tai paina `Command + K`).
3. Kirjoita osoitekenttään sovelluksessa näkyvä osoite, esimerkiksi `http://192.168.1.100:8080`.
4. Napsauta **Connect**.
5. Syötä pyydettäessä käyttäjätunnuksesi ja salasanasi tai yhdistä vieraana.
6. Kun yhteys on muodostettu, WebDav-palvelu näkyy Finderissa verkkoasemana, ja voit käyttää ja hallita tietojasi kuten paikallista kansiota.

### Linux

Linuxissa (esimerkkinä Ubuntu-työpöytä) voit käyttää sisäänrakennettua tiedostonhallintaa yhdistämiseen:

1. Avaa **Files**-sovellus.
2. Napsauta vasemmassa sivupalkissa **Other Locations**.
3. Etsi alareunasta **Connect to Server** -kenttä.
4. Kirjoita osoite muodossa `dav://IP:portti`, esimerkiksi `dav://192.168.1.100:8080`.
5. Napsauta **Connect**.
6. Syötä pyydettäessä käyttäjätunnuksesi ja salasanasi tai yhdistä anonyymisti.
7. Kun yhteys on muodostettu, WebDav-palvelu näkyy tiedostonhallinnassa verkkosijaintina.
