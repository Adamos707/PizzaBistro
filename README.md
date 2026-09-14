# BAVARO Bistro & Pizzeria

Statyczna strona internetowa dla lokali BAVARO w Bydgoszczy — bez frameworków, bez build toola, czysty HTML/CSS/JS w pojedynczych plikach.

## Strony w repozytorium

| Plik | Opis |
|---|---|
| `pizzeria-menu.html` | Strona **BAVARO Pizzeria** (Al. Wojska Polskiego 20d, Bydgoszcz) — pełne menu pizzy (24/30/41 cm) i dodatków. |

## Struktura

Wszystko leży płasko w katalogu głównym — obrazy dań (`.png`/`.jpg`) są ładowane względnymi ścieżkami wprost z HTML, bez podfolderów `assets/` czy `img/`.

## Uruchomienie lokalnie

Żadnej instalacji ani build kroku — wystarczy otworzyć plik w przeglądarce:

```
pizzeria-menu.html
```

## Wdrożenie

- **bavarobistro.pl** — hosting FTP (seohost), pliki wgrywane przez WinSCP do katalogu `public_html`.
- **GitHub Pages** — to repozytorium, branch `main`, katalog `/ (root)`.

## SEO

`index.html` zawiera meta tagi (title/description/OG/Twitter Card), dane strukturalne JSON-LD (`Restaurant`) z adresem, godzinami i geolokalizacją oraz `robots.txt` blokujący indeksowanie plików plakatów.
