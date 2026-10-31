---
ShowToc: true
date: 2026-10-31
title: Perkhidmatan sandaran Samba
---

Samba ialah protokol perkongsian fail yang umum untuk rangkaian kawasan setempat (LAN), dan ia berfungsi dengan baik dengan pelbagai peranti serta sistem.

# Memahami parameter log masuk

- **Nama hos atau alamat IP**: Alamat peranti yang menjalankan pelayan Samba.
- **Port**: Port pelayan Samba. Nilai lalai ialah **445**.
- **Nama perkongsian Samba**: Satu pelayan Samba boleh mempunyai beberapa tetapan perkongsian, jadi anda perlu menentukan perkongsian yang hendak digunakan.
- **Laluan folder storan**: Laluan storan di dalam perkongsian. Ia boleh dibiarkan kosong. Fail sandaran disimpan di bawah laluan ini; jika kosong, direktori akar perkongsian akan digunakan.
- **Nama pengguna**: Nama pengguna, yang tidak boleh kosong.
- **Kata laluan**: Kata laluan, yang tidak boleh kosong.
- **SSID WiFi terhad**: Mengehadkan sandaran kepada satu rangkaian WiFi tertentu. Biarkan kosong untuk membenarkan sandaran pada mana-mana WiFi, atau masukkan SSID agar sandaran hanya berjalan pada rangkaian itu. Samba digunakan untuk berkongsi fail melalui rangkaian setempat, jadi ini memastikan sandaran anda kekal pada WiFi yang dipercayai.
