---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Perkhidmatan sandaran e-mel
---

Perkhidmatan sandaran e-mel menggunakan akaun e-mel anda sendiri untuk menghantar fail sandaran sebagai lampiran ke peti mel anda sendiri. Ini memastikan fail sandaran kekal dalam akaun e-mel yang memang anda kawal, sekali gus memberikan privasi yang lebih baik dan pemilikan penuh ke atas data sandaran anda.

Kami sangat mengambil berat tentang privasi anda. Aplikasi ini tidak akan sekali-kali memuat naik alamat e-mel anda, dan tidak akan sekali-kali menyalahgunakan, mengumpul, atau mencuri kata laluan anda.

# Mengapa anda memerlukan kata laluan aplikasi dan bukan kata laluan e-mel anda

Kebanyakan penyedia e-mel tidak membenarkan aplikasi pihak ketiga log masuk menggunakan kata laluan e-mel biasa anda. Ini ialah dasar keselamatan yang lazim digunakan untuk membantu mengurangkan risiko kebocoran kata laluan dan penyalahgunaan akaun.

Oleh sebab itu, anda biasanya perlu mencipta kata laluan aplikasi pihak ketiga atau kata laluan khusus klien dalam tetapan akaun e-mel anda, kemudian menggunakan kata laluan itu dalam aplikasi dan bukannya kata laluan e-mel biasa anda.

# Dokumen bantuan untuk penyedia e-mel yang biasa digunakan

- Dokumen bantuan Gmail: https://support.google.com/mail/answer/185833
- Dokumen bantuan QQ Mail: https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode

# Memahami parameter log masuk

- **Alamat pelayan IMAP**: Pelayan yang digunakan untuk menerima dan membaca e-mel.
- **Port IMAP**: Port rangkaian yang digunakan oleh IMAP. Port IMAP lalai biasanya ialah **993**.
- **Alamat pelayan SMTP**: Pelayan yang digunakan untuk menghantar e-mel.
- **Port SMTP**: Port rangkaian yang digunakan oleh SMTP. Port SMTP lalai biasanya ialah **465** atau **587**.
- **STARTTLS**: Ciri keselamatan yang menaik taraf sambungan biasa kepada sambungan TLS yang disulitkan selepas sambungan dimulakan. Jika port SMTP ditetapkan kepada **587**, aplikasi akan mengaktifkan dan mewajibkan **STARTTLS** secara lalai.
- **Alamat e-mel**: Akaun e-mel yang menghantar e-mel sandaran dan juga menerimanya.
- **Kata laluan aplikasi pihak ketiga**: Kata laluan yang dijana oleh penyedia e-mel anda untuk aplikasi luaran. Dalam kebanyakan keadaan, anda tidak boleh menggunakan kata laluan e-mel biasa anda di sini, kerana penyedia biasanya menyekat log masuk terus menggunakan kata laluan untuk aplikasi pihak ketiga atas sebab keselamatan.
