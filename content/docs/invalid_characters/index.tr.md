---
ShowToc: true
title: Dosya adlarında kullanılamayan karakterler
---

Bu uygulama notlarınızı, bölümlerinizi, romanlarınızı ve diğer içeriklerinizi metin dosyalarında saklar. Düz metin kullanmamızın nedeni, farklı platformlarda geniş uyumluluk sağlamaktır. Böylece uygulamayı kullanmayı bıraksanız bile dosyalarınızı başka uygulamalarda ve işletim sistemlerinde kolayca yönetip düzenleyebilirsiniz.

## Dosya adlarında kullanılamayan karakterler: `\/:*?"<>|`

Bu karakterlerin dosya sistemlerinde ve yaygın yazılımlarda özel işlevleri vardır. Dosya adlarında kullanıldıklarında, dosyaların farklı cihazlarda tutarlı biçimde oluşturulmasını, bulunmasını veya açılmasını zorlaştırabilirler. Örneğin `/`, dosya yolundaki klasörleri ayırır; `\` ise bazı sistemlerde yol ayırıcı, bazı metin biçimlerinde kaçış karakteri olarak kullanılır. Diğer karakterler de joker, ayraç veya kontrol simgesi işlevi görebilir. Dosyalarınızın farklı platformlarda sorunsuz kullanılabilmesi için uygulama bu karakterlerin dosya adlarında kullanılmasına izin vermez.

## Dosya adları neden `.` veya `..` ile başlayamaz?

Android, Linux çekirdeği temel alınarak geliştirilmiştir. Linux tarzı yollarda `.` geçerli klasörü, `..` ise üst klasörü belirtir. Ayrıca Linux ve Android araçları, adı noktayla başlayan dosya ve klasörleri genellikle gizli kabul eder. Uygulama, özel yol bileşenleriyle karışıklığı önlemek ve dosyalarınızı görünür, bulunması kolay halde tutmak için adların noktayla başlamasına izin vermez.
