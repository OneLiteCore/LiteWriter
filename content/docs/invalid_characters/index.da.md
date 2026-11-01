---
ShowToc: true
title: Ugyldige tegn i filnavne
---

Appen gemmer dine noter, kapitler, romaner og andet indhold i tekstfiler. Vi bruger ren tekst for at sikre kompatibilitet på tværs af platforme: Selv hvis du en dag holder op med at bruge appen, kan du nemt administrere og redigere dine filer i andre apps og operativsystemer.

## Tegn, der ikke må bruges i filnavne: `\/:*?"<>|`

Disse tegn har særlige betydninger i filsystemer og anden almindelig software. Hvis de bruges i filnavne, kan det derfor blive svært at oprette, finde eller åbne filerne ens på forskellige enheder. For eksempel adskiller `/` mapper i en filsti, mens `\` bruges som stiseparator på nogle systemer og som escape-tegn i visse tekstformater. De øvrige tegn kan også fungere som jokertegn, separatorer eller kontrolsymboler. For at gøre dine filer nemme at bruge på tværs af platforme tillader appen ikke disse tegn i filnavne.

## Hvorfor må et filnavn ikke begynde med `.` eller `..`?

Android er baseret på Linux-kernen. I Linux-lignende stier står `.` for den aktuelle mappe, og `..` står for den overordnede mappe. Desuden betragtes filer og mapper, hvis navne begynder med et punktum, normalt som skjulte af værktøjer i Linux og Android. Appen forhindrer filnavne i at begynde med et punktum for at undgå forveksling med særlige sti-elementer og gøre dine filer synlige og nemme at finde.
