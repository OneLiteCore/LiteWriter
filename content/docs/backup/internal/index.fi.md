---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

Sovellus tarjoaa sisäisen varmuuskopiointimekanismin, joka pakkaa lukujesi tiedot säännöllisesti .zip-tiedostoksi.

# Sisäiset varmuuskopiotiedostot menetetään, jos sovellus poistetaan

Sisäänrakennettu mekanismi tallentaa varmuuskopioiden .zip-tiedostot sovelluksen yksityiseen kansioon. Tämä kansio poistetaan yhdessä muiden sovellustietojen kanssa, jos sovellus poistetaan.

Älä siis luota pelkästään tähän mekanismiin tietojesi suojaamisessa. Sitä ei ole suunniteltu ainoaksi varmuuskopiointitavaksesi.

# Miten se toimii

Kun poistut sovelluksesta tai päivittäin määritettynä ajankohtana, sovellus tarkistaa, onko olemassa muutoksia, joita ei ole vielä varmuuskopioitu. Jos on, varmuuskopiointi käynnistyy. Oletuksena kahden varmuuskopioinnin välillä on vähintään 8 tuntia.

Kun uusi zip-tiedosto on luotu, sovellus tarkistaa vanhat varmuuskopiotiedot ja poistaa ne tarvittaessa. Oletuksena sovellus säilyttää 20 uusinta varmuuskopiotiedostoa, joten sinun ei tarvitse huolehtia siitä, että varmuuskopiot vievät liikaa tallennustilaa.

Jos olet määrittänyt muita varmuuskopiointipalveluita, kuten Google Driven tai laitteen tallennustilan varmuuskopioinnin, uusin zip-tiedosto ladataan myös sinne.
