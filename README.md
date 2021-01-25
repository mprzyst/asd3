# zadanie z algorytmów i struktur danych 3

Zadanie 1:
ułożenie planu zajęć tak, by aula wykładowa była wykorzystana w maksymalnym stopniu (maksymalny czas trwania wykładów)
zastosowane metody: programowanie dynamiczne

Plik wejściowy:
pierwsza liczba - łączna ilość potencjalnych wykładów
dalej - przedziały czasowe [p,k)
gdzie: p - godzina rozpoczęcia, k - godzina zakończenia

Przykład:
12
[1,2), [3,5), [0,4), [6,8), [7,13), [4,6), [9,12), [11,14), [15,19), [14,16), [18,20)


Plik wyjściowy:
pierwsza liczba - maksymalny czas trwania wykładów 
wykłady (przedziały czasowe wykładów)

Przykład:

Maksymalny czas trwania wykładów: 16
Wykłady: [0,4), [4,6), [7,13), [15,19)


Zadanie 4:
proces decyzyjny w fabryce papieru odnośnie cięcia dużych arkuszy papieru na mniejsze
zastosowana metody: metoda zachłanna

Plik wejściowy in1.txt:
● pierwsza linia zawiera dwie przedzielone znakiem spacji dodatnie liczby całkowite: m (ilość
części mniejszych dużego arkusza w pionie) i n (ilość części mniejszych dużego arkusza w
poziomie). Liczby spełniają warunek 2 ≤ m, n ≤ 1 000.
● w kolejnej linii znajduje się m-1 liczb naturalnych reprezentujących koszty cięć pionowych
x1, x2, ..., xm-1. Wiadomo, że xi ≤ 1 000,
● w ostatniej linii znajduje się n-1 liczb naturalnych reprezentujących koszty cięć poziomych
y1, y2, ..., yn-1. Wiadomo, że yi ≤ 1 000

Plik wyjściowy out1.txt:
● pierwsza linia zawiera minimalny koszt pocięcia dużego arkusza papieru.
