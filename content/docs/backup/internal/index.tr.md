---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

Uygulama, bölüm verilerinizi düzenli olarak bir .zip dosyasına sıkıştıran dahili bir yedekleme mekanizması sunar.

# Uygulama kaldırılırsa dahili yedek dosyaları kaybolur

Yerleşik mekanizma, yedek .zip dosyalarını uygulamaya özel bir klasörde saklar. Uygulama kaldırıldığında bu klasör de diğer uygulama verileriyle birlikte silinir.

Bu nedenle verilerinizi güvende tutmak için yalnızca bu mekanizmaya güvenmeyin. Bu sistem tek yedekleme yönteminizi oluşturmak için tasarlanmamıştır.

# Nasıl çalışır

Uygulamadan çıktığınızda veya her gün planlanan saatte, uygulama henüz yedeklenmemiş değişiklikler olup olmadığını kontrol eder. Varsa, yedekleme işlemi başlatılır. Varsayılan olarak iki yedekleme işlemi arasında en az 8 saat bulunur.

Yeni bir zip dosyası oluşturulduktan sonra uygulama eski yedek verilerini kontrol eder ve gerekirse bunları siler. Varsayılan olarak uygulama en yeni 20 yedek dosyasını tutar, bu yüzden yedeklerin çok fazla depolama alanı kaplaması konusunda endişelenmeniz gerekmez.

Google Drive veya cihaz depolama yedeği gibi başka yedekleme hizmetleri yapılandırdıysanız, en son zip dosyası buralara da yüklenir.
