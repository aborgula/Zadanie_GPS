#  Zadanie GPS – Android Google Maps

Aplikacja mobilna na system Android, która wyświetla mapę Google i umożliwia śledzenie aktualnej lokalizacji użytkownika za pomocą GPS, wizualizację pozycji na mapie z wykorzystaniem wygładzania danych oraz ręczne wskazanie dowolnej lokalizacji poprzez podanie współrzędnych geograficznych.

> Projekt został wykonany w celach edukacyjnych w czasie prakyk studenckich w dziale aplikacji mobilnych.

---

##  Funkcjonalności

- Wyświetlanie mapy Google Maps
- Pobieranie aktualnej lokalizacji GPS użytkownika
- Automatyczna aktualizacja pozycji co 10 sekund
- Symulacja ruchu użytkownika (losowa zmiana współrzędnych)
- Wygładzanie pozycji GPS poprzez uśrednianie trzech kolejnych pomiarów
- Ręczne dodawanie znacznika na mapie na podstawie wpisanych współrzędnych
- Obsługa uprawnień lokalizacji (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`)

---

##  Zasada działania

W trybie GPS aplikacja cyklicznie pobiera ostatnią znaną lokalizację użytkownika i symuluje niewielkie zmiany pozycji. Dla zwiększenia stabilności wyświetlanej lokalizacji, pozycja jest obliczana jako średnia z trzech kolejnych punktów GPS.

Alternatywnie użytkownik może wyłączyć tryb GPS i wskazać wybraną lokalizację, wpisując jej szerokość i długość geograficzną.

---

##  Wykorzystane technologie

- **Java**
- **Android SDK**
- **Google Maps SDK for Android**
- **FusedLocationProviderClient**
- **Android Studio**

---

##  Uruchomienie projektu

1. Uruchom Android Studio
2. Kliknij File -> New -> Project from version control
3. Wklej w pole URL https://github.com/twoj-login/zad1-gps.git
4. Uruchom aplikację na emulatorze lub urządzeniu fizycznym

---
