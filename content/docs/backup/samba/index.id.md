---
ShowToc: true
date: 2026-10-31
title: Layanan cadangan Samba
---

Samba adalah protokol berbagi file yang umum untuk jaringan area lokal (LAN), dan bekerja dengan baik di berbagai perangkat serta sistem.

# Memahami parameter login

- **Nama host atau alamat IP**: Alamat perangkat yang menjalankan server Samba.
- **Port**: Port server Samba. Defaultnya adalah **445**.
- **Nama share Samba**: Satu server Samba bisa memiliki beberapa pengaturan share, jadi Anda perlu menentukan share mana yang akan digunakan.
- **Path folder penyimpanan**: Path penyimpanan di dalam share. Boleh dibiarkan kosong. File cadangan disimpan di bawah path ini; jika kosong, direktori akar share yang digunakan.
- **Nama pengguna**: Nama pengguna, tidak boleh kosong.
- **Kata sandi**: Kata sandi, tidak boleh kosong.
- **SSID WiFi terbatas**: Membatasi cadangan ke jaringan WiFi tertentu. Biarkan kosong agar cadangan boleh berjalan di WiFi mana pun, atau masukkan SSID agar cadangan hanya berjalan di jaringan itu. Karena Samba dipakai untuk berbagi file di jaringan lokal, ini menjaga cadangan Anda tetap berada di WiFi yang tepercaya.
