---
ShowToc: true
title: Mga hindi pinapahintulutang character sa pangalan ng file
---

Iniimbak ng app na ito ang iyong mga tala, kabanata, nobela, at iba pang nilalaman bilang mga text file. Gumagamit kami ng plain text para maging tugma ang iyong data sa iba't ibang platform. Kahit tumigil ka man sa paggamit ng app na ito, madali mo pa ring mapapamahalaan at mae-edit ang iyong mga file sa ibang app at operating system.

## Mga character na hindi puwedeng gamitin sa pangalan ng file: `\/:*?"<>|`

May espesyal na gamit ang mga character na ito sa mga file system at karaniwang software. Kapag isinama ang mga ito sa pangalan ng file, maaaring hindi pare-pareho ang paggawa, paghahanap, o pagbukas ng file sa iba't ibang device. Halimbawa, ginagamit ang `/` bilang panghiwalay ng mga folder sa path, habang ang `\` ay path separator sa ilang system at escape character sa ilang format ng teksto. Maaari namang gamitin ang iba bilang wildcard, delimiter, o control symbol. Para manatiling madaling gamitin ang mga file sa iba't ibang platform, hindi pinapayagan ng app ang mga character na ito sa mga pangalan ng file.

## Bakit hindi dapat magsimula sa `.` o `..` ang pangalan ng file?

Nakabatay ang Android sa Linux kernel. Sa mga path na istilong Linux, ang `.` ay tumutukoy sa kasalukuyang folder at ang `..` sa parent folder. Bukod dito, karaniwang itinatago ng mga tool sa Linux at Android ang mga file at folder na nagsisimula sa tuldok. Hindi pinapayagan ng app ang tuldok sa unahan ng pangalan upang maiwasan ang kalituhan sa mga espesyal na bahagi ng path at para manatiling nakikita at madaling mahanap ang iyong mga file.
