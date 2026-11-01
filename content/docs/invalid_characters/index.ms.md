---
ShowToc: true
title: Aksara yang tidak dibenarkan dalam nama fail
---

Aplikasi ini menyimpan nota, bab, novel dan kandungan anda yang lain dalam fail teks. Kami menggunakan teks biasa supaya data serasi dengan pelbagai platform. Walaupun anda berhenti menggunakan aplikasi ini suatu hari nanti, anda masih boleh mengurus dan mengedit fail dengan mudah menggunakan aplikasi serta sistem pengendalian lain.

## Aksara yang tidak dibenarkan dalam nama fail: `\/:*?"<>|`

Aksara ini mempunyai fungsi khas dalam sistem fail dan banyak perisian yang biasa digunakan. Jika digunakan dalam nama fail, ia boleh menyukarkan fail untuk dicipta, dicari atau dibuka secara konsisten pada peranti yang berbeza. Contohnya, `/` memisahkan folder dalam laluan, manakala `\` menjadi pemisah laluan pada sesetengah sistem dan aksara escape dalam format teks tertentu. Aksara lain dalam senarai ini pula boleh berfungsi sebagai kad bebas, pemisah atau simbol kawalan. Untuk memastikan fail anda mudah digunakan merentas platform, aplikasi ini tidak membenarkan aksara tersebut dalam nama fail.

## Mengapa nama fail tidak boleh bermula dengan `.` atau `..`?

Android berasaskan kernel Linux. Dalam laluan gaya Linux, `.` merujuk kepada folder semasa dan `..` merujuk kepada folder induk. Selain itu, alat Linux dan Android biasanya menganggap fail serta folder yang namanya bermula dengan titik sebagai tersembunyi. Aplikasi ini melarang titik pada permulaan nama untuk mengelakkan kekeliruan dengan komponen laluan khas serta memastikan fail anda kelihatan dan mudah dicari.
