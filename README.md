# Kotki Dwa — strona na GitHub Pages

Statyczna strona behawiorystki kotów (Natalia, PAZiA). Czysty HTML + CSS, bez zależności i buildów. Opublikowana na GitHub Pages pod adresem:

**https://wilawerek.github.io/kotkidwa/**

## Podgląd lokalnie

```sh
python3 -m http.server 8000
```

i otwórz http://localhost:8000 w przeglądarce.

## Publikacja

Strona jest publikowana automatycznie z gałęzi `main` (GitHub Pages, deploy from branch). Wystarczy:

```sh
git push origin main
```

Pierwsze opublikowanie strony trwa zwykle ok. 1 minuty (Settings → Pages).

## Struktura

```
index.html        # landing page (wszystkie sekcje)
style.css         # paleta i style (bez zewnętrznych zasobów)
assets/           # logo + zdjęcia
```

## Paleta

Kolory są spójne z motywem WordPress `kotkidwa-child` (theme.json) — 12 kolorów jako zmienne CSS w `:root` (`--blue-primary`, `--teal`, `--pink-light` itd.).

## Własna domena (opcjonalnie, na później)

Dodaj plik `CNAME` z domeną (np. `kotkidwa.pl`) i ustaw rekord DNS u dostawcy — GitHub Pages poda HTTPS automatycznie.

## Do zrobienia / pomysły

- Formularz wstępny przed konsultacją (np. przez Formspree)
- Materiały do pobrania dla opiekunów (PDF)
- Podstrony: blog / artykuły
- Integracja rezerwacji (Calendly)