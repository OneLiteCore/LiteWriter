---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Usługa kopii zapasowej przez e-mail
---

Usługa kopii zapasowej przez e-mail używa Twojego własnego konta e-mail do wysyłania plików kopii zapasowej jako załączników do Twojej własnej skrzynki pocztowej. Dzięki temu pliki kopii zapasowej pozostają na koncie e-mail, które już samodzielnie kontrolujesz, co zapewnia lepszą prywatność i pełną własność danych kopii zapasowej.

Bardzo dbamy o Twoją prywatność. Aplikacja nigdy nie prześle Twojego adresu e-mail i nigdy nie nadużyje, nie zbierze ani nie ukradnie Twojego hasła.

# Dlaczego potrzebujesz hasła aplikacji zamiast hasła do e-maila

Większość dostawców poczty e-mail nie pozwala aplikacjom firm trzecich logować się przy użyciu zwykłego hasła do Twojej poczty. To powszechna polityka bezpieczeństwa, która pomaga zmniejszyć ryzyko wycieku haseł i nadużyć kont.

Dlatego zwykle musisz utworzyć w ustawieniach konta e-mail hasło aplikacji firm trzecich lub hasło przeznaczone dla konkretnego klienta, a następnie użyć go w aplikacji zamiast zwykłego hasła do poczty.

# Dokumenty pomocy dla popularnych dostawców poczty e-mail

- [Dokument pomocy Gmail](https://support.google.com/mail/answer/185833)
- [Dokument pomocy QQ Mail](https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode)

# Zrozumienie parametrów logowania

- **Adres serwera IMAP**: Serwer używany do odbierania i odczytywania wiadomości e-mail.
- **Port IMAP**: Port sieciowy używany przez IMAP. Domyślny port IMAP to zwykle **993**.
- **Adres serwera SMTP**: Serwer używany do wysyłania wiadomości e-mail.
- **Port SMTP**: Port sieciowy używany przez SMTP. Domyślny port SMTP to zwykle **465** lub **587**.
- **STARTTLS**: Funkcja bezpieczeństwa, która po rozpoczęciu połączenia podnosi zwykłe połączenie do szyfrowanego połączenia TLS. Jeśli port SMTP jest ustawiony na **587**, aplikacja domyślnie włączy i będzie wymagać **STARTTLS**.
- **Adres e-mail**: Konto e-mail, które wysyła wiadomość z kopią zapasową i jednocześnie ją odbiera.
- **Hasło aplikacji firm trzecich**: Hasło generowane przez dostawcę poczty dla zewnętrznych aplikacji. W większości przypadków nie możesz użyć tutaj zwykłego hasła do swojej poczty, ponieważ dostawcy zwykle blokują bezpośrednie logowanie hasłem w aplikacjach firm trzecich ze względów bezpieczeństwa.
