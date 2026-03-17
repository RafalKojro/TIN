# README — Responsywna strona internetowa (RWD)

## Opis projektu

Projekt przedstawia prostą, responsywną stronę internetową wykonaną w HTML i CSS. Strona demonstruje podstawowe zasady **Responsive Web Design (RWD)**, czyli takiego projektowania interfejsu, aby poprawnie wyświetlał się na różnych urządzeniach: komputerach, laptopach, tabletach i telefonach.

Strona zawiera:

* nagłówek z logo i menu nawigacyjnym,
* sekcję główną z informacją o aktualnym widoku responsywnym,
* trzy boksy treści,
* galerię z czterema przykładowymi obrazami ustawionymi jak na zrzucie ekranu,
* stopkę z informacją o prawach autorskich.

## Technologie użyte w projekcie

* **HTML5**
* **CSS3**
* **Google Fonts** — czcionka Roboto
* **CSS Grid**
* **Media Queries**
* **Transition i hover effects**

## Funkcjonalności

### 1. Układ responsywny

Strona dostosowuje układ do szerokości ekranu:

#### Duże ekrany (`> 992px`)

* 3 kolumny obok siebie,
* menu poziome,
* galeria w układzie 2x2.

#### Średnie ekrany (`768px - 992px`)

* 3 kolumny obok siebie,
* zmniejszone rozmiary czcionek,
* menu poziome.

#### Tablety (`576px - 768px`)

* elementy ustawione jeden pod drugim,
* menu hamburgerowe,
* galeria w układzie 2x2.

#### Telefony (`< 576px`)

* elementy ustawione jeden pod drugim,
* menu hamburgerowe,
* galeria w układzie 1x4,
* zmniejszone logo,
* mniejsze rozmiary czcionek.

### 2. Animacje CSS

W projekcie zastosowano podstawowe animacje i efekty przejść:

* efekt hover na linkach menu — zmiana koloru i podkreślenie,
* efekt hover na przyciskach — zmiana koloru tła,
* efekt hover na kartach — lekkie uniesienie i mocniejszy cień,
* efekt hover na obrazach w galerii — delikatne powiększenie.


### Menu mobilne

Menu hamburgerowe działa bez JavaScript, przy użyciu:

* ukrytego pola `checkbox`,
* etykiety `label`,
* selektora CSS `:checked`.

### Responsywność

Za zmianę układu odpowiadają zapytania `@media`, które modyfikują:

* liczbę kolumn,
* wielkość czcionek,
* układ galerii,
* rozmiar logo,
* sposób wyświetlania menu.


