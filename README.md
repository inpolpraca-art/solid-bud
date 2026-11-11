# SolidBud — strona demonstracyjna

Klasyczna, elegancka strona dla firmy remontowo-wykończeniowej działającej w Warszawie. Projekt jest statyczny: HTML + CSS + JavaScript, bez instalacji i bez procesu budowania. Można go opublikować bezpośrednio na GitHub Pages.

## Uruchomienie
1. Rozpakuj ZIP.
2. Otwórz `index.html` w przeglądarce albo wrzuć wszystkie pliki do repozytorium GitHub.
3. W GitHub: **Settings → Pages → Deploy from a branch → main → /(root)**.

## Co koniecznie zmienić przed pokazaniem jako prawdziwej firmy
- W `index.html` zamień nazwę **SolidBud**, numer telefonu `+48 500 000 000` i e-mail `kontakt@solidbud.pl` na prawdziwe dane.
- W `scripts/main.js` zmień adres `mailto:kontakt@solidbud.pl` na prawdziwy e-mail.
- Zdjęcia w galerii i zdjęcie główne są poglądowe (Unsplash), a nie zdjęciami realizacji wykonawcy. Zastąp je własnymi fotografiami.
- Sekcja opinii zawiera wyraźnie oznaczony tekst demonstracyjny. Wstaw wyłącznie autentyczne opinie, za zgodą autorów.
- Dostosuj listę usług, obszar działania, dostępne terminy i treści do faktycznej oferty.

## Struktura
- `index.html` — wszystkie sekcje strony i SEO.
- `styles/style.css` — układ, responsywność i styl.
- `scripts/i18n.js` — polski (domyślny), angielski i ukraiński.
- `scripts/ui.js` — menu mobilne, filtry galerii, lightbox i tłumaczenia.
- `scripts/main.js` — inicjalizacja i formularz kontaktowy.
- `assets/` — favicon i miejsce na własne grafiki.

## Formularz
Formularz sprawdza wymagane pola i otwiera domyślny program pocztowy z przygotowaną wiadomością (`mailto:`). Nie wysyła danych na serwer. Jeśli chcesz otrzymywać zapytania bez otwierania programu pocztowego, podłącz usługę formularzy lub własny backend.

## Uwagi techniczne
- Tailwind CSS jest ładowany z CDN, a dodatkowy arkusz CSS odpowiada za charakterystyczny wygląd projektu.
- Zdjęcia i Google Fonts wymagają połączenia z internetem.
- Przed produkcyjnym wdrożeniem warto dodać prawdziwą politykę prywatności, jeśli strona będzie zbierać dane kontaktowe.
