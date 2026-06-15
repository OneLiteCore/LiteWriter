---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: E-posta yedekleme hizmeti
---

E-posta yedekleme hizmeti, yedek dosyalarını ek olarak kendi posta kutunuza göndermek için kendi e-posta hesabınızı kullanır. Bu sayede yedek dosyaları zaten sizin kontrolünüzde olan bir e-posta hesabında kalır; bu da size daha iyi gizlilik ve yedek verileriniz üzerinde tam sahiplik sağlar.

Gizliliğinizi çok önemsiyoruz. Uygulama e-posta adresinizi asla yüklemeyecek, parolanızı da asla kötüye kullanmayacak, toplamayıp çalmayacaktır.

# E-posta parolanız yerine neden bir uygulama parolasına ihtiyacınız var

Çoğu e-posta sağlayıcısı, üçüncü taraf uygulamaların normal e-posta parolanızla oturum açmasına izin vermez. Bu, parola sızıntısı ve hesap kötüye kullanımı riskini azaltmaya yardımcı olan yaygın bir güvenlik politikasıdır.

Bu nedenle genellikle e-posta hesabı ayarlarınızda bir üçüncü taraf uygulama parolası veya istemciye özel parola oluşturmanız ve ardından normal e-posta parolanız yerine uygulamada bu parolayı kullanmanız gerekir.

# Yaygın e-posta sağlayıcıları için yardım belgeleri

- Gmail yardım belgesi: https://support.google.com/mail/answer/185833
- QQ Mail yardım belgesi: https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode

# Giriş parametrelerini anlama

- **IMAP sunucu adresi**: E-postaları almak ve okumak için kullanılan sunucudur.
- **IMAP portu**: IMAP tarafından kullanılan ağ portudur. Varsayılan IMAP portu genellikle **993**'tür.
- **SMTP sunucu adresi**: E-postaları göndermek için kullanılan sunucudur.
- **SMTP portu**: SMTP tarafından kullanılan ağ portudur. Varsayılan SMTP portu genellikle **465** veya **587**'dir.
- **STARTTLS**: Bağlantı başladıktan sonra düz bir bağlantıyı şifrelenmiş bir TLS bağlantısına yükselten bir güvenlik özelliğidir. SMTP portu **587** olarak ayarlanmışsa uygulama varsayılan olarak **STARTTLS**'i etkinleştirir ve zorunlu kılar.
- **E-posta adresi**: Yedekleme e-postasını gönderen ve aynı zamanda alan e-posta hesabıdır.
- **Üçüncü taraf uygulama parolası**: E-posta sağlayıcınızın harici uygulamalar için oluşturduğu paroladır. Çoğu durumda burada normal e-posta parolanızı kullanamazsınız, çünkü sağlayıcılar güvenlik nedeniyle üçüncü taraf uygulamalar için doğrudan parola ile oturum açmayı genellikle engeller.
