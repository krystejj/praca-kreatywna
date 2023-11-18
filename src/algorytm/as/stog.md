# Sortowanie Stogowe

**Sortowanie stogowe**, zwane również **sortowaniem przez kopcowanie**, to algorytm sortowania, który działa poprzez przekształcanie zbioru nieuporządkowanego w kopiec binarny. Kopiec binarny to struktura danych, w której każdy element jest większy lub równy swoim dzieciom.

Animacja pokazująca działanie **sortowania stogowego**:

<img style="border: 1px solid rgb(49, 49, 49); border-radius: 20px;" src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Sorting_heapsort_anim.gif">

## Cechy

### Złożoność Czasowa
**Złożoność czasowa** sortowania stogowego wynosi \\( O(n \log{n}) \\), gdzie \\( n \\) jest liczbą elementów w zbiorze. Oznacza to, że czas wykonania algorytmu **jest proporcjonalny do logarytmu liczby elementów w zbiorze**.

## Złożoność Pamięciowa
**Złożoność pamięciowa** sortowania stogowego wynosi \\( O(n) \\). Oznacza to, że algorytm **wymaga dodatkowej pamięci** w ilości proporcjonalnej do liczby elementów w zbiorze.

## Stabilność
**Sortowanie stogowe** jest **stabilnym** algorytmem sortującym. Oznacza to, że kolejność elementów o równej wartości **nie zostanie zaburzona**.

## Sposób Działania
**Sortowanie stogowe** jest algorytmem sortującym, który działa w następujący sposób:
1. **przekazanie danych** - pierwszym krokiem algorytmu jest przekazanie danych do sortowania. W przypadku sortowania stogowego dane mogą być reprezentowane przez dowolną strukturę danych, która umożliwia dostęp do kolejnych elementów na przykład tablica.
2. **konstrukcja stogu** - kolejnym krokiem jest skonstruowanie stogu z elementów zbioru. Stóg jest strukturą danych, która umożliwia dostęp do elementów w kolejności od największego do najmniejszego.
3. **usuwanie elementów ze stogu** - algorytm zaczyna od usuwania elementu o największej wartości ze stogu. Następnie, element ten jest dodawany na koniec zbioru. Algorytm powtarza te kroki, aż stóg będzie pusty.

## Podsumowanie
**Sortowanie stogowe** jest algorytmem sortującym, który jest **stabilnym** i **działa w czasie rzędu** \\( O(n \log{n}) \\). Jest to **wydajny algorytm**, który można zastosować w przypadku **dużych zbiorów danych**.
