# BAVARO Bistro & Pizzeria

Statyczna strona internetowa dla lokali BAVARO w Bydgoszczy — bez frameworków, bez build toola, czysty HTML/CSS/JS w pojedynczych plikach.

## Strony w repozytorium

| Plik | Opis |
|---|---|
| `index.html` | Główna strona **BAVARO Bistro** (Ugory 23, Bydgoszcz) — dania obiadowe, pierogi, zupy, zapiekanki i pizza. |
| `pizzeria-menu.html` | Strona **BAVARO Pizzeria** (Al. Wojska Polskiego 20d, Bydgoszcz) — pełne menu pizzy (24/30/41 cm) i dodatków. |
| `plakat-60x110-pizza.html` / `.pdf` | Plakat reklamowy 60×110 cm (wariant pizza), gotowy do druku. |
| `plakat-60x110-obiady.html` / `.pdf` | Plakat reklamowy 60×110 cm (wariant dania obiadowe), gotowy do druku. |
| `robots.txt` | Konfiguracja dla robotów wyszukiwarek (wyklucza pliki plakatów z indeksowania). |

Obie strony HTML współdzielą ten sam system wizualny: ciemna paleta z złotym akcentem, fonty **Cormorant Garamond** (nagłówki) i **Jost** (tekst), zakładki kategorii w menu, sekcja z godzinami/lokalizacją/kontaktem.

## Struktura

Wszystko leży płasko w katalogu głównym — obrazy dań (`.png`/`.jpg`) są ładowane względnymi ścieżkami wprost z HTML, bez podfolderów `assets/` czy `img/`.

## Uruchomienie lokalnie

Żadnej instalacji ani build kroku — wystarczy otworzyć plik w przeglądarce:

```
index.html
pizzeria-menu.html
```

## Wdrożenie

- **bavarobistro.pl** — hosting FTP (seohost), pliki wgrywane przez WinSCP do katalogu `public_html`.
- **GitHub Pages** — to repozytorium, branch `main`, katalog `/ (root)`.

## SEO

`index.html` zawiera meta tagi (title/description/OG/Twitter Card), dane strukturalne JSON-LD (`Restaurant`) z adresem, godzinami i geolokalizacją oraz `robots.txt` blokujący indeksowanie plików plakatów.
