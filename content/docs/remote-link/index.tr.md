---
ShowToc: true
copy_mark: copied
date: 2024-05-25
title: Uzak Bağlantı özelliği nasıl kullanılır
---

"Bağlantı" özelliği, uygulama verilerini bir PC dizini olarak eşleştirmenizi sağlar; böylece verilerinizi düzenlemek ve yönetmek için PC yazılımını kullanabilirsiniz.

Bu özellik, genel **WebDav** protokolünü temel alır. Çoğu işletim sistemi bunu kutudan çıktığı gibi desteklemelidir, ancak kullanımı o kadar kolay olmayabilir. İşte burada daha kolay bir yol var.

## Windows

Windows platformunda üçüncü taraf yazılım olan **RaiDrive**'ı öneriyoruz. Aşağıdaki bağlantıya tıklayarak indirebilirsiniz:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(1.8.0 sürümü en son sürüm değildir, ancak ihtiyacımız olan her şeye sahiptir ve daha da önemlisi reklam içermez)

Kurup açın; bunun gibi bir panel görebilirsiniz, yalnızca ipuçlarını izleyin:

![RaiDrive setup](/img/add_drive.webp)

1. Yapılandırmaya girmek için üstteki "Add" düğmesine tıklayın.
2. "NAS" sekmesine gidin ve WebDav seçeneğini seçin
3. Sürücü adını istediğiniz gibi girin
4. Adresi girin
    - "address" metninin yanında bir onay kutusu görebilirsiniz; http url'si kullanabilmemiz için onu **İŞARETSİZ** bırakın.
    - Uygulamada bağlantı özelliğini açtığınızda bulabileceğiniz IP adresini ve bağlantı noktası numarasını girin.
5. Varsa özel kullanıcı adınızı ve şifrenizi girin; yoksa "Anonymous" onay kutusunu işaretleyin
6. Eşleştirmeyi başlatmak için "OK" düğmesine tıklayın

Her şey yolunda giderse şunu görebilirsiniz:

![Done](/img/done.webp)

## Linux veya MacOS

Tamamlanmayı bekliyor.
