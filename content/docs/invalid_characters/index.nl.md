---
ShowToc: true
title: Ongeldige tekens in bestandsnamen
---

Deze app slaat je notities, hoofdstukken, romans en andere inhoud op in tekstbestanden. We gebruiken platte tekst voor brede compatibiliteit en gebruik op verschillende platforms. Ook als je de app later niet meer gebruikt, kun je je bestanden eenvoudig beheren en bewerken met andere apps en besturingssystemen.

## Tekens die niet in bestandsnamen mogen voorkomen: `\/:*?"<>|`

Deze tekens hebben een speciale betekenis in bestandssystemen en veelgebruikte software. Gebruik je ze in een bestandsnaam, dan kan het lastig worden om bestanden op verschillende apparaten op dezelfde manier aan te maken, te vinden of te openen. Zo scheidt `/` mappen in een pad. Op sommige systemen is `\` ook een padscheidingsteken en in bepaalde tekstindelingen een escape-teken. Andere tekens uit deze reeks kunnen dienen als jokerteken, scheidingsteken of besturingssymbool. Om je bestanden op verschillende platforms bruikbaar te houden, staat de app deze tekens niet toe in bestandsnamen.

## Waarom mag een bestandsnaam niet beginnen met `.` of `..`?

Android is gebaseerd op de Linux-kernel. In Linux-achtige paden verwijst `.` naar de huidige map en `..` naar de bovenliggende map. Bovendien beschouwen Linux- en Android-hulpmiddelen bestanden en mappen waarvan de naam met een punt begint doorgaans als verborgen. De app verbiedt daarom een punt aan het begin van een naam, om verwarring met speciale padonderdelen te voorkomen en je bestanden zichtbaar en gemakkelijk vindbaar te houden.
