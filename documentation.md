Podsumowanie spostrzezen

Zadanie 1:

Funkcja G jest funkcją 2 zmiennych, więc z góry można założyć, że ciężej ją bedzie zoptymalizować.
Ale ma ona tylko jedno minimum, co ułatwia sprawę.

Za to funkcja F jest funkcją 1 zmiennej, ale ma wiele minimum lokalnych, co powoduje, że algorytm może się zatrzymać w którymś z nich przez
co nie znajdzie minimum globalnego, a jedynie lokalne.

Trudnosc zoptymalizowania funkcji 2 zmiennych jest latwiejsza niz zoptymalizowanie funkcji z wieloma minimami lokalnymi.

Wiec ostatecznie trudniejsza do zoptymalizowania jest funkcja F ze wzgledu na jej wiele minimów lokalnych.

Zadanie 2:

Funkcja F ma minimum globalne w: -0.4149116040378343
Funkcja G ma minimum globalne w: [ 5.43656366 -2.7182818 ]


Zadanie 3:

Wplyw rozmiaru skoku na wyniki:

Dla funkcji F:

Czestosc znajdowania minimum:
- Dla wartosci skoku powyzej 1 minimum globalne nie jest znajdowane wcale albo bardzo w niewielu przypadkach
- Najczesciej znajdowane jest dla skoku okolo 0.1

Liczby iteracji:
- Dla wartości skoku przy której znajdowane najczęściej było minimum globalne liczba iteracji jest stosunkowa mała zazwyczaj
- Najszybciej znajdowane jest minimum globalne dla wartości skoku okolo 0.1

Dla funkcji G:

Czestosc znajdowania minimum:
- Dla wartosci skoku powyzej 1 albo bardzo malych wartosci skoku algorytm nie znajduje minimum wcale dla zadnego punktu
- Dla wartosci mniejszych niz 1 znajduje je w 100% dla kazdego punktu startowego z przedzialu.

Liczby iteracji:
- Liczba iteracji jest stosunkowo mała zazwyczaj w okolicach (10-50) i znalezione zostaje minimum w 100% dla wartosci skokow mniejszych niz 1
- Dla wartosci skoku wiekszych niz 1 jest to maksymalna liczba iteracji i minimum nie jest znalezione wcale

