# Jak pracujemy w tym repo

To repo służy do robienia stron internetowych. Właścicielka wkleja plik DESIGN.md
(najczęściej z getdesign.md) i opisuje, jaką stronę chce. Ty robisz resztę.

## Gdy dostaniesz DESIGN.md i opis strony

1. Wymyśl krótką nazwę folderu (małe litery, bez polskich znaków, np. `kwiaciarnia-roza`).
2. Zapisz wklejony DESIGN.md bez zmian jako `strony/<nazwa>/DESIGN.md`.
3. Przeczytaj go w całości, zanim zaczniesz projektować.
4. Użyj skilla `landing-page-design` (`.claude/skills/landing-page-design/SKILL.md`).
5. Zbuduj stronę jako `strony/<nazwa>/index.html`: jeden samodzielny plik HTML
   (CSS i JS w środku, bez kroku budowania), chyba że poproszono inaczej.
6. Zrób zrzut ekranu strony (Playwright, szerokość 1440 i 390 px), obejrzyj go
   i popraw błędy, zanim oddasz pracę.
7. Zacommituj i wypchnij zmiany na swoją gałąź.

Jeśli DESIGN.md nie został wklejony, zapytaj o niego raz. Jeśli mimo to trzeba
działać, użyj ostatniego DESIGN.md z folderu `strony/` i napisz, który wybrałeś.

## Co ma pierwszeństwo

1. To, co właścicielka napisała w czacie.
2. **DESIGN.md** decyduje o wyglądzie: kolory, fonty, rozmiary tekstu, odstępy,
   zaokrąglenia, cienie, gradienty, styl przycisków i kart, nastrój.
   Jeśli skill mówi coś innego (np. zakazuje gradientów, narzuca fonty Geist/Manrope
   albo ciemne tła), wygrywa DESIGN.md.
3. **Skill landing-page-design** decyduje o tym, czego DESIGN.md nie określa:
   struktura strony, teksty, stany przycisków, animacje, dostępność, SEO,
   lista rzeczy przed oddaniem (B9, B10) i sekcja z hasłem (B11).

## Zasady

- Treść strony po polsku, chyba że poproszono inaczej. Regułę skilla „bez myślników”
  stosuj z umiarem: poprawna polska pisownia (np. „biało-czerwony”) jest ważniejsza.
- Nie wymyślaj faktów o prawdziwej firmie (ceny, opinie, liczby klientów).
  Jeśli ich brakuje, wstaw czytelny znacznik, np. `{{cena}}`, i wypisz je na końcu.
- DESIGN.md wzorowany na znanej marce traktuj jako inspirację stylu.
  Nie kopiuj jej nazwy, logo ani tekstów.
- Nie zmieniaj stron z innych folderów, jeśli o to nie poproszono.

## Na koniec napisz krótko

- gdzie jest nowa strona,
- jakie znaczniki `{{...}}` trzeba uzupełnić,
- czego nie udało się zrobić (jeśli czegoś).
