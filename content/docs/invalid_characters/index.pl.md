---
ShowToc: true
title: Niedozwolone znaki w nazwach plików
---

Aplikacja zapisuje notatki, rozdziały, powieści i inne treści w plikach tekstowych. Zwykły tekst zapewnia szeroką zgodność i wygodne korzystanie z danych na różnych platformach. Nawet jeśli kiedyś przestaniesz używać tej aplikacji, nadal łatwo otworzysz, uporządkujesz i edytujesz swoje pliki w innych aplikacjach i systemach operacyjnych.

## Znaki niedozwolone w nazwach plików: `\/:*?"<>|`

W systemach plików i wielu popularnych programach znaki te mają specjalne znaczenie. Użycie ich w nazwie może utrudnić spójne tworzenie, wyszukiwanie lub otwieranie plików na różnych urządzeniach. Na przykład `/` oddziela foldery w ścieżce, a `\` w niektórych systemach również pełni rolę separatora ścieżki i w wybranych formatach tekstowych służy do ucieczki znaków. Pozostałe znaki mogą działać jako symbole wieloznaczne, separatory lub znaki sterujące. Aby pliki działały bezproblemowo na różnych platformach, aplikacja nie pozwala używać tych znaków w nazwach.

## Dlaczego nazwa pliku nie może zaczynać się od `.` ani `..`?

Android bazuje na jądrze Linux. W ścieżkach w stylu Linux `.` oznacza bieżący folder, a `..` folder nadrzędny. Ponadto narzędzia systemów Linux i Android zwykle traktują pliki i foldery, których nazwy zaczynają się od kropki, jako ukryte. Aplikacja nie pozwala więc rozpoczynać nazwy od kropki, aby uniknąć pomyłek ze specjalnymi elementami ścieżki i zachować widoczność oraz łatwość odnajdywania plików.
