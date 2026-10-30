---
ShowToc: true
date: 2024-05-25
title: Cara menggunakan fitur Tautan Jarak Jauh
---

Fitur "Tautan" memungkinkan Anda memetakan data aplikasi sebagai direktori PC, sehingga Anda dapat menggunakan perangkat lunak PC untuk mengedit dan mengelola data Anda.

Fitur ini didasarkan pada protokol **WebDav** umum. Sebagian besar sistem operasi seharusnya mendukungnya secara langsung, tetapi mungkin tidak semudah itu digunakan. Jadi, berikut cara yang lebih mudah.

## Windows

Di platform Windows, kami merekomendasikan perangkat lunak pihak ketiga **RaiDrive**. Anda dapat mengunduhnya dengan mengeklik tautan di bawah ini:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Versi 1.8.0 bukan yang terbaru, tetapi memiliki semua yang kami butuhkan, dan yang lebih penting, tidak ada iklan)

Instal dan buka; Anda mungkin melihat panel seperti ini, cukup ikuti petunjuknya:

![RaiDrive setup](/img/add_drive.webp)

1. Klik tombol "Add" di bagian atas untuk masuk ke konfigurasi.
2. Buka tab "NAS" dan pilih opsi WebDav
3. Masukkan nama drive sesuai keinginan Anda
4. Masukkan alamat
    - di samping teks "address", Anda mungkin melihat kotak centang; biarkan **TIDAK DICENTANG** agar kita dapat menggunakan url http.
    - Masukkan alamat IP dan nomor port, yang dapat Anda temukan saat menyalakan fitur tautan di aplikasi.
5. Masukkan nama pengguna dan kata sandi khusus Anda jika ada; jika tidak, cukup centang kotak "Anonymous"
6. Klik tombol "OK" untuk memulai pemetaan

Jika semuanya berjalan baik, Anda mungkin melihat ini:

![Done](/img/done.webp)

## Linux atau MacOS

### MacOS

Di macOS, Anda dapat menggunakan **Finder** bawaan untuk terhubung ke layanan WebDav:

1. Buka **Finder**.
2. Di bilah menu, klik **Go** dan pilih **Connect to Server…** (atau tekan `Command + K`).
3. Masukkan alamat yang ditampilkan di aplikasi ke kolom alamat, misalnya `http://192.168.1.100:8080`.
4. Klik **Connect**.
5. Jika diminta, masukkan nama pengguna dan kata sandi Anda, atau sambungkan sebagai tamu.
6. Setelah terhubung, layanan WebDav akan muncul di Finder sebagai drive jaringan, dan Anda dapat mengakses serta mengelola data seperti folder lokal.

### Linux

Di Linux (menggunakan desktop Ubuntu sebagai contoh), Anda dapat menggunakan pengelola file bawaan untuk terhubung:

1. Buka aplikasi **Files**.
2. Klik **Other Locations** di bilah sisi kiri.
3. Temukan kolom **Connect to Server** di bagian bawah.
4. Masukkan alamat dengan format `dav://IP:port`, misalnya `dav://192.168.1.100:8080`.
5. Klik **Connect**.
6. Jika diminta, masukkan nama pengguna dan kata sandi Anda, atau sambungkan secara anonim.
7. Setelah terhubung, layanan WebDav akan muncul di pengelola file sebagai lokasi jaringan.
