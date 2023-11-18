# Złożoność Obliczeniowa

**Złożoność obliczeniowa** to miara ilości zasobów, których algorytm zużywa do wykonania zadania. Zasoby te mogą obejmować **czas, pamięć, przestrzeń dyskową, energię** itp. Złożoność obliczeniową wyrażamy używając [ **notacji Big O**](#notacja-big-o)

## Notacja Big O
**Notacja Big O** to sposób opisywania złożoności obliczeniowej. Służy ona do określania, **jak szybko algorytm wykonuje się** w zależności od wielkości danych wejściowych. Wykorzystuje ona symbole matematyczne do opisywania złożoności algorytmu.

### Przykłady
Najczęściej używane symbole to:
- \\( O(1) \\) - oznacza, że złożoność algorytmu jest **stała**, niezależnie od wielkości danych wejściowych.
- \\( O(n) \\) - złożoność algorytmu **rośnie liniowo** wraz z wielkością danych wejściowych.
- \\( O(n^2) \\) - złożoność algorytmu **rośnie kwadratowo** wraz z wielkością danych wejściowych.
- \\( O(\log{n}) \\) - złożoność algorytmu **rośnie logarytmicznie** wraz z wielkością danych wejściowych.

## Czasowa
**Czasowa złożoność algorytmu** to miara ilości czasu, jaką algorytm potrzebuje do **wykonania zadania**. Całkowity czas wykonania algorytmu **zależy od wielkości danych wejściowych**.

### Przykłady
Oto kilka przykładów **czasowej złożoności algorytmu**: 
- **algorytm sortowania przez wstawianie** ma złożoność \\( O(n^2) \\). Oznacza to, że czas wykonania algorytmu jest **proporcjonalny do kwadratu liczby elementów w wejściowej liście**.
- **algorytm sortowania szybkiego** ma złożoność \\( O(n \log{n}) \\). Oznacza to, że czas wykonania algorytmu jest **proporcjonalny do logarytmu naturalnego liczby elementów w wejściowej liście**.

## Pamięciowa
**Pamięciowa złożoność algorytmu** to miara ilości pamięci, jaką algorytm potrzebuje do **wykonania zadania**. **Może zależeć od wielkości danych wejściowych**.

### Przykłady
Oto kilka przykładów **pamięciowej złożoności algorytmu**: 
- **algorytm sortowania przez wstawianie** ma pamięciową złożoność \\( O(n) \\). Oznacza to, że algorytm **potrzebuje dodatkowej pamięci** proporcjonalnej do liczby elementów w wejściowej liście.
- **algorytm sortowania przez scalanie** ma pamięciową złożoność \\( O(\log{n}) \\). Oznacza to, że algorytm **potrzebuje dodatkowej pamięci** proporcjonalnej do logarytmu naturalnego liczby elementów w wejściowej liście.

## Inne Rodzaje
Oprócz **czasowej i pamięciowej** złożoności algorytmów, można również rozważyć **inne rodzaje** złożoności, takie jak:
- **przestrzenna** - miara ilości przestrzeni dyskowej, jakiej algorytm potrzebuje do wykonania zadania.
- **energii** - miara ilości energii, jakiej algorytm potrzebuje do wykonania zadania.
- **komunikacyjna** - miara ilości danych, które muszą być przesyłane między różnymi częściami algorytmu.

## Optymalizacja
**Optymalizacja złożoności** jest ważną częścią projektowania algorytmów. Celem optymalizacji złożoności algorytmu jest **zmniejszenie ilości zasobów**, które algorytm zużywa do wykonania zadania. Optymalizację złożoności można osiągnąć na **różne sposoby**, takie jak:
- **upraszczanie algorytmu** - usuwanie niepotrzebnych kroków lub operacji.
- **używanie bardziej efektywnych technik** - wybór technik, które są bardziej efektywne pod względem zużycia zasobów.
- **użycie równoległości** - wykorzystanie wielu procesorów do wykonania zadania równolegle.

## Podsumowanie
**Złożoność obliczeniowa** to bardzo przydatna miara ilości zasobów, dzięki której możemy **oszacować ile zasobów będzie potrzebował nasz algorytm** do wykonania zadania. Nie powinniśmy **nigdy jej ignorować**, lecz **zawsze brać ją pod uwagę**.
