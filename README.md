# Kalkulator Półek

Prosty kalkulator rozstawu półek w szafkach.

## Jak używać

1. Otwórz `index.html` w przeglądarce.
2. Wpisz wysokość szafki, liczbę półek i grubość półek.
3. Kliknij "Oblicz".
4. Wyniki pojawią się na ekranie oraz w wizualizacji szafki.

## Folder kody/

Zawiera wcześniejsze wersje kalkulatora:
- `wersja_podstawowa.html`
- `wersja_grafika.html`
- `wersja_etykiety_pod_polką.html`

## APK

Aby utworzyć APK:
1. Otwórz Android Studio i utwórz Empty Activity.
2. Skopiuj pliki HTML i grafiki do `assets/`.
3. W `MainActivity` użyj WebView aby ładować `index.html`.
4. Build > Build APK.
