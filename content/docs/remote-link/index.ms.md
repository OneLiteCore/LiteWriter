---
ShowToc: true
copy_mark: copied
date: 2024-05-25
title: Cara menggunakan ciri Pautan Jauh
---

Ciri "Pautan" membolehkan anda memetakan data aplikasi sebagai direktori PC, supaya anda boleh menggunakan perisian PC untuk mengedit dan mengurus data anda.

Ciri ini berdasarkan protokol **WebDav** umum. Kebanyakan sistem pengendalian sepatutnya menyokongnya secara terus, tetapi mungkin ia tidak begitu mudah untuk digunakan. Jadi, inilah cara yang lebih mudah.

## Windows

Pada platform Windows, kami mengesyorkan perisian pihak ketiga **RaiDrive**. Anda boleh memuat turunnya dengan mengklik pautan di bawah:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Versi 1.8.0 bukanlah yang terkini, tetapi ia mempunyai semua yang kami perlukan, dan lebih penting lagi, ia tidak mempunyai iklan)

Pasang dan bukanya; anda mungkin melihat panel seperti ini, hanya ikut petunjuk:

![RaiDrive setup](/img/add_drive.webp)

1. Klik butang "Add" di bahagian atas untuk memasuki konfigurasi.
2. Pergi ke tab "NAS" dan pilih pilihan WebDav
3. Masukkan nama pemacu mengikut kehendak anda
4. Masukkan alamat
    - di sebelah teks "address", anda mungkin melihat kotak semak; biarkan ia **TIDAK DITANDA** supaya kita boleh menggunakan url http.
    - Masukkan alamat IP dan nombor port, yang boleh anda temui apabila anda menghidupkan ciri pautan dalam aplikasi.
5. Masukkan nama pengguna dan kata laluan tersuai anda jika ada; jika tidak, hanya tandakan kotak semak "Anonymous"
6. Klik butang "OK" untuk memulakan pemetaan

Jika semuanya berjalan lancar, anda mungkin melihat ini:

![Done](/img/done.webp)

## Linux atau MacOS

### MacOS

Pada macOS, anda boleh menggunakan **Finder** terbina dalam untuk menyambung ke perkhidmatan WebDav:

1. Buka **Finder**.
2. Dalam bar menu, klik **Go** dan pilih **Connect to Server…** (atau tekan `Command + K`).
3. Masukkan alamat yang ditunjukkan dalam aplikasi ke dalam medan alamat, contohnya `http://192.168.1.100:8080`.
4. Klik **Connect**.
5. Jika diminta, masukkan nama pengguna dan kata laluan anda, atau sambung sebagai tetamu.
6. Setelah disambungkan, perkhidmatan WebDav akan muncul dalam Finder sebagai pemacu rangkaian, dan anda boleh mengakses serta mengurus data anda seperti folder setempat.

### Linux

Pada Linux (mengambil desktop Ubuntu sebagai contoh), anda boleh menggunakan pengurus fail terbina dalam untuk menyambung:

1. Buka aplikasi **Files**.
2. Klik **Other Locations** dalam bar sisi kiri.
3. Cari medan **Connect to Server** di bahagian bawah.
4. Masukkan alamat dalam format `dav://IP:port`, contohnya `dav://192.168.1.100:8080`.
5. Klik **Connect**.
6. Jika diminta, masukkan nama pengguna dan kata laluan anda, atau sambung secara tanpa nama.
7. Setelah disambungkan, perkhidmatan WebDav akan muncul dalam pengurus fail sebagai lokasi rangkaian.
