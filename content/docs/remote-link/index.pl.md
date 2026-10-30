---
ShowToc: true
date: 2024-05-25
title: Jak korzystać z funkcji Remote Link
---

Funkcja "Link" umożliwia zmapowanie danych aplikacji jako katalogu na komputerze, dzięki czemu możesz używać oprogramowania PC do edycji i zarządzania swoimi danymi.

Ta funkcja opiera się na ogólnym protokole **WebDav**. Większość systemów operacyjnych powinna obsługiwać go od razu, ale korzystanie z niego może nie być takie proste. Oto więc prostszy sposób.

## Windows

Na platformie Windows polecamy oprogramowanie innych firm **RaiDrive**. Możesz je pobrać, klikając poniższy link:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(Wersja 1.8.0 nie jest najnowsza, ale ma wszystko, czego potrzebujemy, a co ważniejsze, nie ma reklam)

Zainstaluj i otwórz; możesz zobaczyć panel taki jak ten. Po prostu postępuj zgodnie ze wskazówkami:

![RaiDrive setup](/img/add_drive.webp)

1. Kliknij przycisk "Add" u góry, aby przejść do konfiguracji.
2. Przejdź do karty "NAS" i wybierz opcję WebDav
3. Wpisz nazwę dysku według własnego uznania
4. Wpisz adres
    - obok tekstu "address" możesz zobaczyć pole wyboru; pozostaw je **ODZNACZONE**, abyśmy mogli użyć adresu http.
    - Wpisz adres IP i numer portu, które znajdziesz po włączeniu funkcji linku w aplikacji.
5. Wpisz własną nazwę użytkownika i hasło, jeśli je masz; w przeciwnym razie zaznacz pole "Anonymous"
6. Kliknij przycisk "OK", aby rozpocząć mapowanie

Jeśli wszystko pójdzie dobrze, możesz zobaczyć to:

![Done](/img/done.webp)

## Linux lub MacOS

### MacOS

W systemie macOS możesz użyć wbudowanego **Findera**, aby połączyć się z usługą WebDav:

1. Otwórz **Finder**.
2. Na pasku menu kliknij **Go** i wybierz **Connect to Server…** (lub naciśnij `Command + K`).
3. Wpisz w polu adresu adres pokazany w aplikacji, na przykład `http://192.168.1.100:8080`.
4. Kliknij **Connect**.
5. Jeśli pojawi się monit, wpisz swoją nazwę użytkownika i hasło albo połącz się jako gość.
6. Po nawiązaniu połączenia usługa WebDav pojawi się w Finderze jako dysk sieciowy i będziesz mógł uzyskiwać dostęp do swoich danych oraz nimi zarządzać jak folderem lokalnym.

### Linux

W systemie Linux (na przykładzie pulpitu Ubuntu) możesz użyć wbudowanego menedżera plików, aby się połączyć:

1. Otwórz aplikację **Files**.
2. Kliknij **Other Locations** na lewym pasku bocznym.
3. Znajdź pole **Connect to Server** na dole.
4. Wpisz adres w formacie `dav://IP:port`, na przykład `dav://192.168.1.100:8080`.
5. Kliknij **Connect**.
6. Jeśli pojawi się monit, wpisz swoją nazwę użytkownika i hasło albo połącz się anonimowo.
7. Po nawiązaniu połączenia usługa WebDav pojawi się w menedżerze plików jako lokalizacja sieciowa.
