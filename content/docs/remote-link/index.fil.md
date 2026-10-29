---
ShowToc: true
copy_mark: copied
date: 2024-05-25
title: Paano gamitin ang Remote Link feature
---

Ang feature na "Link" ay nagbibigay-daan sa iyo na i-map ang data ng app bilang isang direktoryo sa PC, para magamit mo ang PC software upang i-edit at pamahalaan ang iyong data.

Ang feature na ito ay batay sa pangkalahatang **WebDav** protocol. Karamihan sa mga operating system ay dapat na sumusuporta rito kaagad, ngunit maaaring hindi ito gaanong madaling gamitin. Kaya narito ang mas madaling paraan.

## Windows

Sa platform na Windows, inirerekomenda namin ang third-party software na **RaiDrive**. Maaari mo itong i-download sa pamamagitan ng pag-click sa link sa ibaba:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Ang bersyon na 1.8.0 ay hindi ang pinakabago, ngunit mayroon itong lahat ng kailangan namin, at higit sa lahat, wala itong mga ad)

I-install at buksan ito; maaari kang makakita ng panel na tulad nito, sundin lamang ang mga tip:

![RaiDrive setup](/img/add_drive.webp)

1. I-click ang button na "Add" sa itaas upang pumasok sa configuration.
2. Pumunta sa tab na "NAS" at piliin ang opsyong WebDav
3. Ilagay ang pangalan ng drive ayon sa gusto mo
4. Ilagay ang address
    - sa tabi ng tekstong "address", maaari mong makita ang checkbox; panatilihin lamang itong **WALANG TSEK** upang magamit natin ang http url.
    - Ilagay ang IP address at port number, na makikita mo kapag binuksan mo ang link feature sa app.
5. Ilagay ang iyong custom na user name at password kung mayroon ka; kung wala, lagyan lamang ng tsek ang checkbox na "Anonymous"
6. I-click ang button na "OK" upang simulan ang pag-map

Kung maayos ang lahat, maaari mong makita ito:

![Done](/img/done.webp)

## Linux o MacOS

Hintaying matapos.
