---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Usługa wewnętrznej kopii zapasowej
---

Aplikacja oferuje wewnętrzny mechanizm kopii zapasowej, który okresowo kompresuje dane Twoich rozdziałów do pliku .zip.

# Wewnętrzne pliki kopii zapasowej zostaną utracone po odinstalowaniu aplikacji

Wbudowany mechanizm zapisuje pliki kopii zapasowej .zip w prywatnym folderze aplikacji. Ten folder, wraz z innymi danymi aplikacji, zostanie usunięty po odinstalowaniu aplikacji.

Dlatego nie polegaj wyłącznie na tym mechanizmie, aby chronić swoje dane. Nie został on zaprojektowany jako jedyna metoda tworzenia kopii zapasowej.

# Jak to działa

Gdy opuszczasz aplikację lub nadejdzie zaplanowana pora każdego dnia, aplikacja sprawdza, czy są jakieś zmiany, które nie zostały jeszcze uwzględnione w kopii zapasowej. Jeśli tak, uruchamiany jest proces tworzenia kopii zapasowej. Domyślnie między dwoma procesami tworzenia kopii zapasowej musi minąć co najmniej 8 godzin.

Po utworzeniu nowego pliku zip aplikacja sprawdza stare dane kopii zapasowych i usuwa je w razie potrzeby. Domyślnie aplikacja zachowuje 20 najnowszych plików kopii zapasowej, więc nie musisz się martwić, że kopie zajmą zbyt dużo miejsca.

Jeśli masz skonfigurowane inne usługi kopii zapasowej, takie jak Google Drive lub kopia zapasowa pamięci urządzenia, najnowszy plik zip również zostanie tam przesłany.
