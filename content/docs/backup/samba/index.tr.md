---
ShowToc: true
date: 2026-10-31
title: Samba yedekleme hizmeti
---

Samba, yerel ağlar (LAN) için evrensel bir dosya paylaşım protokolüdür ve çok çeşitli cihaz ve sistemlerle sorunsuz çalışır.

# Giriş parametrelerini anlama

- **Ana bilgisayar adı veya IP adresi**: Samba sunucusunu çalıştıran cihazın adresi.
- **Port**: Samba sunucusunun portu. Varsayılan **445**'tir.
- **Samba paylaşım adı**: Bir Samba sunucusunda birden fazla paylaşım ayarı olabilir; bu yüzden hangi paylaşımın kullanılacağını belirtmeniz gerekir.
- **Depolama klasörü yolu**: Paylaşım içindeki depolama yolu. Boş bırakılabilir. Yedekler bu yolun altına kaydedilir; boşsa paylaşımın kök dizini kullanılır.
- **Kullanıcı adı**: Kullanıcı adı, boş olamaz.
- **Şifre**: Şifre, boş olamaz.
- **Kısıtlı WiFi SSID**: Yedeklemeyi belirli bir WiFi ağıyla sınırlar. Herhangi bir WiFi'de yedeklemeye izin vermek için boş bırakın veya yalnızca o ağda çalışması için bir SSID girin. Samba, yerel ağ üzerinden dosya paylaşmak için kullanıldığından bu seçenek yedeklerinizi güvenilir bir WiFi'de tutar.
