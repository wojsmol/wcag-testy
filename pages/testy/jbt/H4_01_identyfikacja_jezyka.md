---
title: Określenie języka

summary: "Cała treść strony umieszczona jest w oznaczonych głównych obszarach (punktach orientacyjnych)."
sidebar: testy_sidebar
permalink: H4_01_identyfikacja_jezyka
folder: testy/jbt
---


## Określenie języka

### Metoda badania: 
Kontrola wzrokowa. Inspekcja kodu HTML. 

## Założenia, zastrzeżenia lub wyjątki
_do opracowania_

## Obsługa dostępności
_do opracowania_

### Oczekiwania:
Kryterium sukcesu: [3.1.1 Język strony](https://wcag.lepszyweb.pl/#language-of-page), kryterium sukcesu: [3.1.2 Język części](https://wcag.lepszyweb.pl/#language-of-parts).

- Element `<html>` zawiera atrybut języka `lang`, a określony w nim język pasuje do głównego języka strony. 
- Treść w innych językach ma odpowiednio zdefiniowany atrybut językowy na elemencie obejmującym fragment innojęzyczny. 

### Procedura testowania: 
1.	Przeglądając treść strony, zidentyfikuj domyślny naturalny język strony. Domyślnym jest język, w którym prezentowana jest większość treści.
2.	Zobacz źródło strony i sprawdź, czy w znaczniku `<html>` zdefiniowany jest atrybut `lang`.
3.	Sprawdź, czy wartość atrybutu `lang` odpowiada domyślnemu językowi strony.
4.	Przejrzyj ponownie stronę i sprawdź, czy pojawiają się na stronie pojedyncze słowa lub zestawienia słów w innych językach, niż naturalny język strony.
5.	Korzystając z funkcji Zbadaj element w przeglądarce, sprawdź, czy każdy znaleziony innojęzyczny element strony został objęty odpowiednim znacznikiem z poprawną wartością atrybutu `lang`.


### Zasoby

#### Pomocne narzędzia:
- skryptozakładka [Images](http://pauljadam.com/bookmarklets/index.html)  z kolekcji Paula J. Adama
- skryptozakładka [Lang Favlet](https://labs.levelaccess.com/index.php/Category:Favlet) z kolekcji Level Access
- opcja *structure* w skryptozakładce ANDI  https://www.ssa.gov/accessibility/andi/help/install.html 

#### Wykorzystanie skryptozkładki ANDI
![Wykorzystanie skryptozkładki ANDI](/img/andi_lang.png) 
1.	Uruchom skryptozakładkę ANDI i wybierz z menu opcję *structure*. 
2.	Wybierz z menu poziomego opcję  *more details*  (więcej szczegółów).
3.	Wybierz z rozwijanej listy opcję *page language* (język strony) 
4.	Sprawdź w oknie dialogowym, czy domyślny język strony  został określony poprawnie.

#### Techniki WCAG 2.1
-   [H57: Używanie atrybutu lang dla elementu html](https://www.w3.org/WAI/WCAG21/Techniques/html/H57.html)
-   [H58: Używanie atrybutu lang do wskazywania zmian w języku naturalnym](https://www.w3.org/WAI/WCAG21/Techniques/html/H58.html)
-   [FLASH13: Użycie atrybutów lang HTML w celu określenia języka treści we Flashu](https://www.w3.org/WAI/WCAG21/Techniques/flash/FLASH13.html)

### Przypadki testowe

#### Zaliczone
_do opracowania_

#### Niezaliczone
_do opracowania_ 