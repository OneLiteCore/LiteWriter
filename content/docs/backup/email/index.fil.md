---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Serbisyo ng backup sa email
---

Ginagamit ng email backup service ang sarili mong email account upang magpadala ng mga backup file bilang mga attachment sa sarili mong mailbox. Ibig sabihin, nananatili ang mga backup file sa isang email account na ikaw mismo ang may kontrol, kaya mas pribado ito at buo ang pagmamay-ari mo sa iyong backup data.

Mahalaga sa amin ang iyong privacy. Hinding-hindi ia-upload ng app ang iyong email address, at hinding-hindi nito aabusuhin, kokolektahin, o nanakawin ang iyong password.

# Bakit kailangan mo ng app password sa halip na iyong email password

Karamihan sa mga email provider ay hindi pinapayagan ang mga third-party app na mag-sign in gamit ang normal mong email password. Isa itong karaniwang patakaran sa seguridad na tumutulong mabawasan ang panganib ng pagtagas ng password at pang-aabuso sa account.

Dahil dito, karaniwan mong kailangang gumawa ng third-party app password o client-specific password sa mga setting ng iyong email account, at pagkatapos ay iyon ang gamitin sa app sa halip na ang regular mong email password.

# Mga help document ng mga karaniwang email provider

- [Help document ng Gmail](https://support.google.com/mail/answer/185833)
- [Help document ng QQ Mail](https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode)

# Pag-unawa sa mga parameter sa pag-login

- **IMAP server address**: Ang server na ginagamit upang tumanggap at magbasa ng mga email.
- **IMAP port**: Ang network port na ginagamit ng IMAP. Ang default na IMAP port ay karaniwang **993**.
- **SMTP server address**: Ang server na ginagamit upang magpadala ng mga email.
- **SMTP port**: Ang network port na ginagamit ng SMTP. Ang default na SMTP port ay karaniwang **465** o **587**.
- **STARTTLS**: Isang security feature na nag-a-upgrade ng plain na koneksyon tungo sa naka-encrypt na TLS connection pagkatapos magsimula ang koneksyon. Kung ang SMTP port ay nakatakda sa **587**, io-on at ioobliga ng app ang paggamit ng **STARTTLS** bilang default.
- **Email address**: Ang email account na nagpapadala ng backup email at siya ring tumatanggap nito.
- **Third-party app password**: Isang password na ginagawa ng iyong email provider para sa mga external app. Sa karamihan ng sitwasyon, hindi mo maaaring gamitin dito ang normal mong email password, dahil karaniwang hinaharang ng mga provider ang direktang password sign-in para sa mga third-party app dahil sa mga kadahilanang panseguridad.
