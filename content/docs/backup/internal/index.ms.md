---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

Aplikasi ini menyediakan mekanisme sandaran dalaman yang secara berkala memampatkan data bab anda ke dalam fail .zip.

# Fail sandaran dalaman akan hilang jika aplikasi dinyahpasang

Mekanisme terbina dalam menyimpan fail sandaran .zip dalam folder peribadi aplikasi. Folder ini, bersama data aplikasi yang lain, akan dipadam jika aplikasi dinyahpasang.

Oleh itu, jangan bergantung pada mekanisme ini sahaja untuk memastikan data anda selamat. Ia tidak direka untuk menjadi satu-satunya kaedah sandaran anda.

# Cara ia berfungsi

Apabila anda meninggalkan aplikasi, atau pada masa yang dijadualkan setiap hari, aplikasi akan memeriksa sama ada terdapat perubahan yang belum disandarkan. Jika ada, proses sandaran akan dimulakan. Secara lalai, terdapat sela masa sekurang-kurangnya 8 jam antara dua proses sandaran.

Selepas fail zip baharu dicipta, aplikasi akan menyemak data sandaran lama dan memadamkannya jika perlu. Secara lalai, aplikasi menyimpan 20 fail sandaran terkini, jadi anda tidak perlu risau sandaran akan mengambil terlalu banyak ruang storan.

Jika anda telah mengkonfigurasi perkhidmatan sandaran lain, seperti Google Drive atau sandaran storan peranti, fail zip terkini juga akan dimuat naik ke sana.
