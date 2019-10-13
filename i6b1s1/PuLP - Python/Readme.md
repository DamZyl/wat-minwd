Przykład biblioteki do rozwiązywania problemów optymalizacyjnych w języku Python.
Nazwa biblioteki: PuLP
Autor: Damian Żyłka I6B1S1

PuLP Python 

	Jest to biblioteka open source. Biblioteka stworzona do rozwiązywania problemów optymalizacji. Biblioteka zostala napisana w Pythonie. Wspiera wiele open source’owych solverów programowania liniowego takich jak CBC, GLPK oraz wspiera komercyjne solvery takie jak Gurobi, CPLEX. Domyślnym solverem jest CBC, który jest instalowany z biblioteką. Występują następujące statusy w domyślnym solverze:
    • Nie rozwiązane
    • Optymalne
    • Niemożliwy
    • Bezgraniczny
    • Nieokreślony

Autorzy:
    • Stuart Mitchell
    • Anita Kean
    • Andrew Manson
    • Michael O’Sullivan
    • Anthony Phillips

Link do dokumentacji: pythonhosted.org/PuLP

Przykład użycia:

Szukanie maksymalnego rozwiązania dla funkcji: Z = 4x + 3y
Dla ograniczeń:
x >= 0
y >= 2
2y <= 25 – x
4y >= 2x – 8
y <= 2x - 5 
