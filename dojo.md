# Projekt: Dojo – Platforma dla dydaktyków

## Opis projektu
**Dojo** to projekt przeznaczony dla dydaktyków, którego celem jest stworzenie ujednoliconego środowiska do prowadzenia zajęć programistycznych z wykorzystaniem **GitHub** oraz **GitHub Classroom**. System ma wspierać:
- zarządzanie zadaniami studenckimi,
- automatyczną weryfikację rozwiązań,
- automatyczne informowanie studentów i wykładowców o wynikach,
- monitorowanie postępów nauki.

Dojo będzie zawierać zestaw narzędzi, skryptów oraz pipeline’ów CI/CD, które umożliwią dydaktykom łatwe tworzenie, uruchamianie i utrzymywanie procesów oceny zadań programistycznych.

## Cele projektu
- Uspójnienie sposobu prowadzenia zajęć programistycznych na uczelni.
- Automatyzacja sprawdzania zadań domowych i laboratoryjnych.
- Zapewnienie przejrzystego i mierzalnego obrazu postępów studentów.
- Odciążenie dydaktyków od ręcznego sprawdzania podstawowych aspektów zadań (testy, kompilacja, formatowanie, styl).

## Integracja z GitHub i GitHub Classroom
- Wykorzystanie **GitHub Classroom** do dystrybucji zadań i tworzenia repozytoriów studenckich.
- Automatyczne wiązanie repozytoriów studenckich z procesami CI/CD.
- Centralne repozytorium „Dojo” z szablonami zadań, testami i konfiguracjami pipeline’ów.

## CI/CD zadań studenckich
System będzie oparty o pipeline’y, które:
- budują i testują rozwiązania studentów,
- uruchamiają testy jednostkowe/integracyjne,
- sprawdzają jakość kodu (lint, format, style),
- generują raport wyników,
- wysyłają powiadomienia:
  - do studenta (status zadania, błędy, sugestie),
  - do wykładowcy (zbiorczy przegląd wyników grupy).

## Wykorzystanie języka PKL
Projekt zakłada wykorzystanie języka **PKL** do definiowania pipeline’ów dla wykładowców. Dzięki temu dydaktycy otrzymują:
- deklaratywny sposób definiowania wymagań dla zadania,
- możliwość łatwej konfiguracji kroków (build, test, analiza, raport),
- gotowe szablony pipeline’ów dla różnych przedmiotów i języków programowania,
- możliwość współdzielenia i wersjonowania konfiguracji w repozytoriach Git.

## Funkcjonalności Dojo
- Szablony zadań programistycznych z gotowymi testami.
- Konfiguracje CI/CD generowane lub opisywane w PKL.
- Automatyczne raporty dla wykładowców (dashboard postępów studentów).
- Integracja z systemem powiadomień (e-mail / GitHub Issues / komentarze w PR).
- Możliwość rozszerzania o kolejne języki programowania i kursy.

## Korzyści dydaktyczne
- **Przejrzysta kontrola postępów** – wykładowca widzi, kto i kiedy oddał zadanie, jaki jest jego status oraz ile testów przeszło.
- **Feedback w czasie zbliżonym do rzeczywistego** – student otrzymuje szybkie informacje zwrotne, co ułatwia naukę przez eksperymentowanie.
- **Skalowalność** – jeden wykładowca może obsłużyć większą liczbę studentów bez spadku jakości oceny.
- **Standaryzacja** – te same kryteria oceny dla wszystkich grup, roczników i kierunków.

## Możliwe rozszerzenia
- Integracja z uczelnianym systemem (np. Gakko) w celu synchronizacji list studentów i ocen.
- Moduł analityczny (statystyki, wykresy, identyfikacja problematycznych zagadnień).
- Generowanie automatycznych rekomendacji materiałów dla studentów na podstawie wyników.

## Efekty projektu
- Gotowy zestaw skryptów i pipeline’ów CI/CD do obsługi zadań studenckich.
- Dokumentacja dla dydaktyków (jak tworzyć nowe zadania, pipeline’y w PKL, interpretować raporty).
- Przykładowe kursy i zadania wdrożone w Dojo.

