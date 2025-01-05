---
title: Verileri nasıl senkronize edebilirim  
date: 2024-09-20  
ShowToc: true  
---

Teknik olarak, uygulamamız cihazlar arasında veri senkronizasyonunu desteklememektedir. Verilerinizi bir cihazdan diğerine aktarmak için yedekleme özelliğini kullanabilirsiniz, ancak bu işlem senkronizasyon olarak adlandırılamaz.

Bununla birlikte, uygulama dışında veri senkronizasyonunu gerçekleştirmek için birkaç yol bulunmaktadır.

# Uygulamanın Ana Klasörü Olarak Bir Depolama Klasörü Ayarlayın

Cihazınızdaki bir depolama klasörünü uygulamanın ana klasörü olarak ayarlayabilirsiniz. Bu ayarda, kitaplarınız ve bölümleriniz, depolama klasöründe alt klasörler ve metin dosyaları olarak kaydedilir.

Veriler zaten dosya olarak saklandığından, harici dosya senkronizasyon araçlarını kullanarak bu verileri cihazlar arasında senkronize edebilirsiniz.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing, yaygın olarak kullanılan, platformlar arası bir veri senkronizasyon aracıdır. Mobil cihazlarınız, PC’niz, dizüstü bilgisayarınız veya ev sunucunuz arasında uygulamanızın verilerini senkronize etmek için Syncthing'i kullanabilirsiniz.

Syncthing'in nasıl kurulacağını öğrenmek için resmi rehberine göz atın:

[Syncthing - Başlarken](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Ağ Diskleri

Bazı ağ diskleri, çift yönlü dosya senkronizasyon özelliği sunmaktadır. Uygulamanızın ana klasörünü senkronizasyon klasörü olarak ayarlayarak, verilerinizi cihazlar arasında senkronize edebilirsiniz. Ayrıca bu durumda ağ diski bir yedekleme sunucusu olarak da işlev görebilir.

# Git, SVN ve Rsync

Programlama bilgisine sahip olanlar için bu yöntem tavsiye edilir. Termux gibi uygulamaları kullanarak veri senkronizasyonu için komut satırı araçlarını çalıştırabilirsiniz.

Git, SVN veya Rsync ile aşina iseniz, bu yöntem büyük bir esneklik sunar. Ancak, bu araçlara aşina değilseniz, bu yöntemi önermeyiz çünkü Git, SVN veya komut satırları genel kullanıcılar için uygun değildir.

# Özet

Uygulamanın temel amacı, kullanıcıların verilerini güvende tutmaktır. İki istemci uygulaması arasında veri senkronizasyonu her zaman güvenli olmadığından, yerleşik bir senkronizasyon özelliği geliştirmedik. Bunun yerine, veri senkronizasyonu için güvenilir, profesyonel araçların kullanılmasını öneriyoruz.
