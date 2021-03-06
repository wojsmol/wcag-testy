---
title: 1-3-1 Informacje i relacje


sidebar: testy_sidebar
permalink: 1-3-1_Informacje-i-relacje
folder: testy/adept
---

## Test
**Czy informacje, relacje i ich struktura są możliwe do odczytania przez program komputerowy lub w inny sposób opisane?**

## Wyjaśnienie
Informacja prezentowana na stronach internetowych wymaga czasem, by zorientować się w relacjach pomiędzy różnymi jej elementami. Przykładem może być układ tabelaryczny danych, gdy informacja z konkretnej komórki ma sens tylko wtedy, gdy jesteśmy w stanie określić w którym rzędzie i w której kolumnie się znajduje. Do tego trzeba określić, które komórki mają charekter nagłówkowy, czyli opisują zawartość kolumn i wierszy. Jeżeli taka tabela zostanie zaprojektowana za pomocą znaczników HTML definiujących tabelę, rzędy, komórki i komórki nagłówkowe, to program jest w stanie odczytać takie informacje. Jeżeli zaś są to dane rozmieszczone wizualnie za pomocą arkuszy stylów, to tylko widzący człowiek będzie w stanie określić zależności pomiędzy danymi. Dlatego wizualna prezentacja informacji musi korelować z jej strukturą semantyczną zapisaną w kodzie strony.

## Testowanie
Sprawdzenie tego warunku wymaga dosyć dokładnego przyjrzenia się różnym elementom serwisu internetowego. Do szczególnie narażonych na zaburzenia należą tabele i formularze. Do testowania można wykorzystać bezpłatny czytnik ekranu NVDA. Za jego pomocą spróbuj odczytać tabele i formularze znajdujące się w serwisie. Przy domyślnych ustawieniach NVDA przemieszczanie się pomiędzy komórkami tabeli generuje komunikaty z nazwami kolumn i wierszy. Możesz też zauważyć, że coś wyglądającego na tabelę wcale nią nie jest i nie pozwala na odczytywanie prawidłowo informacji. W wypadku formularzy kluczowe jest połączenie etykiet dla pól z samymi polami. Opieranie się tylko na sposobie wyświetlania etykiet może być mylące, więc warto skorzystać z narzędzia do walidacji dostępności WAVE Toolbar. Program wskaże między innymi na elementy formularzy, do których nie są przypisane etykiety. Jeżeli taki błąd się pojawi, to znaczy że nie ma relacji pomiędzy polem formularza a jego etykietą.

