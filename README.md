# TestCo — Landing Page

Prosty, jednostronicowy landing page dla testowej firmy TestCo. Projekt napisany w czystym HTML i CSS, bez frameworków i zależności.

## Struktura projektu

```
test-landing/
├── index.html      # Główny plik HTML
├── styles.css      # Style (jeden plik, custom properties)
├── README.md       # Ten plik
└── .gitignore
```

## Sekcje strony

- **Hero** — duży tytuł, podtytuł i wezwanie do działania (CTA).
- **O nas** — krótki opis firmy.
- **Usługi** — trzy karty prezentujące oferowane usługi (UI/UX, web development, strategia).
- **Kontakt** — prosty formularz kontaktowy (na razie wyłącznie wizualny, bez backendu).

## Design

Nowoczesny, minimalistyczny styl: dużo białej przestrzeni, neutralna paleta (czerń, biel, jasne szarości), responsywny układ oparty na CSS Grid i Flexbox. Sticky navbar z efektem `backdrop-filter`.

## Uruchomienie

Wystarczy otworzyć `index.html` w przeglądarce — żadna kompilacja nie jest potrzebna.

```bash
open index.html
```

## Dalsze kroki

- Podpięcie formularza pod realny endpoint (np. Formspree, własny backend).
- Dodanie własnych ikon SVG w sekcji usług.
- Optymalizacja pod SEO (meta tagi, Open Graph).
