# SolidBud — GitHub Pages

Wersja poprawiona: wszystkie główne pliki strony znajdują się bezpośrednio w katalogu głównym repozytorium. Dzięki temu nie ma problemu z dodatkowym folderem `solidbud-demo/` ani ze ścieżką do CSS.

## Pliki
- `index.html`
- `style.css` — główny arkusz stylów, w katalogu głównym
- `i18n.js` — tłumaczenia PL / EN / UA
- `ui.js` — menu, filtry galerii, lightbox i zmiana języka
- `main.js` — formularz i inicjalizacja
- `favicon.svg`

## Publikacja
1. Rozpakuj ZIP.
2. Otwórz repozytorium GitHub i usuń poprzednie pliki strony (albo zastąp je plikami z tego ZIP).
3. Załaduj **zawartość** ZIP bez dodatkowego folderu nadrzędnego. `index.html` i `style.css` muszą być obok siebie на najwyższym уровне репозитория.
4. В Settings → Pages выбери нужную ветку и `/ (root)`.
5. Подожди завершения деплоя и обнови страницу через `Ctrl + F5`.

## Важно перед публикацией
Название SolidBud, телефон, e-mail и фото демонстрационные. Замени их на реальные. Отзывы также демонстрационные. Форма использует `mailto:` и открывает почтовую программу, серверной отправки нет.

Tailwind подключается через CDN, поэтому для отображения его utility-классов требуется интернет. Основной визуальный стиль находится в локальном `style.css`.


## Responsywność
Dodano dodatkowe reguły mobilne dla małych ekranów (w tym 340–420 px), formularza, menu, galerii, FAQ i lightboxa. Po podmianie plików odśwież stronę przez Ctrl+F5.


## Styl wizualny
Najnowsza wersja używa spokojnej, monochromatycznej palety czerni i bieli, prostszych detali, ograniczonych cieni i bardziej naturalnych odstępów. Układ, tłumaczenia i funkcje strony pozostają zachowane.


## Kierunek projektu
Układ inspirowany strukturą stron referencyjnych: duże zdjęcia, wyrazisty hero, sekcje z numeracją, galeria, proces współpracy, opinie i mocny blok kontaktowy. Projekt zachowuje własną identyfikację SolidBud.


## Aktualizacja nagłówka
Nagłówek ma ciemne tło, nawigację w obrysowanych kapsułach, przełącznik języków i widoczny przycisk „Zadzwoń”. Przed publikacją zmień numer `+48500000000` w `index.html` i `scripts/main.js` (jeśli występuje) na numer wykonawcy.


## Ciemna wersja — poprawki
Cała strona ma teraz ciemną paletę monochromatyczną. Usługi mają większą typografię i wyraźniejsze, kontrastowe karty. Linki nawigacyjne nie mają obramowań; ramki pozostają tylko przy przełączniku języka i przycisku telefonu. Usunięto komunikat o zdjęciach poglądowych pod galerią.


## Stopka i nawigacja
Dodano responsywną nawigację w stopce, skróty do wszystkich głównych sekcji, blok kontaktowy oraz link powrotu na górę. Etykiety stopki są tłumaczone razem z językiem strony (PL / EN / UA).


## Zmieniane zdjęcia w sekcji głównej
Pierwsza sekcja ma teraz pełnoekranowe tło fotograficzne z trzema zdjęciami wnętrz. Zdjęcia płynnie przełączają się co 6 sekund, a ciemna nakładka utrzymuje czytelność tekstu. Obrazy można podmienić w `index.html` w elementach `.hero-slide`.
