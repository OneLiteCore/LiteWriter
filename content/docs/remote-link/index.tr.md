---
ShowToc: true
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

### MacOS

macOS'ta WebDav hizmetine bağlanmak için yerleşik **Finder**'ı kullanabilirsiniz:

1. **Finder**'ı açın.
2. Menü çubuğunda **Go**'ya tıklayın ve **Connect to Server…** öğesini seçin (veya `Command + K` tuşlarına basın).
3. Adres alanına uygulamada gösterilen adresi girin, örneğin `http://192.168.1.100:8080`.
4. **Connect**'e tıklayın.
5. İstenirse kullanıcı adınızı ve şifrenizi girin veya misafir olarak bağlanın.
6. Bağlandıktan sonra WebDav hizmeti Finder'da bir ağ sürücüsü olarak görünür ve verilerinize yerel bir klasör gibi erişip yönetebilirsiniz.

### Linux

Linux'ta (örnek olarak Ubuntu masaüstü kullanılarak) bağlanmak için yerleşik dosya yöneticisini kullanabilirsiniz:

1. **Files** uygulamasını açın.
2. Sol kenar çubuğundaki **Other Locations** öğesine tıklayın.
3. Alttaki **Connect to Server** alanını bulun.
4. Adresi `dav://IP:port` biçiminde girin, örneğin `dav://192.168.1.100:8080`.
5. **Connect**'e tıklayın.
6. İstenirse kullanıcı adınızı ve şifrenizi girin veya anonim olarak bağlanın.
7. Bağlandıktan sonra WebDav hizmeti dosya yöneticisinde bir ağ konumu olarak görünür.
