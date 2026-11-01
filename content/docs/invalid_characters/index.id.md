---
ShowToc: true
title: Karakter yang tidak valid dalam nama file
---

Aplikasi ini menyimpan catatan, bab, novel, dan konten lainnya dalam file teks. Kami menggunakan teks biasa agar data tetap kompatibel di berbagai platform. Jadi, meskipun suatu saat Anda berhenti menggunakan aplikasi ini, Anda tetap dapat mengelola dan mengedit file dengan mudah melalui aplikasi atau sistem operasi lain.

## Karakter yang tidak boleh digunakan dalam nama file: `\/:*?"<>|`

Karakter-karakter ini memiliki fungsi khusus dalam sistem file dan berbagai perangkat lunak umum. Jika digunakan dalam nama file, karakter tersebut dapat membuat file sulit dibuat, ditemukan, atau dibuka secara konsisten di perangkat yang berbeda. Contohnya, `/` memisahkan folder dalam sebuah path, sedangkan `\` digunakan sebagai pemisah path di beberapa sistem dan sebagai karakter escape dalam format teks tertentu. Karakter lainnya dapat berfungsi sebagai wildcard, pemisah, atau simbol kontrol. Agar file Anda tetap mudah digunakan di berbagai platform, aplikasi ini tidak mengizinkan karakter tersebut dalam nama file.

## Mengapa nama file tidak boleh diawali dengan `.` atau `..`?

Android didasarkan pada kernel Linux. Dalam path bergaya Linux, `.` merujuk ke folder saat ini dan `..` merujuk ke folder induk. Selain itu, alat di Linux dan Android biasanya menganggap file dan folder yang namanya diawali titik sebagai item tersembunyi. Aplikasi ini melarang titik di awal nama untuk mencegah kerancuan dengan komponen path khusus serta menjaga file tetap terlihat dan mudah ditemukan.
