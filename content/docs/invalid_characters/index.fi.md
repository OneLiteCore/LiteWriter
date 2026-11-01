---
ShowToc: true
title: Tiedostonimissä kielletyt merkit
---

Sovellus tallentaa muistiinpanosi, lukusi, romaanisi ja muun sisältösi tekstitiedostoihin. Käytämme pelkkää tekstiä, jotta tiedot toimivat laajasti eri alustoilla. Vaikka lopettaisit sovelluksen käytön, voit helposti hallita ja muokata tiedostojasi muissa sovelluksissa ja käyttöjärjestelmissä.

## Tiedostonimissä kielletyt merkit: `\/:*?"<>|`

Näillä merkeillä on erityisiä merkityksiä tiedostojärjestelmissä ja monissa yleisissä ohjelmissa. Niiden käyttö tiedostonimessä voi siksi vaikeuttaa tiedoston luomista, löytämistä tai avaamista yhdenmukaisesti eri laitteilla. Esimerkiksi `/` erottaa kansiot polussa, kun taas `\` toimii joissakin järjestelmissä polkuerottimena ja tietyissä tekstimuodoissa escape-merkkinä. Muut merkit voivat toimia esimerkiksi jokerimerkkeinä, erottimina tai ohjausmerkkeinä. Jotta tiedostosi toimisivat sujuvasti eri alustoilla, sovellus ei salli näitä merkkejä tiedostonimissä.

## Miksi tiedostonimi ei saa alkaa merkillä `.` tai `..`?

Android perustuu Linux-ytimeen. Linux-tyylisissä poluissa `.` tarkoittaa nykyistä kansiota ja `..` emokansiota. Lisäksi Linuxin ja Androidin työkalut käsittelevät yleensä pisteellä alkavia tiedostoja ja kansioita piilotettuina. Sovellus estää nimeä alkamasta pisteellä, jotta se ei sekoitu polkujen erikoisosiin ja tiedostosi pysyvät näkyvissä ja helposti löydettävissä.
