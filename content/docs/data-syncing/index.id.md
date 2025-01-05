---
title: Cara Sinkronisasi Data  
date: 2024-09-20  
ShowToc: true
copy_mark: "src"
---

Secara teknis, aplikasi kami tidak mendukung sinkronisasi data antar perangkat. Meskipun Anda dapat menggunakan fitur cadangan untuk mentransfer data dari satu perangkat ke perangkat lain, ini tidak bisa disebut sebagai sinkronisasi.

Namun, ada beberapa cara untuk melakukan sinkronisasi di luar aplikasi.

# Atur Folder Penyimpanan sebagai Folder Utama Aplikasi

Anda dapat mengatur folder di penyimpanan perangkat Anda sebagai folder utama aplikasi. Dalam pengaturan ini, buku dan bab Anda akan disimpan sebagai sub-folder dan file teks di dalam folder penyimpanan.

Karena sudah disimpan sebagai file, Anda dapat menggunakan alat sinkronisasi file eksternal untuk menyinkronkan data ini di berbagai perangkat.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing adalah alat sinkronisasi data lintas platform yang banyak digunakan. Anda dapat menggunakannya untuk menyinkronkan data aplikasi Anda antara perangkat seluler, PC, laptop, atau server rumah Anda.

Lihat panduan resmi Syncthing untuk mengetahui cara mengaturnya:

[Syncthing - Memulai](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Disk Jaringan

Beberapa disk jaringan menawarkan fitur sinkronisasi file dua arah. Dengan mengatur folder utama aplikasi sebagai folder sinkronisasi, Anda dapat menyinkronkan data di berbagai perangkat, dengan manfaat tambahan menggunakan disk jaringan sebagai cadangan.

# Git, SVN, dan Rsync

Bagi yang memiliki pengetahuan pemrograman, metode ini sangat direkomendasikan. Menggunakan aplikasi seperti Termux, Anda dapat menjalankan alat baris perintah untuk sinkronisasi data.

Jika Anda sudah familiar dengan Git, SVN, atau Rsync, opsi ini memberikan fleksibilitas yang baik. Namun, jika Anda tidak familiar dengan alat ini, kami tidak merekomendasikan metode ini karena membutuhkan pengetahuan teknis lebih dan bukan untuk pengguna umum.

# Ringkasan

Tujuan utama aplikasi ini adalah menjaga keamanan data pengguna. Karena sinkronisasi data antara dua aplikasi klien tidak selalu aman, kami memilih untuk tidak mengembangkan fitur sinkronisasi bawaan. Sebagai gantinya, kami merekomendasikan penggunaan alat profesional yang andal untuk sinkronisasi data.
