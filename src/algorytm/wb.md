# Wyszukiwanie Binarne

**Wyszukiwanie binarne** to [algorytm](index.html) wyszukiwania, który działa poprzez wielokrotne **dzielenie zbioru danych na połowę**, aż do znalezienia szukanego elementu.

Animacja pokazująca działanie **wyszukiwania binarnego**:

<img style="border: 1px solid rgb(49, 49, 49); border-radius: 20px;" src="https://upload.wikimedia.org/wikipedia/commons/c/c1/Binary-search-work.gif">

## Cechy

### Złożoność Czasowa
**Złożoność czasowa** wyszukiwania binarnego wynosi \\( O(\log{n}) \\), gdzie \\( n \\) jest liczbą elementów w zbiorze. Oznacza to, że czas wykonania algorytmu jest **proporcjonalny do logarytmu liczby elementów w zbiorze**.

### Złożoność Pamięciowa
**Złożoność pamięciowa** wyszukiwania binarnego wynosi \\( O(1) \\). Oznacza to, że algorytm **nie wymaga dodatkowej pamięci** poza pamięcią wymaganą do przechowywania danych wejściowych.

### Stabilność
**Wyszukiwanie binarne** jest **niestabilnym** algorytmem wyszukiwania. Oznacza to, że kolejność elementów o równej wartości **może zostać zaburzona**.

## Sposób Działania
**Wyszukiwanie binarne** jest algorytmem wyszukiwania, który działa w następujący sposób:
1. **przekazanie danych** - pierwszym krokiem algorytmu jest przekazanie danych do wyszukiwania. Przekazany zbiór danych **musi być uporządkowany rosnąco**.
2. **wyznaczanie zakresu wyszukiwania** - kolejnym krokiem jest określenie zakresu wyszukiwania. Zakres wyszukiwania to zbiór elementów, w których może znajdować się szukany element.
3. **porównanie szukanego elementu z elementem środkowym** - algorytm zaczyna od porównania szukanego elementu z elementem środkowym zakresu wyszukiwania:
    - jeśli szukany element jest równy elementowi środkowemu, algorytm **kończy działanie**,
    - jeśli szukany element jest mniejszy niż element środkowy, algorytm **ogranicza zakres wyszukiwania do lewej połowy zbioru**,
    - jeśli szukany element jest większy niż element środkowy, algorytm **ogranicza zakres wyszukiwania do prawej połowy zbioru**.
4. **powtarzanie kroków 2 i 3** - algorytm powtarza kroki 2 i 3, aż znajdzie szukany element lub do momentu, gdy zakres wyszukiwania będzie pusty.

## Podsumowanie
<iframe width="560" height="315" style="border: 1px solid rgb(49, 49, 49); border-radius: 20px;" src="https://www.youtube-nocookie.com/embed/KXJSjte_OAI?si=VtpShWO7nOWzdUse" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Wyszukiwanie binarne** jest bardzo wydajnym algorytmem wyszukiwania, który jest **często używany w praktyce**. Jest on szczególnie przydatny do **wyszukiwania elementów w uporządkowanych zbiorach danych**.
