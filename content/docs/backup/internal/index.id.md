---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Layanan cadangan internal
---

Aplikasi menyediakan mekanisme cadangan internal yang secara berkala mengompresi data bab Anda ke dalam file .zip.

# File cadangan internal akan hilang jika aplikasi dihapus

Mekanisme bawaan menyimpan file cadangan .zip di folder pribadi aplikasi. Folder ini, bersama data aplikasi lainnya, akan dihapus jika aplikasi dihapus.

Jadi, jangan hanya mengandalkan mekanisme ini untuk menjaga data Anda tetap aman. Mekanisme ini tidak dirancang untuk menjadi satu-satunya metode cadangan Anda.

# Cara kerjanya

Saat Anda meninggalkan aplikasi, atau pada waktu terjadwal setiap hari, aplikasi akan memeriksa apakah ada perubahan yang belum dicadangkan. Jika ada, proses cadangan akan dipicu. Secara default, ada jeda setidaknya 8 jam di antara dua proses cadangan.

Setelah file zip baru dibuat, aplikasi akan memeriksa data cadangan lama dan menghapusnya jika diperlukan. Secara default, aplikasi menyimpan 20 file cadangan terbaru, sehingga Anda tidak perlu khawatir cadangan akan memakan terlalu banyak ruang penyimpanan.

Jika Anda telah mengonfigurasi layanan cadangan lain, seperti Google Drive atau cadangan penyimpanan perangkat, file zip terbaru juga akan diunggah ke sana.
