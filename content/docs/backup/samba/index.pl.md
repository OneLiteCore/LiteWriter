---
ShowToc: true
date: 2026-10-31
title: Usługa kopii zapasowej Samba
---

Samba to uniwersalny protokół udostępniania plików dla sieci lokalnych (LAN), który dobrze współpracuje z wieloma różnymi urządzeniami i systemami.

# Zrozumienie parametrów logowania

- **Nazwa hosta lub adres IP**: Adres urządzenia, na którym działa serwer Samba.
- **Port**: Port serwera Samba. Domyślnie **445**.
- **Nazwa udziału Samba**: Serwer Samba może mieć kilka konfiguracji udziałów, więc musisz wskazać, który udział ma być używany.
- **Ścieżka folderu przechowywania**: Ścieżka przechowywania wewnątrz udziału. Może pozostać pusta. Kopie zapasowe są zapisywane w tej ścieżce; jeśli jest pusta, używany jest katalog główny udziału.
- **Nazwa użytkownika**: Nazwa użytkownika, która nie może być pusta.
- **Hasło**: Hasło, które nie może być puste.
- **Ograniczony SSID WiFi**: Ogranicza kopię zapasową do konkretnej sieci WiFi. Pozostaw puste, aby zezwolić na kopie w dowolnym WiFi, lub podaj SSID, aby kopia działała tylko w tej sieci. Ponieważ Samba służy do udostępniania plików w sieci lokalnej, dzięki temu Twoje kopie pozostają w zaufanym WiFi.
