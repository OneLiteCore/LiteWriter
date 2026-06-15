---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Layanan cadangan email
---

Layanan cadangan email menggunakan akun email Anda sendiri untuk mengirim file cadangan sebagai lampiran ke kotak masuk Anda sendiri. Ini membuat file cadangan tetap berada di akun email yang sudah Anda kendalikan, sehingga memberi Anda privasi yang lebih baik dan kepemilikan penuh atas data cadangan Anda.

Kami sangat peduli pada privasi Anda. Aplikasi tidak akan pernah mengunggah alamat email Anda, dan tidak akan pernah menyalahgunakan, mengumpulkan, atau mencuri kata sandi Anda.

# Mengapa Anda memerlukan kata sandi aplikasi, bukan kata sandi email Anda

Sebagian besar penyedia email tidak mengizinkan aplikasi pihak ketiga masuk menggunakan kata sandi email biasa Anda. Ini adalah kebijakan keamanan umum yang membantu mengurangi risiko kebocoran kata sandi dan penyalahgunaan akun.

Karena itu, biasanya Anda perlu membuat kata sandi aplikasi pihak ketiga atau kata sandi khusus klien di pengaturan akun email Anda, lalu menggunakan kata sandi tersebut di aplikasi, bukan kata sandi email biasa Anda.

# Dokumen bantuan untuk penyedia email umum

- Dokumen bantuan Gmail: https://support.google.com/mail/answer/185833
- Dokumen bantuan QQ Mail: https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode

# Memahami parameter login

- **Alamat server IMAP**: Server yang digunakan untuk menerima dan membaca email.
- **Port IMAP**: Port jaringan yang digunakan oleh IMAP. Port IMAP default biasanya adalah **993**.
- **Alamat server SMTP**: Server yang digunakan untuk mengirim email.
- **Port SMTP**: Port jaringan yang digunakan oleh SMTP. Port SMTP default biasanya adalah **465** atau **587**.
- **STARTTLS**: Fitur keamanan yang meningkatkan koneksi biasa menjadi koneksi TLS terenkripsi setelah koneksi dimulai. Jika port SMTP diatur ke **587**, aplikasi akan mengaktifkan dan mewajibkan **STARTTLS** secara default.
- **Alamat email**: Akun email yang mengirim email cadangan dan juga menerimanya.
- **Kata sandi aplikasi pihak ketiga**: Kata sandi yang dibuat oleh penyedia email Anda untuk aplikasi eksternal. Dalam kebanyakan kasus, Anda tidak dapat menggunakan kata sandi email biasa Anda di sini, karena penyedia biasanya memblokir login kata sandi langsung untuk aplikasi pihak ketiga demi alasan keamanan.
