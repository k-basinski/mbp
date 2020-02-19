# Przygotowanie danych do analizy

## Format pliku

- Format pliku: Excel (xls albo xlsx) albo csv

## Ogólne zasady 

- Obserwacja to jeden pomiar zmiennej zależnej dla danego poziomu danego czynnika
- Jeden wiersz w tabeli to jedna obserwacja
- Każda obserwacja powinna mieć id i wartość zmiennej zależnej
- Do tego w kolejnych kolumnach opisujemy czynniki

## Przykład 1

- N = 10
- Plan prosty, grupy niezależne
- Zmienna zależna: wynik testu pamięci
- Czynnik: pora dnia 
- 2 poziomy - rano (r) i wieczorem (w)

## Przykład 2

- N = 18
- Plan złożony 3x2, grupy niezależne
- Zmienna zależna: wynik testu pamięci
- Czynniki: pora dnia i manipulacja afektem
- 3 poziomy pory dnia: rano (r), w południe (p) i wieczorem (w)
- 2 poziomy afektu: pozytywny (p) i negatywny (n)

## Przykład 3

- N = 16
- Plan złożony 2x2x2, grupy niezależne
- Zmienna zależna: wynik testu pamięci
- Czynniki: pora dnia, manipulacja afektem, płeć
- 2 poziomy pory dnia: rano (r), w południe (p) i wieczorem (w)
- 2 poziomy afektu: pozytywny (p) i negatywny (n)
- 2 poziomy płci: kobieta (k) i mężczyzna (m)

## Powtarzane pomiary

- Jeśli ktoś ma plan z powtarzanymi pomiarami, musi mieć dwie kolumny id:
- id obserwacji (unikalne dla każdej obserwacji)
- id uczestnika (unikalne dla każdego uczestnika)

## Przykład 4

- N = 10
- Plan prosty z powtarzanym pomiarem
- Zmienna zależna: wynik testu pamięci
- Czynnik: obecność dystraktora
- 2 poziomy czynnika: dystraktor (d), brak dystraktora (bd)

## Przykład 5

- N = 10
- Plan złożony 2x2, powtarzany pomiar dla jednego czynnika (dystraktor)
- Zmienna zależna: wynik testu pamięci
- Czynniki: obecność dystraktora i płeć
- 2 poziomy dystraktora: dystraktor (d), brak dystraktora (bd)
- 2 poziomy płci: kobieta (k) i mężczyzna (m)



## Nazwy czynników

- Nazwy czynników powinny być krótkie i pisane z małej litery
- Bardzo ważne, żeby dla wszystkich obserwacji były one spójne
- 'rano', 'Rano', 'RANO' i 'rrano' to różne czynniki!
- Zmienne i czynniki powinny być opisane w treści maila, którego wysyłacie

## Ogólne uwagi 

- WSZYSTKO piszcie z małej litery
- Nie używajcie polskich znaków, znaków specjalnych ani spacji (pamiętacie reguły nazywania zmiennych w Pythonie?)
- Nie korzystamy z jakiegokolwiek formatowania w Excelu (przyciemnianie wierszy w materiałach tylko dla czytelności)
- Jeśli wprowadzacie dane liczbowe do Excela, pilnujcie przecinków! (. i , pełnią różne funkcje w zależności od wersji językowej)

## Najważniejsze

- Bądźcie pedantycznie poprawni! 
- Nie mam czasu poprawiać waszych błędów
- Jeżeli przygotujecie zbiór niechlujnie, nie zrobię wam analizy!
- W razie wątpliwości, pytajcie się mailowo

