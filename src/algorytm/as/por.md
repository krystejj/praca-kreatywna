# Porównanie

Oto **tabela porównująca** [**sortowanie bąbelkowe**](bab.md), [**przez wybór**](pwy.md), [**przez wstawianie**](pws.md) oraz [**stogowe**](stog.md).

| Cecha | Bąbelkowe | Przez Wybór | Przez Wstawianie | Stogowe |
|---|---|---|---|---|
| **Stabilność** | nie | nie | tak | tak |
| **Łatwość Implementacji** | łatwa | łatwa | łatwa | trudniejsza |
| **Wydajność** | mała | mała | mała | dobra |
| **Liczba Porównań** | wiele | wiele | wiele | mała |
| **Liczba Przesunięć** | wiele | mała | wiele | mała |
| **Wymagania Pamięciowe** | brak | brak | brak | dodatkowa pamięć na kopiec |

## Podsumowanie
[**Sortowanie bąbelkowe**](bab.md), [**przez wybór**](pwy.md) oraz [**przez wstawianie**](pws.md) są **prostymi i łatwymi do implementacji** algorytmami sortowania. Są one jednak stosunkowo **nieefektywne**, ponieważ wymagają wykonania wielu porównań i przesunięć elementów.

[**Sortowanie stogowe**](stog.md) jest **bardziej wydajnym** algorytmem, którego złożoność czasowa wynosi \\( O(n \log{n}) \\). Jest on jednak **bardziej złożony w implementacji i wymaga dodatkowej pamięci** na przechowywanie kopca.
