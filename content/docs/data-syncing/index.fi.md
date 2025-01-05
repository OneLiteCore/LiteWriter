---
title: Kuinka synkronoida tiedot  
date: 2024-09-20  
ShowToc: true
copy_mark: "src"
---

Teknisesti ottaen sovelluksemme ei tue tietojen synkronointia laitteiden välillä. Vaikka voit käyttää varmuuskopiointiominaisuutta siirtääksesi tietosi yhdeltä laitteelta toiselle, sitä ei voida kutsua synkronoinniksi.

Siitä huolimatta sinulla on joitain keinoja suorittaa synkronointi sovelluksen ulkopuolella.

# Aseta tallennuskansio sovelluksen kotikansioksi

Voit asettaa laitteen tallennustilassa olevan kansion sovelluksen kotikansioksi. Tässä tapauksessa kirjasi ja luvut tallennetaan alikansioina ja tekstitiedostoina tähän kansioon.

Koska ne ovat jo tiedostoja, voit käyttää ulkoisia tiedostojen synkronointityökaluja synkronoimaan nämä tiedot laitteiden välillä.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing on laajalti käytetty, monialustainen tiedonsynkronointityökalu. Voit käyttää sitä synkronoimaan sovelluksesi tiedot mobiililaitteiden, tietokoneen, kannettavan tietokoneen tai kotipalvelimen välillä.

Katso Syncthingin virallinen opas oppiaksesi, kuinka se asennetaan:

[Syncthing - Aloitusopas](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Verkkolevyt

Jotkin verkkolevyt tarjoavat kaksisuuntaisen tiedostojen synkronointikansiotoiminnon. Asettamalla sovelluksen kotikansion synkronointikansioksi voit synkronoida tiedot laitteiden välillä. Lisäksi voit käyttää verkkolevyä varmuuskopiopalvelimena tässä tapauksessa.

# Git, SVN ja Rsync

Jos osaat ohjelmoida, tämä menetelmä on suositeltavin. Voit käyttää esimerkiksi Termux-sovellusta ajaaksesi komentorivityökaluja tietojen synkronointiin.

Jos tunnet Gitin, SVN:n tai Rsyncin, tämä vaihtoehto tarjoaa hyvän joustavuuden. Jos et tunne näitä työkaluja, emme suosittele tätä menetelmää, sillä ne vaativat enemmän teknistä osaamista eivätkä ole tavallisille käyttäjille tarkoitettuja.

# Yhteenveto

Sovelluksen ensisijainen tavoite on pitää käyttäjien tiedot turvassa. Koska tietojen synkronointi kahden asiakassovelluksen välillä ei ole aina tarpeeksi turvallista, emme ole kehittäneet sisäänrakennettua synkronointiominaisuutta. Sen sijaan suosittelemme käyttämään luotettavia ja ammattimaisia työkaluja tietojen synkronointiin.
