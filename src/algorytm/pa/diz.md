# Dziel i Zwyciężaj

**Dziel i zwyciężaj** to metoda [**projektowania algorytmu**](index.html), która polega na **podziale problemu na mniejsze podproblemy**, które są następnie rozwiązywane rekurencyjnie. Jest ona najczęściej używana do projektowania algorytmów sortujących.

## Sposób Działania
Metoda **dziel i zwyciężaj** działa w następujących etapach:
1. problem dzieli się na **mniejsze podproblemy**.
2. podproblemy są **rozwiązywane rekurencyjnie**.
3. rozwiązania podproblemów są **łączone**, aby uzyskać rozwiązanie problemu oryginalnego.

## Zalety
**Dziel i zwyciężaj** ma następujące zalety:
- jest często **efektywna**, ponieważ rozwiązuje problem poprzez rozwiązanie jego mniejszych podproblemów,
- jest **prosta do zaimplementowania**.

## Wady
**Dziel i zwyciężaj** ma również wady:
- może być **trudna do zrozumienia** dla początkujących programistów,
- może **wymagać dużej ilości czasu**, jeśli podproblemy są duże.

## Przykład Zastosowania
Przykładem zastosowania metody **dziel i zwyciężaj** może być **algorytm sortowania przez scalanie**. Algorytm ten działa w następujący sposób:
1. jeśli tablica zawiera tylko jeden element, to **jest on już posortowany**.
2. jeśli tablica zawiera więcej niż jeden element, to **jest ona dzielona na dwie połowy**.
3. każda połowa jest **sortowana rekurencyjnie**.
4. dwie posortowane **połowy są scalane** w jedną posortowaną tablicę.

**Algorytm sortowania przez scalanie** można zaprojektować używając metody **dziel i zwyciężaj** za pomocą następujących kroków:
1. **zdefiniuj problem** - w tym przypadku problemem jest sortowanie tablicy liczb.
2. **zidentyfikuj przypadek bazowy** - w przypadku sortowania przez scalanie przypadkiem bazowym jest tablica zawierająca tylko jeden element.
3. **zdefiniuj przypadek rekurencyjny** - przypadkiem rekurencyjnym jest tablica zawierająca więcej niż jeden element.
4. **napisz kod dla przypadku rekurencyjnego** - kod dla przypadku rekurencyjnego dzieli tablicę na dwie połowy i wywołuje funkcję sortowania rekurencyjnie dla każdej połowy.
5. **napisz kod dla przypadku bazowego** - kod dla przypadku bazowego po prostu zwraca tablicę.

## Podsumowanie
Metoda **dziel i zwyciężaj** to potężna metoda projektowania algorytmów, która może być używana do rozwiązywania **wielu różnych problemów**. Nie ma problemu, którego nie moglibyśmy rozwiązać używając tej metody.
