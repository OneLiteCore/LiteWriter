---
title: Jak synchronizować dane  
date: 2024-09-20  
ShowToc: true
copy_mark: "src"
---

Technicznie rzecz biorąc, nasza aplikacja nie obsługuje synchronizacji danych między urządzeniami. Chociaż możesz użyć funkcji tworzenia kopii zapasowej, aby przenieść swoje dane z jednego urządzenia na drugie, nie można tego nazwać synchronizacją.

To powiedziawszy, istnieją jednak sposoby na synchronizację danych poza aplikacją.

# Ustaw folder jako folder domowy aplikacji

Możesz ustawić folder w pamięci urządzenia jako folder domowy aplikacji. W takim przypadku Twoje książki i rozdziały będą zapisywane jako podfoldery i pliki tekstowe w wybranym folderze.

Ponieważ są to już pliki, możesz używać narzędzi do synchronizacji plików, aby synchronizować swoje dane między urządzeniami.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing to powszechnie używane narzędzie do synchronizacji danych, obsługujące różne platformy. Możesz je wykorzystać do synchronizowania danych aplikacji między telefonami, komputerami, laptopami lub serwerem domowym.

Sprawdź oficjalny poradnik Syncthing, aby dowiedzieć się, jak go skonfigurować:

[Syncthing - Pierwsze Kroki](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Dyski sieciowe

Niektóre dyski sieciowe oferują funkcję dwukierunkowej synchronizacji plików. Ustawiając folder domowy aplikacji jako folder do synchronizacji, możesz synchronizować dane między urządzeniami, a dodatkowo dysk sieciowy może pełnić funkcję serwera kopii zapasowej.

# Git, SVN i Rsync

Dla osób znających się na programowaniu jest to zalecana metoda. Korzystając z aplikacji takich jak Termux, możesz uruchamiać narzędzia wiersza poleceń do synchronizacji danych.

Jeśli znasz Git, SVN lub Rsync, ta opcja daje dużą elastyczność. Jednak jeśli nie jesteś zaznajomiony z tymi narzędziami, nie zalecamy tej metody, ponieważ wymaga ona zaawansowanej wiedzy technicznej i nie jest przeznaczona dla zwykłych użytkowników.

# Podsumowanie

Głównym celem aplikacji jest zapewnienie bezpieczeństwa danych użytkowników. Ponieważ synchronizacja danych między dwoma aplikacjami klienckimi nie jest wystarczająco bezpieczna, zdecydowaliśmy się nie rozwijać wbudowanej funkcji synchronizacji. Zamiast tego zalecamy korzystanie z niezawodnych, profesjonalnych narzędzi do synchronizacji danych.
