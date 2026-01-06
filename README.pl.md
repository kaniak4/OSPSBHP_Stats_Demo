# OSPSBHP - Dashboard i System Zarządzania Raportami

> **Note:** For English documentation, see [README.md](./README.md).

## Opis

Platforma do zarządzania i wizualizacji raportów oddziałów OSPSBHP (Ogólnopolskiego Stowarzyszenia Pracowników Służby BHP) (https://ospsbhp.pl) z interaktywnym dashboardem i generowaniem dokumentów PDF. Opracowana z własnej inicjatywy na potrzeby stowarzyszenia, którego jestem członkiem. Na etapie testowania, premierowa prezentacja 16.01.2026.

## Cel

System rozwiązuje problem kompleksowego zarządzania raportami rocznymi oddziałów organizacji branżowej OSPSBHP, umożliwiając:
- Centralne zbieranie i przetwarzanie danych z wszystkich oddziałów
- Wizualizację statystyk na interaktywnej mapie Polski i wykresach
- Generowanie raportów PDF dla pojedynczych oddziałów oraz zbiorczych ksiąg raportów
- Zarządzanie danymi członków zarządów i organizowanych wydarzeń
- Śledzenie statusów raportów (szkic, złożony, zatwierdzony, odrzucony)

> **Uwaga:** Zrzuty ekranu i podgląd dashboardu poniżej wykorzystują **dane przykładowe** do celów demonstracyjnych. Nie wyświetlane są żadne rzeczywiste dane wrażliwe. Nazwy oddziałów OSPS BHP są prawdziwe i publicznie dostępne.

## Panel Dashboardu

![Prezentacja aplikacji](./assets/dashboard.gif)

## Panel Admina

![Prezentacja aplikacji](./assets/admin.gif)

## Więcej zrzutów ekranu

Zobacz więcej zrzutów ekranu oraz wideoprezentację w folderze [assets](./assets/). Aby zobaczyć plik PDF dla oddziału Kraków, przejdź do [tego pliku](./assets/Raport_2025_Krakow.pdf).

## Tech Stack

**Frontend:**
- React 18
- Vite
- React Router DOM
- Tailwind CSS
- Recharts (wykresy)
- React Simple Maps (mapa Polski)
- React PDF Renderer (generowanie PDF)

**Backend:**
- Node.js
- Express.js
- PostgreSQL
- pg (klient PostgreSQL)

**Narzędzia:**
- Lucide React (ikony)
- clsx (warunkowe klasy CSS)

